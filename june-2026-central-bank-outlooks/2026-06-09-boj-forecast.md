# Dodona Sealed Forecast: BoJ June 2026

**Published:** 2026-06-09
**Decision date:** 2026-06-16
**7 days before decision — SEALED FORECAST**

**This forecast is final and will not be updated.** Post-decision analysis will be published within 24 hours of the outcome.

---

## Summary

**Forecast direction:** hold

**Direction confidence:** 68% [54%, 78%]

## Evidence Cutoff

**Cutoff:** 2026-06-09 00:00 UTC. All evidence in this forecast predates this timestamp. Strict temporal holdout enforced at the data layer.

## Actor Stance Trajectories

Cutoff: 2026-06-16. Actors marked ⚬ contribute evidence but do not vote in this meeting's equilibrium.

| Actor | Role | Current Stance | Confidence | Trajectory |
|-------|------|---------------|-----------|------------|
| adachi-seiji ⚬ | board-member | neutral | 39% | *2026-06-16* — No substrate evidence in 365-day window pre-2026-06-16; carry-forward neutral (confidence 0.39). |
| himino-ryozo | deputy-governor | neutral | 47% | *2026-03-02* — 1 recent signals to 2026-06-16. Most recent: Mar 2 :stance signal neutral (acquire:speech-vector-tone). |
| koeda-junko ⚬ | board-member | neutral | 39% | *2026-06-16* — No substrate evidence in 365-day window pre-2026-06-16; carry-forward neutral (confidence 0.39). |
| nakagawa-junko ⚬ | board-member | neutral | 39% | *2026-06-16* — No substrate evidence in 365-day window pre-2026-06-16; carry-forward neutral (confidence 0.39). |
| nakamura-toyoaki ⚬ | board-member | neutral | 39% | *2026-06-16* — No substrate evidence in 365-day window pre-2026-06-16; carry-forward neutral (confidence 0.39). |
| noguchi-asahi ⚬ | board-member | neutral | 39% | *2026-06-16* — No substrate evidence in 365-day window pre-2026-06-16; carry-forward neutral (confidence 0.39). |
| takata-hajime | board-member | hawkish | 51% | *2026-02-26* — 1 recent signals to 2026-06-16. Most recent: Feb 26 :stance signal hawkish (acquire:speech-vector-tone). |
| tamura-naoki | board-member | hawkish | 72% | *2026-02-13* — 1 recent signals to 2026-06-16. Most recent: Feb 13 :stance signal hawkish (acquire:speech-vector-tone). |
| uchida-shinichi ⚬ | deputy-governor | neutral | 39% | *2026-06-16* — No substrate evidence in 365-day window pre-2026-06-16; carry-forward neutral (confidence 0.39). |
| ueda-kazuo | governor | neutral | 81% | *2026-03-03* — 2 recent signals to 2026-06-16. Most recent: Mar 3 :stance signal neutral (acquire:speech-vector-tone). Prior: Dec 25 :stance signal neutral (acquire:speech-vector-tone). |

## Policy Cycle

- **Current cycle:** neutral
- **Previous decision:** hold
- **Chair stance:** neutral

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
| hold | 68% |
| hike-25 | 15% |
| hike-50 | 10% |
| cut-25 | 6% |
| cut-50 | 1% |

**Direction probabilities:** cut 7% / hold 68% / hike 25%

## What Would Make This Forecast Wrong

- Inflation surprise above 1.5% (most-recent print) would broaden the hawk-dissent tail.
- Core-inflation persistence above target reinforces hold-with-hawkish-tilt; below target opens cut-flip possibility.
- Indicator data after 2026-06-16 is excluded by temporal-holdout discipline; first-prints with material moves can shift the post-seal tail without changing the seal.
- Personnel-transition windows (see :institutional-dynamic-note) can shift effective committee composition mid-window.

## Summary Reasoning

The voting equilibrium includes 4 members (of 10 total actors tracked in `actors.edn`). The policy cycle is classified as **neutral**. The chair's stance is **neutral**. The equilibrium produces a **hold** forecast at 68% confidence, supported by a hike indicator signal at strength 0.4.

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

The evidence used to generate this forecast is the **Actor Stance Trajectories** table above: every voting stance carries its `:last-update` date and the primary-source acquisition (`acquire:speech-vector-tone` / `acquire:spacy-stance`) that produced it. Carry-forward / non-voting members with no in-window substrate are surfaced rather than hidden.

---

*Dodona is a symbolic cognitive reasoning system for institutional actor modeling. This note is a research output, not investment advice.*
