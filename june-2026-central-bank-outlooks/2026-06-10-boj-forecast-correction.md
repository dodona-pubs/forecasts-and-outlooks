# Dodona Sealed Forecast: BoJ June 2026

**Published:** 2026-06-10
**Decision date:** 2026-06-16
**6 days before decision — SEALED FORECAST**

**This forecast is final and will not be updated.** Post-decision analysis will be published within 24 hours of the outcome.

> **Correction — bug fix (2026-06-10).** This corrects the original BoJ June seal (`2026-06-09-boj-forecast.md`, retained unchanged for the record). A bug had frozen our speech→stance classifier at 2026-04-30 — the step that converts central-banker speeches into stance signals had silently stopped running — so that seal was built on six-week-stale stance inputs. We retrained the classifier today and re-ran on stance data current through 2026-06-09. **Original → corrected:** cut 7 / hold 67.5 / hike 25.5 → **cut 6 / hold 63 / hike 30** (direction unchanged: hold; confidence 68% → 63%).

---

## Summary

**Forecast direction:** hold

**Direction confidence:** 63% [51%, 73%]

## Evidence Cutoff

**Cutoff:** 2026-06-10 00:00 UTC. All evidence in this forecast predates this timestamp. Strict temporal holdout enforced at the data layer.

## Actor Stance Trajectories

Cutoff: 2026-06-10. Actors marked ⚬ contribute evidence but do not vote in this meeting's equilibrium.

| Actor | Role | Current Stance | Confidence | Trajectory |
|-------|------|---------------|-----------|------------|
| adachi-seiji ⚬ | board-member | neutral | 39% | *2026-06-16* — No substrate evidence in 365-day window pre-2026-06-16; carry-forward neutral (confidence 0.39). |
| himino-ryozo | deputy-governor | neutral | 70% | *2026-03-02* — 2 recent signals to 2026-06-16. Most recent: Mar 2 :stance signal neutral (acquire:speech-vector-tone). Prior: Mar 2 :stance signal neutral (acquire:speech-vector-tone). |
| koeda-junko | board-member | neutral | 43% | *2026-05-27* — 2 recent signals to 2026-06-16. Most recent: May 27 :stance signal neutral (acquire:speech-vector-tone). Prior: May 27 :stance signal neutral (acquire:speech-vector-tone). |
| nakagawa-junko ⚬ | board-member | neutral | 39% | *2026-06-16* — No substrate evidence in 365-day window pre-2026-06-16; carry-forward neutral (confidence 0.39). |
| nakamura-toyoaki ⚬ | board-member | neutral | 39% | *2026-06-16* — No substrate evidence in 365-day window pre-2026-06-16; carry-forward neutral (confidence 0.39). |
| noguchi-asahi ⚬ | board-member | neutral | 39% | *2026-06-16* — No substrate evidence in 365-day window pre-2026-06-16; carry-forward neutral (confidence 0.39). |
| takata-hajime | board-member | hawkish | 75% | *2026-02-26* — 2 recent signals to 2026-06-16. Most recent: Feb 26 :stance signal hawkish (acquire:speech-vector-tone). Prior: Feb 26 :stance signal hawkish (acquire:speech-vector-tone). |
| tamura-naoki | board-member | hawkish | 75% | *2026-02-13* — 2 recent signals to 2026-06-16. Most recent: Feb 13 :stance signal hawkish (acquire:speech-vector-tone). Prior: Feb 13 :stance signal hawkish (acquire:speech-vector-tone). |
| uchida-shinichi ⚬ | deputy-governor | neutral | 39% | *2026-06-16* — No substrate evidence in 365-day window pre-2026-06-16; carry-forward neutral (confidence 0.39). |
| ueda-kazuo | governor | hawkish | 75% | *2026-06-04* — 6 recent signals to 2026-06-16. Most recent: Jun 4 :stance signal hawkish (acquire:speech-vector-tone). Prior: Jun 4 :stance signal hawkish (acquire:speech-vector-tone); Mar 3 :stance signal neutral (acquire:speech-vector-tone); Mar 3 :stance signal neutral (acquire:speech-vector-tone). |

## Policy Cycle

- **Current cycle:** neutral
- **Previous decision:** hold
- **Chair stance:** hawkish

## Economic Indicators

| Indicator | Value | Date |
|-----------|-------|------|
| cpi | 1.5% | 2026-03-01 |
| core-pce | 1.4% | 2026-04-01 |
| unemployment | 2.8% | 2026-04-05 |
| gdp | 0.53886% | 2025-11-05 |
| policy-rate | 0.6500% | 2025-12-19 |
| ust-10y | 2.515% | 2026-05-06 |

**Indicator signal:** hike at strength 0.4

## Equilibrium

| Outcome | Probability |
|---------|-------------|
| hold | 63% |
| hike-25 | 19% |
| hike-50 | 12% |
| cut-25 | 6% |
| cut-50 | 0% |

**Direction probabilities:** cut 6% / hold 63% / hike 30%

## What Would Make This Forecast Wrong

- Inflation surprise above 1.5% (most-recent print) would broaden the hawk-dissent tail.
- Core-inflation persistence above target reinforces hold-with-hawkish-tilt; below target opens cut-flip possibility.
- Indicator data after 2026-06-16 is excluded by temporal-holdout discipline; first-prints with material moves can shift the post-seal tail without changing the seal.
- Personnel-transition windows (see :institutional-dynamic-note) can shift effective committee composition mid-window.

## Summary Reasoning

The voting equilibrium includes 5 members (of 10 total actors tracked in `actors.edn`). The policy cycle is classified as **neutral**. The chair's stance is **hawkish**. The equilibrium produces a **hold** forecast at 63% confidence, supported by a hike indicator signal at strength 0.4.

## Macro Backdrop

Bank of Japan 2026-06-16 — macro backdrop (auto-generated, B3 v1). Policy rate at 0.6500% (as-of 2025-12-19). Inflation backdrop: headline 1.5%, core 1.4%. Growth backdrop: unemployment 2.8%, GDP 0.53886%. Substrate window: prior 365 days from decision-date. Stale rows beyond 180 days are treated as missing. Geopolitical / forward-guidance context: pending B3.v2 (Day-3+ scoped) or hand-curated `:notes`.

## Institutional Dynamic

*Context that the equilibrium math does not capture but should inform interpretation:*

BoJ Policy Board 2026-06-16 — committee composition: 10 voting members. Auto-derived from v0.9.2-trackB B5 rotation calendar + personnel-transitions schedule.

## Key Uncertainty Flags

- **Sealed forecast.** Parameters locked. No post-seal revision.
- Voting member rosters are hand-coded in `actors.edn` for this specific decision. Any personnel changes not yet reflected are a coverage gap.

## Methodology Reference

This sealed forecast uses the methodology described in Casu, J. (2026), "Institutional Actor Modeling in Dodona: A Central Bank Rate Policy Case Study, 2024-2026." Parameters are locked as of the paper's submission date; no per-decision tuning.

The evidence used to generate this forecast is in the companion file `actors.edn` in this directory. Every stance includes a `:last-update` date and a primary-source citation in `:source`.

---

*Dodona is a symbolic cognitive reasoning system for institutional actor modeling. This note is a research output, not investment advice.*
