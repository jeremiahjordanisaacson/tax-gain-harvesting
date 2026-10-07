# Tax-Gain Harvesting 🌾

A short, free, farm-themed reference for **tax-gain harvesting** — the retirement/tax
strategy of deliberately realizing **long-term capital gains** while they fall inside the
federal **0% long-term capital-gains bracket**. Three self-contained HTML pages, no
dependencies, no build step, no tracking.

**Live site:** <https://jeremiahjordanisaacson.github.io/tax-gain-harvesting/>

## The idea in one breath

The IRS taxes *long-term* capital gains at **0%** as long as your **taxable income** stays
under a threshold — and because that threshold is based on *taxable* income, the **standard
deduction comes first**. In a low-income year (classically, early retirement before pensions,
Social Security, and required distributions kick in) you can *intentionally* sell appreciated
stock, realize the gain at **0% federal tax**, optionally **buy it right back** to reset your
cost basis higher, and repeat. Money that would have gone to taxes stays invested and keeps
compounding.

> **Gain, not proceeds.** If you bought at \$100k and it's now worth \$200k, selling all
> \$200k is only a **\$100k** gain — the first \$100k is your cost basis. Depending on basis,
> you may be able to *sell* far more stock than the gain limit.

## 2026 quick numbers

| Filing status | 0% LTCG top (taxable income) | Standard deduction | ≈ Gross LTCG at 0% with no other income |
|---|---:|---:|---:|
| Single / MFS | \$49,450 | \$16,100 | **~\$65,550** |
| Married filing jointly | \$98,900 | \$32,200 | **~\$131,100** |
| Head of household | \$66,200 | \$24,150 | **~\$90,350** |

Gift tax annual exclusion: **\$19,000** per recipient (\$38,000 for a married couple splitting).
Lifetime gift/estate exemption: **\$15,000,000** per person. *(2026, per IRS Rev. Proc. 2025-32.
Figures change every year with inflation.)*

## Contents

| File | What |
|------|------|
| [`index.html`](index.html) | Landing page linking to the two below |
| [`harvest_guide.html`](harvest_guide.html) | Long-form guide: the 0% bracket, gain vs. basis, the harvest loop, the math, a live calculator, the gifting play, and the catches |
| [`harvest_training_quest.html`](harvest_training_quest.html) | Interactive four-phase quest map with progress tracking |

Read the guide first, then walk the quest to internalize it.

## Running locally

Open any of the HTML files directly in a browser. There is no build step, no server, no
JavaScript dependencies.

```bash
# macOS
open index.html

# Windows (PowerShell)
Start-Process .\index.html
```

## Disclaimer

**Educational content only — not tax, legal, or investment advice.** Tax outcomes depend on
your complete, individual situation, and the rules change every year. Realizing a gain at a
0% *federal* rate can still raise your AGI/MAGI (affecting ACA subsidies, taxation of Social
Security, and Medicare IRMAA) and does not mean your *state* charges nothing. Always run your
actual numbers and consult a licensed CPA or tax advisor before acting.

## License

The content of this site is provided as-is for educational purposes. You may read, share,
and adapt it for personal use.
