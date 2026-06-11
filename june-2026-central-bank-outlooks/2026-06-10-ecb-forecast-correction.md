# Dodona Sealed Forecast: ECB June 2026

**Published:** 2026-06-10
**Decision date:** 2026-06-11
**1 days before decision — SEALED FORECAST**

**This forecast is final and will not be updated.** Post-decision analysis will be published within 24 hours of the outcome.

> **Correction — bug fix (2026-06-10).** This corrects the original ECB June seal (`2026-06-04-ecb-forecast.md`, retained unchanged for the record). A bug had frozen our speech→stance classifier at 2026-04-30 — the step that converts central-banker speeches into stance signals had silently stopped running — so that seal was built on stale stance inputs (ECB was the most affected: its attributed-speech inputs were frozen back to 2026-04-22). We retrained the classifier today and re-ran on stance data current through 2026-06-09. **Original → corrected:** cut 15.3 / hold 70.8 / hike 13.8 → **cut 11 / hold 76 / hike 13** (direction unchanged: hold; confidence 71% → 76%).

---

## Summary

**Forecast direction:** hold

**Direction confidence:** 76% [61%, 88%]

## Evidence Cutoff

**Cutoff:** 2026-06-10 00:00 UTC. All evidence in this forecast predates this timestamp. Strict temporal holdout enforced at the data layer.

## Actor Stance Trajectories

Cutoff: 2026-06-10. Actors marked ⚬ contribute evidence but do not vote in this meeting's equilibrium.

| Actor | Role | Current Stance | Confidence | Trajectory |
|-------|------|---------------|-----------|------------|
| centeno-mario ⚬ | governor-bancodeportugal | neutral | 39% | *2026-06-11* — No substrate evidence in 365-day window pre-2026-06-11; carry-forward neutral (confidence 0.39). |
| cipollone-piero | executive-board | dovish | 60% | *2026-06-04* — 18 recent signals to 2026-06-11. Most recent: Jun 4 :stance signal dovish (acquire:speech-vector-tone). Prior: Jun 4 :stance signal dovish (acquire:speech-vector-tone); Apr 15 :stance signal neutral (acquire:speech-vector-tone); Apr 15 :stance signal neutral (acquire:speech-vector-tone). |
| elderson-frank | executive-board | hawkish | 40% | *2026-06-04* — 10 recent signals to 2026-06-11. Most recent: Jun 4 :stance signal hawkish (acquire:speech-vector-tone). Prior: Jun 4 :stance signal hawkish (acquire:speech-vector-tone); Mar 9 :stance signal neutral (acquire:speech-vector-tone); Mar 9 :stance signal neutral (acquire:speech-vector-tone). |
| escriva-jose-luis ⚬ | governor-bancodeespana | neutral | 39% | *2026-06-11* — No substrate evidence in 365-day window pre-2026-06-11; carry-forward neutral (confidence 0.39). |
| holzmann-robert ⚬ | governor-oenb | neutral | 39% | *2026-06-11* — No substrate evidence in 365-day window pre-2026-06-11; carry-forward neutral (confidence 0.39). |
| kazaks-martins ⚬ | governor-latvijasbanka | neutral | 39% | *2026-06-11* — No substrate evidence in 365-day window pre-2026-06-11; carry-forward neutral (confidence 0.39). |
| kazimir-peter ⚬ | governor-nbs | neutral | 39% | *2026-06-11* — No substrate evidence in 365-day window pre-2026-06-11; carry-forward neutral (confidence 0.39). |
| lagarde-christine | president | dovish | 75% | *2026-04-30* — 16 recent signals to 2026-06-11. Most recent: Apr 30 :stance signal dovish (acquire:speech-vector-tone). Prior: Apr 30 :stance signal dovish (acquire:speech-vector-tone); Apr 20 :stance signal dovish (acquire:speech-vector-tone); Apr 20 :stance signal dovish (acquire:speech-vector-tone). |
| lane-philip | chief-economist | dovish | 77% | *2026-04-22* — 8 recent signals to 2026-06-11. Most recent: Apr 22 :stance signal dovish (acquire:speech-vector-tone). Prior: Apr 22 :stance signal dovish (acquire:speech-vector-tone); Apr 22 :stance signal dovish (acquire:speech-vector-tone); Apr 22 :stance signal dovish (acquire:speech-vector-tone). |
| makhlouf-gabriel ⚬ | governor-centralbankireland | neutral | 39% | *2026-06-11* — No substrate evidence in 365-day window pre-2026-06-11; carry-forward neutral (confidence 0.39). |
| muller-madis ⚬ | governor-eestipank | neutral | 39% | *2026-06-11* — No substrate evidence in 365-day window pre-2026-06-11; carry-forward neutral (confidence 0.39). |
| nagel-joachim ⚬ | governor-bundesbank | neutral | 39% | *2026-06-11* — No substrate evidence in 365-day window pre-2026-06-11; carry-forward neutral (confidence 0.39). |
| panetta-fabio ⚬ | governor-bancaditalia | neutral | 39% | *2026-06-11* — No substrate evidence in 365-day window pre-2026-06-11; carry-forward neutral (confidence 0.39). |
| patsalides-christodoulos ⚬ | governor-cbc | neutral | 39% | *2026-06-11* — No substrate evidence in 365-day window pre-2026-06-11; carry-forward neutral (confidence 0.39). |
| radev-dimitar ⚬ | governor-bnb | neutral | 39% | *2026-06-11* — No substrate evidence in 365-day window pre-2026-06-11; carry-forward neutral (confidence 0.39). |
| rehn-olli ⚬ | governor-suomenpankki | neutral | 39% | *2026-06-11* — No substrate evidence in 365-day window pre-2026-06-11; carry-forward neutral (confidence 0.39). |
| reinesch-gaston ⚬ | governor-bcl | neutral | 39% | *2026-06-11* — No substrate evidence in 365-day window pre-2026-06-11; carry-forward neutral (confidence 0.39). |
| schnabel-isabel | executive-board | neutral | 70% | *2026-06-04* — 10 recent signals to 2026-06-11. Most recent: Jun 4 :stance signal neutral (acquire:speech-vector-tone). Prior: Jun 4 :stance signal neutral (acquire:speech-vector-tone); Mar 6 :stance signal hawkish (acquire:speech-vector-tone); Mar 6 :stance signal hawkish (acquire:speech-vector-tone). |
| scicluna-edward ⚬ | governor-cbm | neutral | 39% | *2026-06-11* — No substrate evidence in 365-day window pre-2026-06-11; carry-forward neutral (confidence 0.39). |
| simkus-gediminas ⚬ | governor-lietuvosbankas | neutral | 39% | *2026-06-11* — No substrate evidence in 365-day window pre-2026-06-11; carry-forward neutral (confidence 0.39). |
| sleijpen-olaf ⚬ | governor-dnb | neutral | 39% | *2026-06-11* — No substrate evidence in 365-day window pre-2026-06-11; carry-forward neutral (confidence 0.39). |
| stournaras-yannis ⚬ | governor-bankofgreece | neutral | 39% | *2026-06-11* — No substrate evidence in 365-day window pre-2026-06-11; carry-forward neutral (confidence 0.39). |
| unfilled-seat-governor-HR ⚬ | governor-HR | neutral | 0% | SUBSTRATE GAP: seat for governor-HR is unfilled at 2026-06-11. No successor named. |
| vasle-bostjan ⚬ | governor-bankaslovenije | neutral | 39% | *2026-06-11* — No substrate evidence in 365-day window pre-2026-06-11; carry-forward neutral (confidence 0.39). |
| villeroy-francois ⚬ | governor-banquedefrance | neutral | 39% | *2026-06-11* — No substrate evidence in 365-day window pre-2026-06-11; carry-forward neutral (confidence 0.39). |
| vujcic-boris ⚬ | governor-hnb | neutral | 39% | *2026-06-11* — No substrate evidence in 365-day window pre-2026-06-11; carry-forward neutral (confidence 0.39). |
| wunsch-pierre ⚬ | governor-nbb | neutral | 39% | *2026-06-11* — No substrate evidence in 365-day window pre-2026-06-11; carry-forward neutral (confidence 0.39). |

## Policy Cycle

- **Current cycle:** neutral
- **Previous decision:** hold
- **Chair stance:** dovish

## Economic Indicators

| Indicator | Value | Date |
|-----------|-------|------|
| cpi | 2.53368% | 2026-04-05 |
| core-pce | 2.3 | 2025-12-01 |
| unemployment | 6.7% | 2023-02-05 |
| gdp | 0.77853% | 2026-02-05 |
| policy-rate | 2.0% | 2026-05-15 |
| ust-10y | 3.2209840909% | 2026-02-05 |

**Indicator signal:** hike at strength 0.2

## Equilibrium

| Outcome | Probability |
|---------|-------------|
| hold | 76% |
| hike-25 | 9% |
| cut-25 | 8% |
| hike-50 | 4% |
| cut-50 | 3% |

**Direction probabilities:** cut 11% / hold 76% / hike 13%

## What Would Make This Forecast Wrong

- Inflation surprise above 2.53368% (most-recent print) would broaden the hawk-dissent tail.
- Core-inflation persistence above target reinforces hold-with-hawkish-tilt; below target opens cut-flip possibility.
- Indicator data after 2026-06-11 is excluded by temporal-holdout discipline; first-prints with material moves can shift the post-seal tail without changing the seal.
- Personnel-transition windows (see :institutional-dynamic-note) can shift effective committee composition mid-window.

## Summary Reasoning

The voting equilibrium includes 5 members (of 27 total actors tracked in `actors.edn`). The policy cycle is classified as **neutral**. The chair's stance is **dovish**. The equilibrium produces a **hold** forecast at 76% confidence, supported by a hike indicator signal at strength 0.2.

## Macro Backdrop

ECB 2026-06-11 — macro backdrop (auto-generated, B3 v1). Policy rate at 2.0% (as-of 2026-05-15). Inflation backdrop: headline 2.53368%, core 2.3. Growth backdrop: unemployment 6.7%, GDP 0.77853%. Substrate window: prior 365 days from decision-date. Stale rows beyond 180 days are treated as missing. Geopolitical / forward-guidance context: pending B3.v2 (Day-3+ scoped) or hand-curated `:notes`.

## Institutional Dynamic

*Context that the equilibrium math does not capture but should inform interpretation:*

ECB Governing Council 2026-06-11 — committee composition: 21 voting members. Rotation: 6 non-voting this meeting (IT, PT, SK, SI, AT, FI); 1 substrate gap(s) flagged. Personnel: deguindos-luis → vujcic-boris (vice-president) effective 2026-06-01. Auto-derived from v0.9.2-trackB B5 rotation calendar + personnel-transitions schedule.

## Key Uncertainty Flags

- **Sealed forecast.** Parameters locked. No post-seal revision.
- Voting member rosters are hand-coded in `actors.edn` for this specific decision. Any personnel changes not yet reflected are a coverage gap.

## Methodology Reference

This sealed forecast uses the methodology described in Casu, J. (2026), "Institutional Actor Modeling in Dodona: A Central Bank Rate Policy Case Study, 2024-2026." Parameters are locked as of the paper's submission date; no per-decision tuning.

The evidence used to generate this forecast is in the companion file `actors.edn` in this directory. Every stance includes a `:last-update` date and a primary-source citation in `:source`.

---

*Dodona is a symbolic cognitive reasoning system for institutional actor modeling. This note is a research output, not investment advice.*
