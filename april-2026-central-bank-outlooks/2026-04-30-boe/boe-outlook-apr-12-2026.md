# Dodona Outlook: BoE April 2026

**Note generated:** 2026-04-12
**Decision date:** 2026-04-30
**18 days before decision — OUTLOOK (not for publication)**

---

## Summary

**Predicted direction:** hold

**Direction confidence:** 49% [39%, 56%]

*This is an outlook, not a sealed forecast. The decision is more than two weeks away; material new evidence may arrive before the seal date.*

## Actor Stance Snapshot

Cutoff: 2026-04-30. All evidence below predates this date. Strict temporal holdout enforced at the data layer.

| Actor | Role | Stance | Confidence | Basis |
|-------|------|--------|-----------|-------|
| bailey-andrew | governor | neutral | 85% | forecast-2026-04-12-boe |
| breeden-sarah | deputy-governor | dovish | 47% | forecast-2026-04-12-boe |
| dhingra-swati | external-member | dovish | 50% | forecast-2026-04-12-boe |
| greene-megan | external-member | hawkish | 50% | forecast-2026-04-12-boe |
| mann-catherine | external-member | hawkish | 90% | forecast-2026-04-12-boe |
| pill-huw | chief-economist | hawkish | 51% | forecast-2026-04-12-boe |
| ramsden-dave | deputy-governor | dovish | 55% | forecast-2026-04-12-boe |
| taylor-alan | external-member | dovish | 45% | forecast-2026-04-12-boe |

## Policy Cycle

- **Current cycle:** neutral
- **Previous decision:** hold
- **Chair stance:** neutral

## Economic Indicators

| Indicator | Value | Date |
|-----------|-------|------|
| cpi | 3.0% | 2026-03-26 |
| unemployment | 4.4% | 2026-03-18 |
| bank-rate | 3.75% | 2026-03-18 |
| gdp | 0.1% | 2026-03-13 |

**Indicator signal:** hike at strength 0.4

## Equilibrium

| Outcome | Probability |
|---------|-------------|
| hold | 49% |
| cut-25 | 17% |
| hike-25 | 17% |
| hike-50 | 11% |
| cut-50 | 7% |

**Direction probabilities:** cut 24% / hold 49% / hike 27%

## Convergence Conditions

- **Chair stance:** neutral
- **Equilibrium direction:** hold
- **Indicator direction:** hike
- **Previous decision:** hold

## Summary Reasoning

The system evaluated 8 voting members in a policy cycle currently classified as **neutral**. The chair's stance is **neutral**. The equilibrium produces a **hold** prediction at 49% confidence, supported by a hike indicator signal at strength 0.4.

## Macro Backdrop

As of Apr 12, 2026, the BoE MPC is evenly split 4 hawk / 1 neutral / 4 dove but united on hold by the Iran war energy shock. The February 5-4 split (doves wanted to cut) collapsed to a unanimous 9-0 hold in March. Hawks (Pill, Mann, Greene, Lombardelli) see second-round inflation risks from energy passthrough + 3.6% pay settlements. Doves (Ramsden, Breeden, Dhingra, Taylor) believe disinflation was nearly complete before the Iran shock and want to resume cutting once the picture clears. Bailey (neutral) pushed back on market hike pricing ('getting ahead of themselves'). The most likely April 30 outcome is another hold, potentially unanimous. A hike is very unlikely absent a major CPI surprise (March CPI due April 16). If energy prices moderate, doves could push for a cut as early as June.

## Institutional Dynamic

*Context that the equilibrium math does not capture but should inform interpretation:*

The BoE April 30 meeting includes the Monetary Policy Report (MPR), which means new forecasts and fan charts. The MPR will incorporate the first post-Iran macro projections, which could shift the narrative significantly depending on the inflation and growth outlook. If the MPR projects CPI above 3% through 2026, hawks gain leverage; if it projects a growth slowdown absorbing the inflation, doves gain leverage. The MPR is often the single biggest input to MPC decisions at these meetings — more than individual member speeches.

## Key Uncertainty Flags

- **Outlook mode**: this is not a sealed prediction. The decision is more than two weeks away.
- Voting member rosters are hand-coded in `actors.edn` for this specific forecast. Any personnel changes not yet reflected are a coverage gap.

## Market Consensus Snapshot (April 12, 2026)

| Source | Hold | Hike | Cut | Notes |
|--------|------|------|-----|-------|
| [Polymarket](https://polymarket.com/event/bank-of-england-decision-in-april) | 95% | 5% | <1% | $404K volume |
| Reuters survey (50 economists) | 90% | 10% | 0% | JP Morgan: April "too soon" for hike majority |
| SONIA-implied | ~95-100% | ~0-5% | ~0% | ~78bp cumulative hikes priced for full-year 2026, concentrated H2 |
| Oxford Economics | Hold through 2026 | — | — | Hold at 3.75% "well into 2027" |
| Goldman / Citi | Hold through 2026 | — | — | Shifted from 3 cuts to 0 cuts |

### Dodona vs Market

| Outcome | Dodona | Market range | Divergence |
|---------|--------|-------------|------------|
| Hold | **49%** | 90-95% | **Dodona much less confident in hold** |
| Hike | **27%** | 5-10% | **Dodona sees 3-5x the hike probability** |
| Cut | **24%** | <1% | **Dodona sees a significant dovish tail** |

**Largest divergence: both tails.** Dodona assigns only 49% to hold vs markets' 90-95%. The 4-hawk/1-neutral/4-dove MPC split produces a nearly symmetric distribution where markets see overwhelming hold. The dovish tail (24%) reflects Ramsden/Breeden/Dhingra/Taylor's frustrated desire to resume cutting. The hawkish tail (27%) reflects Pill/Mann/Greene/Lombardelli's inflation persistence concern. Markets are pricing certainty that Dodona's actor-level analysis doesn't support.

## Methodology Reference

This outlook uses the methodology described in Casu, J. (2026), "Institutional Actor Modeling in Dodona: A Central Bank Rate Policy Case Study, 2024-2026."

Parameters are locked as of the hindcast paper submission. No adjustment has been made for this prediction.

The evidence used to generate this outlook is in the companion file `actors.edn` in this directory.

---

*Dodona is a symbolic cognitive reasoning system for institutional actor modeling. This note is a research output, not investment advice.*
