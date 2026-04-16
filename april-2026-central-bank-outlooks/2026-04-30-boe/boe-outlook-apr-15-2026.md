# Dodona Outlook: BoE April 2026

**Published:** 2026-04-15
**Decision date:** 2026-04-30
**15 days before decision — OUTLOOK**

---

## Summary

**Predicted direction:** hold

**Direction confidence:** 49% [39%, 56%]

*This is a daily outlook generated against the current evidence base. Material new evidence between now and the decision date may shift the predicted direction and/or confidence. A sealed forecast will be published at T-7 days and will not be updated thereafter.*

## Actor Stance Snapshot

Cutoff: 2026-04-30. All evidence below predates this date. Strict temporal holdout enforced at the data layer. Actors marked ⚬ contribute evidence but do not vote in this meeting's equilibrium (either non-voting governors or members outside the current rotation).

| Actor | Role | Stance | Confidence | Basis |
|-------|------|--------|-----------|-------|
| bailey-andrew | governor | neutral | 85% | *2026-04-01* — Apr 1 Reuters: pushed back against market hike pricing, said traders are 'getting ahead of themselves.' Focus on growth and jobs risks as well as inflation. Described shift from pre-war easing path as 'intensely frustra… |
| breeden-sarah | deputy-governor | dovish | 47% | *2026-03-18* — Voted for 25bp cut in February (dissent). March minutes: 'absent the shock, the underlying disinflation process had continued broadly as expected and she would have expected to vote for a cut again.' Dovish stance intac… |
| dhingra-swati | external-member | dovish | 50% | *2026-03-18* — Most persistent dove — voted to cut at past 8 consecutive meetings before March. March minutes: 'limited scope may exist for major pass-through and second-round effects given the state of the labour market and broader d… |
| greene-megan | external-member | hawkish | 50% | *2026-03-25* — Mar 25 Jefferies event: 'lasting effects for UK inflation even in best case' where conflict de-escalates; risk premium now baked into energy prices. 'More worried about war's impact on inflation than the economy.' March… |
| lombardelli-clare ⚬ | deputy-governor-monetary-policy | hawkish | 70% | *2026-04-07* — Apr 7 published BoE analysis on dynamic pricing potentially lifting inflation expectations. Framed shock broadly: inflation up, output down, second-round risks alive through direct fuel costs, indirect business costs, e… |
| mann-catherine | external-member | hawkish | 90% | *2026-03-18* — March minutes: 'sustained pressure on energy prices could re-embed the inflation persistence.' Flagged household inflation expectations formed during prolonged high-inflation environment. Most explicit hawk. Voted hold … |
| pill-huw | chief-economist | hawkish | 51% | *2026-03-24* — Mar 24 SUERF speech: cannot let 'fog of uncertainty' paralyze response to inflation resurgence. 2026 pay settlements at 3.6% signal stalling disinflation. Substantial second-round effect risks. |
| ramsden-dave | deputy-governor | dovish | 55% | *2026-03-18* — Voted for 25bp cut in February (dissent). March minutes: data since Feb 'broadly matched his expectations and suggested continuing disinflation, so he would otherwise have voted for a 25bp cut.' Risks tilted to downside… |
| taylor-alan | external-member | dovish | 45% | *2026-03-26* — Mar 26 'Stopping for gas' speech (Exante Data): UK sensitive to gas/oil but size and duration uncertain. Economy's starting point 'very different from past energy shocks.' 'Appropriate to pause' but 'inappropriate to in… |

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

The voting equilibrium includes 8 members (of 9 total actors tracked in `actors.edn` — non-voters contribute evidence but do not cast a vote this meeting). The policy cycle is classified as **neutral**. The chair's stance is **neutral**. The equilibrium produces a **hold** prediction at 49% confidence, supported by a hike indicator signal at strength 0.4.

## Macro Backdrop

As of Apr 14, 2026, the BoE MPC is evenly split 4 hawk / 1 neutral / 4 dove but united on hold by the Iran war energy shock. The February 5-4 split (doves wanted to cut) collapsed to a unanimous 9-0 hold in March.

Hawks (Pill, Mann, Greene, Lombardelli) see second-round inflation risks from energy passthrough + 3.6% pay settlements. Doves (Ramsden, Breeden, Dhingra, Taylor) believe disinflation was nearly complete before the Iran shock and want to resume cutting once the picture clears. Bailey (neutral) pushed back on market hike pricing ('getting ahead of themselves').

The most likely April 30 outcome is another hold, potentially unanimous. A hike is very unlikely absent a major CPI surprise (UK March CPI due April 22). If energy prices moderate, doves could push for a cut as early as June.

## Institutional Dynamic

*Context that the equilibrium math does not capture but should inform interpretation:*

The BoE April 30 meeting includes the Monetary Policy Report (MPR), which means new forecasts and fan charts. The MPR will incorporate the first post-Iran macro projections, which could shift the narrative significantly depending on the inflation and growth outlook.

If the MPR projects CPI above 3% through 2026, hawks gain leverage; if it projects a growth slowdown absorbing the inflation, doves gain leverage.

The MPR is often the single biggest input to MPC decisions at these meetings — more than individual member speeches.

## Key Uncertainty Flags

- **Outlook, not a sealed forecast**: this note will be regenerated as new evidence arrives. A sealed forecast (not regenerated after publication) will be issued at T-7 days.
- Voting member rosters are hand-coded in `actors.edn` for this specific decision. Any personnel changes not yet reflected are a coverage gap.

## Methodology Reference

This outlook uses the methodology described in Casu, J. (2026), "Institutional Actor Modeling in Dodona: A Central Bank Rate Policy Case Study, 2024-2026." Parameters are locked as of the paper's submission date; no per-decision tuning.

The evidence used to generate this outlook is in the companion file `actors.edn` in this directory. Every stance includes a `:last-update` date and a primary-source citation in `:source`.

---

*Dodona is a symbolic cognitive reasoning system for institutional actor modeling. This note is a research output, not investment advice.*
