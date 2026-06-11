# Dodona Sealed Forecast: FOMC June 2026

**Published:** 2026-06-10
**Decision date:** 2026-06-17
**7 days before decision — SEALED FORECAST**

**This forecast is final and will not be updated.** Post-decision analysis will be published within 24 hours of the outcome.

> **Methodology note — bug fix (2026-06-10).** Earlier today we found and fixed a bug that had frozen our speech→stance classifier at 2026-04-30: the step that converts central-banker speeches into stance signals had silently stopped running, so outlooks published Jun 4–9 were built on six-week-stale stance inputs. We retrained the classifier today and re-ran on stance data current through 2026-06-09 (visible in the Actor Stance Trajectories below, now dated into June). This is the first published FOMC June seal and reflects the corrected pipeline from the outset.

---

## Summary

**Forecast direction:** hold

**Direction confidence:** 48% [39%, 56%]

## Evidence Cutoff

**Cutoff:** 2026-06-10 00:00 UTC. All evidence in this forecast predates this timestamp. Strict temporal holdout enforced at the data layer.

## Actor Stance Trajectories

Cutoff: 2026-06-10. Actors marked ⚬ contribute evidence but do not vote in this meeting's equilibrium.

| Actor | Role | Current Stance | Confidence | Trajectory |
|-------|------|---------------|-----------|------------|
| barkin-thomas ⚬ | president-richmond | neutral | 39% | *2026-06-17* — No substrate evidence in 365-day window pre-2026-06-17; carry-forward neutral (confidence 0.39). |
| barr-michael | governor | neutral | 63% | *2026-06-09* — 20 recent signals to 2026-06-17. Most recent: Jun 9 :stance signal neutral (acquire:speech-vector-tone). Prior: Jun 9 :stance signal neutral (acquire:speech-vector-tone); May 27 :stance signal neutral (acquire:speech-vector-tone); May 27 :stance signal neutral (acquire:speech-vector-tone). |
| bowman-michelle | vice-chair-supervision | hawkish | 75% | *2026-06-08* — 16 recent signals to 2026-06-17. Most recent: Jun 8 :stance signal hawkish (acquire:speech-vector-tone). Prior: Jun 8 :stance signal hawkish (acquire:speech-vector-tone); Jun 4 :stance signal dovish (acquire:speech-vector-tone); Jun 4 :stance signal dovish (acquire:speech-vector-tone). |
| collins-susan ⚬ | president-boston | neutral | 39% | *2026-06-17* — No substrate evidence in 365-day window pre-2026-06-17; carry-forward neutral (confidence 0.39). |
| cook-lisa | governor | hawkish | 68% | *2026-05-27* — 8 recent signals to 2026-06-17. Most recent: May 27 :stance signal hawkish (acquire:speech-vector-tone). Prior: May 27 :stance signal hawkish (acquire:speech-vector-tone); May 8 :stance signal neutral (acquire:speech-vector-tone); May 8 :stance signal neutral (acquire:speech-vector-tone). |
| daly-mary ⚬ | president-sanfrancisco | neutral | 39% | *2026-06-17* — No substrate evidence in 365-day window pre-2026-06-17; carry-forward neutral (confidence 0.39). |
| goolsbee-austan ⚬ | president-chicago | neutral | 39% | *2026-06-17* — No substrate evidence in 365-day window pre-2026-06-17; carry-forward neutral (confidence 0.39). |
| hammack-beth ⚬ | president-cleveland | neutral | 39% | *2026-06-17* — No substrate evidence in 365-day window pre-2026-06-17; carry-forward neutral (confidence 0.39). |
| jefferson-philip | vice-chair | neutral | 63% | *2026-05-27* — 10 recent signals to 2026-06-17. Most recent: May 27 :stance signal neutral (acquire:speech-vector-tone). Prior: May 27 :stance signal neutral (acquire:speech-vector-tone); Apr 7 :stance signal neutral (acquire:speech-vector-tone); Apr 7 :stance signal neutral (acquire:speech-vector-tone). |
| kashkari-neel ⚬ | president-minneapolis | neutral | 39% | *2026-06-17* — No substrate evidence in 365-day window pre-2026-06-17; carry-forward neutral (confidence 0.39). |
| logan-lorie | president-dallas | hawkish | 79% | *2026-05-27* — 6 recent signals to 2026-06-17. Most recent: May 27 :stance signal hawkish (acquire:speech-vector-tone). Prior: May 27 :stance signal hawkish (acquire:speech-vector-tone); May 10 :stance signal neutral (acquire:speech-vector-tone); May 10 :stance signal neutral (acquire:speech-vector-tone). |
| miran-stephen | governor | dovish | 77% | *2026-03-26* — 4 recent signals to 2026-06-17. Most recent: Mar 26 :stance signal dovish (acquire:speech-vector-tone). Prior: Mar 26 :stance signal dovish (acquire:speech-vector-tone); Mar 25 :stance signal dovish (acquire:speech-vector-tone); Mar 25 :stance signal dovish (acquire:speech-vector-tone). |
| musalem-alberto ⚬ | president-stlouis | neutral | 39% | *2026-06-17* — No substrate evidence in 365-day window pre-2026-06-17; carry-forward neutral (confidence 0.39). |
| paulson-anna ⚬ | president-philadelphia | neutral | 39% | *2026-06-17* — No substrate evidence in 365-day window pre-2026-06-17; carry-forward neutral (confidence 0.39). |
| powell-jerome | governor | hawkish | 81% | *2026-04-29* — 8 recent signals to 2026-06-17. Most recent: Apr 29 :stance signal hawkish (acquire:speech-vector-tone). Prior: Apr 29 :stance signal hawkish (acquire:speech-vector-tone); Apr 29 :stance signal dovish (acquire:speech-vector-tone); Apr 29 :stance signal dovish (acquire:speech-vector-tone). |
| schmid-jeff ⚬ | president-kansascity | neutral | 39% | *2026-06-17* — No substrate evidence in 365-day window pre-2026-06-17; carry-forward neutral (confidence 0.39). |
| venable-cheryl ⚬ | president-atlanta-interim | neutral | 39% | *2026-06-17* — No substrate evidence in 365-day window pre-2026-06-17; carry-forward neutral (confidence 0.39). |
| waller-christopher | governor | dovish | 62% | *2026-05-22* — 14 recent signals to 2026-06-17. Most recent: May 22 :stance signal dovish (acquire:speech-vector-tone). Prior: May 22 :stance signal dovish (acquire:speech-vector-tone); May 8 :stance signal dovish (acquire:speech-vector-tone); May 8 :stance signal dovish (acquire:speech-vector-tone). |
| warsh-kevin | chair | hawkish | 78% | *2026-05-22* — 9 recent signals to 2026-06-17. Most recent: May 22 :stance signal hawkish (acquire:speech-vector-tone). Prior: May 22 :stance signal hawkish (acquire:speech-vector-tone); May 22 :stance signal neutral (acquire:spacy-stance); Apr 22 :stance signal neutral (acquire:speech-vector-tone). |
| williams-john | president-ny | neutral | 75% | *2026-06-04* — 2 recent signals to 2026-06-17. Most recent: Jun 4 :stance signal neutral (acquire:speech-vector-tone). Prior: Jun 4 :stance signal neutral (acquire:speech-vector-tone). |

## Policy Cycle

- **Current cycle:** neutral
- **Previous decision:** hold
- **Chair stance:** hawkish

## Economic Indicators

| Indicator | Value | Date |
|-----------|-------|------|
| cpi | 3.77925% | 2026-05-06 |
| core-pce | 3.28919% | 2026-05-06 |
| unemployment | 4.3% | 2026-06-05 |
| gdp | 2.65972% | 2026-02-05 |
| policy-rate | 3.75% | 2026-06-05 |
| pce | 3.49608% | 2026-04-05 |
| nfp | 158736 | 2026-05-06 |
| indpro | 1.35314% | 2026-05-06 |
| ust-10y | 4.47% | 2026-05-14 |
| ust-2y | 4.0% | 2026-05-14 |

**Indicator signal:** hike at strength 0.6

## Equilibrium

| Outcome | Probability |
|---------|-------------|
| hold | 48% |
| hike-25 | 23% |
| hike-50 | 19% |
| cut-25 | 8% |
| cut-50 | 1% |

**Direction probabilities:** cut 10% / hold 48% / hike 42%

## What Would Make This Forecast Wrong

- Inflation surprise above 3.77925% (most-recent print) would broaden the hawk-dissent tail.
- Core-inflation persistence above target reinforces hold-with-hawkish-tilt; below target opens cut-flip possibility.
- Indicator data after 2026-06-17 is excluded by temporal-holdout discipline; first-prints with material moves can shift the post-seal tail without changing the seal.
- Personnel-transition windows (see :institutional-dynamic-note) can shift effective committee composition mid-window.

## Summary Reasoning

The voting equilibrium includes 10 members (of 20 total actors tracked in `actors.edn`). The policy cycle is classified as **neutral**. The chair's stance is **hawkish**. The equilibrium produces a **hold** forecast at 48% confidence, supported by a hike indicator signal at strength 0.6.

## Macro Backdrop

Federal Reserve 2026-06-17 — macro backdrop (auto-generated, B3 v1). Policy rate at 3.75% (as-of 2026-06-05). Inflation backdrop: headline 3.77925%, core 3.28919%. Growth backdrop: unemployment 4.3%, GDP 2.65972%. Substrate window: prior 365 days from decision-date. Stale rows beyond 180 days are treated as missing. Geopolitical / forward-guidance context: pending B3.v2 (Day-3+ scoped) or hand-curated `:notes`.

## Institutional Dynamic

*Context that the equilibrium math does not capture but should inform interpretation:*

FOMC 2026-06-17 — committee composition: 13 voting members. Auto-derived from v0.9.2-trackB B5 rotation calendar + personnel-transitions schedule.

## Key Uncertainty Flags

- **Sealed forecast.** Parameters locked. No post-seal revision.
- Voting member rosters are hand-coded in `actors.edn` for this specific decision. Any personnel changes not yet reflected are a coverage gap.

## Methodology Reference

This sealed forecast uses the methodology described in Casu, J. (2026), "Institutional Actor Modeling in Dodona: A Central Bank Rate Policy Case Study, 2024-2026." Parameters are locked as of the paper's submission date; no per-decision tuning.

The evidence used to generate this forecast is in the companion file `actors.edn` in this directory. Every stance includes a `:last-update` date and a primary-source citation in `:source`.

---

*Dodona is a symbolic cognitive reasoning system for institutional actor modeling. This note is a research output, not investment advice.*
