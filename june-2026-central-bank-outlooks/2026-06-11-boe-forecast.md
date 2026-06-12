# Dodona Sealed Forecast: BoE June 2026

**Published:** 2026-06-11
**Decision date:** 2026-06-18
**7 days before decision — SEALED FORECAST**

**This forecast is final and will not be updated.** Post-decision analysis will be published within 24 hours of the outcome.

---

## Summary

**Forecast direction:** hold

**Direction confidence:** 69% [55%, 79%]

## Evidence Cutoff

**Cutoff:** 2026-06-11 00:00 UTC. All evidence in this forecast predates this timestamp. Strict temporal holdout enforced at the data layer.

## Actor Stance Trajectories

Cutoff: 2026-06-11. Actors marked ⚬ contribute evidence but do not vote in this meeting's equilibrium.

| Actor | Role | Current Stance | Confidence | Trajectory |
|-------|------|---------------|-----------|------------|
| bailey-andrew | governor | neutral | 71% | *2026-04-27* — 6 recent signals to 2026-06-18. Most recent: Apr 27 :stance signal neutral (acquire:speech-vector-tone). Prior: Apr 27 :stance signal neutral (acquire:speech-vector-tone); Apr 14 :stance signal neutral (acquire:speech-vector-tone); Apr 14 :stance signal neutral (acquire:speech-vector-tone). |
| breeden-sarah | deputy-governor | hawkish | 69% | *2026-05-27* — 8 recent signals to 2026-06-18. Most recent: May 27 :stance signal hawkish (acquire:speech-vector-tone). Prior: May 27 :stance signal hawkish (acquire:speech-vector-tone); Apr 29 :stance signal neutral (acquire:speech-vector-tone); Apr 29 :stance signal neutral (acquire:speech-vector-tone). |
| broadbent-ben ⚬ | deputy-governor | neutral | 39% | *2026-06-18* — No substrate evidence in 365-day window pre-2026-06-18; carry-forward neutral (confidence 0.39). |
| dhingra-swati ⚬ | external-member | neutral | 39% | *2026-06-18* — No substrate evidence in 365-day window pre-2026-06-18; carry-forward neutral (confidence 0.39). |
| greene-megan | external-member | dovish | 60% | *2026-01-23* — 4 recent signals to 2026-06-18. Most recent: Jan 23 :stance signal dovish (acquire:speech-vector-tone). Prior: Jan 23 :stance signal dovish (acquire:speech-vector-tone); Jan 22 :stance signal hawkish (acquire:speech-vector-tone); Jan 22 :stance signal hawkish (acquire:speech-vector-tone). |
| mann-catherine ⚬ | external-member | neutral | 39% | *2026-06-18* — No substrate evidence in 365-day window pre-2026-06-18; carry-forward neutral (confidence 0.39). |
| pill-huw | chief-economist | hawkish | 77% | *2026-03-24* — 4 recent signals to 2026-06-18. Most recent: Mar 24 :stance signal hawkish (acquire:speech-vector-tone). Prior: Mar 24 :stance signal hawkish (acquire:speech-vector-tone); Mar 23 :stance signal hawkish (acquire:speech-vector-tone); Mar 23 :stance signal hawkish (acquire:speech-vector-tone). |
| ramsden-dave | deputy-governor | neutral | 70% | *2026-01-14* — 4 recent signals to 2026-06-18. Most recent: Jan 14 :stance signal dovish (acquire:speech-vector-tone). Prior: Jan 14 :stance signal dovish (acquire:speech-vector-tone); Jan 13 :stance signal neutral (acquire:speech-vector-tone); Jan 13 :stance signal neutral (acquire:speech-vector-tone). |
| taylor-alan | external-member | neutral | 76% | *2026-04-13* — 8 recent signals to 2026-06-18. Most recent: Apr 13 :stance signal neutral (acquire:speech-vector-tone). Prior: Apr 13 :stance signal neutral (acquire:speech-vector-tone); Apr 12 :stance signal neutral (acquire:speech-vector-tone); Apr 12 :stance signal neutral (acquire:speech-vector-tone). |

## Policy Cycle

- **Current cycle:** neutral
- **Previous decision:** hold
- **Chair stance:** neutral

## Economic Indicators

| Indicator | Value | Date |
|-----------|-------|------|
| cpi | 2.8000% | 2026-04-01 |
| core-pce | 2.5000% | 2026-04-01 |
| unemployment | 5.2% | 2026-01-05 |
| gdp | 0.99743% | 2025-11-05 |
| policy-rate | 3.729% | 2026-05-13 |
| ust-10y | 4.8207% | 2026-05-06 |

**Indicator signal:** hike at strength 0.4

## Equilibrium

| Outcome | Probability |
|---------|-------------|
| hold | 69% |
| hike-25 | 12% |
| hike-50 | 9% |
| cut-25 | 8% |
| cut-50 | 2% |

**Direction probabilities:** cut 10% / hold 69% / hike 21%

## What Would Make This Forecast Wrong

- Inflation surprise above 2.8000% (most-recent print) would broaden the hawk-dissent tail.
- Core-inflation persistence above target reinforces hold-with-hawkish-tilt; below target opens cut-flip possibility.
- Indicator data after 2026-06-18 is excluded by temporal-holdout discipline; first-prints with material moves can shift the post-seal tail without changing the seal.
- Personnel-transition windows (see :institutional-dynamic-note) can shift effective committee composition mid-window.

## Summary Reasoning

The voting equilibrium includes 6 members (of 9 total actors tracked in `actors.edn`). The policy cycle is classified as **neutral**. The chair's stance is **neutral**. The equilibrium produces a **hold** forecast at 69% confidence, supported by a hike indicator signal at strength 0.4.

## Macro Backdrop

Bank of England 2026-06-18 — macro backdrop (auto-generated, B3 v1). Policy rate at 3.729% (as-of 2026-05-13). Inflation backdrop: headline 2.8000%, core 2.5000%. Growth backdrop: unemployment 5.2%, GDP 0.99743%. Substrate window: prior 365 days from decision-date. Stale rows beyond 180 days are treated as missing. Geopolitical / forward-guidance context: pending B3.v2 (Day-3+ scoped) or hand-curated `:notes`.

## Institutional Dynamic

*Context that the equilibrium math does not capture but should inform interpretation:*

BoE MPC 2026-06-18 — committee composition: 9 voting members. Auto-derived from v0.9.2-trackB B5 rotation calendar + personnel-transitions schedule.

## Key Uncertainty Flags

- **Sealed forecast.** Parameters locked. No post-seal revision.
- Voting member rosters are hand-coded in `actors.edn` for this specific decision. Any personnel changes not yet reflected are a coverage gap.

## Methodology Reference

This sealed forecast uses the methodology described in Casu, J. (2026), "Institutional Actor Modeling in Dodona: A Central Bank Rate Policy Case Study, 2024-2026." Parameters are locked as of the paper's submission date; no per-decision tuning.

The evidence used to generate this forecast is in the companion file `actors.edn` in this directory. Every stance includes a `:last-update` date and a primary-source citation in `:source`.

---

*Dodona is a symbolic cognitive reasoning system for institutional actor modeling. This note is a research output, not investment advice.*
