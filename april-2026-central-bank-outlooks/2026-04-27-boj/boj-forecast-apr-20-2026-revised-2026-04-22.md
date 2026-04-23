# Dodona Sealed Forecast: BoJ April 2026 — REVISED 2026-04-22

**Original published:** 2026-04-20
**Revised:** 2026-04-22
**Decision date:** 2026-04-27
**7 days before decision — SEALED FORECAST (RE-COMPUTED)**

> **Transparency note.** The original Apr 20 sealed forecast for BoJ (also
> preserved in `docs/Forecasts/2026-04-27-boj/2026-04-20-forecast/`)
> reported **HOLD 50% [40%, 57%]**. During the Apr 22 pre-FOMC-T-7
> research window we discovered that the `actor_ontology` table on the
> production KB had **0 BoJ board members registered** — a casualty of
> the Apr 19-20 DuckDB corruption and rebuild. With the roster empty,
> the prediction engine fell back to its 0-voter default (50%, the
> hard-coded neutral prior) instead of computing an actor-level
> equilibrium. This affected BoJ outputs Apr 20-22.
>
> We re-seeded the BoJ roster (9 Policy Board members from
> `resources/data/fe/boj_members.edn`) and re-ran the seal with strict
> `:as-of "2026-04-20"` temporal holdout — every evidence item predates
> 2026-04-20 00:00 UTC, identical cutoff to the original. The
> re-computed seal is the HOLD direction-confidence recorded below.
>
> This revised seal is published alongside the original; both are
> visible on the public repo. For scoring purposes, the re-computed
> seal is authoritative — the original broken seal should not be used
> for calibration accounting.

**This forecast is final and will not be updated.** Post-decision analysis will be published within 24 hours of the outcome.

---

## Summary

**Forecast direction:** hold

**Direction confidence:** 63% [50%, 72%]

## Convergence History

How this call evolved from the first daily outlook through the seal date:

| Date | Direction | Confidence | Shift |
|------|-----------|-----------|-------|
| 2026-03-20 | hold | 56% | — |
| 2026-03-23 | hold | 56% | — |
| 2026-03-24 | hold | 56% | — |
| 2026-03-25 | hold | 56% | — |
| 2026-03-26 | hold | 56% | — |
| 2026-03-27 | hold | 56% | — |
| 2026-03-30 | hold | 56% | — |
| 2026-03-31 | hold | 56% | — |
| 2026-04-01 | hold | 56% | — |
| 2026-04-02 | hold | 56% | — |
| 2026-04-03 | hold | 56% | — |
| 2026-04-06 | hold | 56% | — |
| 2026-04-07 | hold | 56% | — |
| 2026-04-08 | hold | 56% | — |
| 2026-04-09 | hold | 56% | — |
| 2026-04-10 | hold | 56% | — |
| 2026-04-14 | hold | 56% | — |
| 2026-04-15 | hold | 56% | — |
| 2026-04-16 | hold | 56% | — |
| 2026-04-17 | hold | 56% | — |
| 2026-04-18 | hold | 56% | — |
| 2026-04-19 | hold | 56% | — |
| 2026-04-20 | hold | 50% | -6% |
| 2026-04-21 | hold | 50% | — |
| 2026-04-22 | hold | 63% | +13% |

## Market Consensus Comparison

| Source | Cut | Hold | Hike | As-of |
|--------|-----|------|------|-------|
| **Dodona** | 14% | 63% | 24% | 2026-04-20 |
| Polymarket | — | 89% | 11% | 2026-04-17 |
| OIS-implied | — | 90% | 10% | 2026-04-17 |

## Evidence Cutoff

**Cutoff:** 2026-04-20 00:00 UTC. All evidence in this forecast predates this timestamp. Strict temporal holdout enforced at the data layer.

**Upcoming data NOT incorporated in this forecast:**

- Japan March CPI (2026-04-24) — relevance: high
- Ueda press briefing (post-G20) (2026-04-17) — relevance: high
- Japan March trade balance (2026-04-16) — relevance: medium
- BoJ Outlook Report (2026-04-27) — relevance: high (released day-of, not pre-decision)

## Actor Stance Trajectories

Cutoff: 2026-04-20. Actors marked ⚬ contribute evidence but do not vote in this meeting's equilibrium.

| Actor | Role | Current Stance | Confidence | Trajectory |
|-------|------|---------------|-----------|------------|
| asada-toichiro ⚬ | board-member | dovish | 75% | dovish 75% (2026-03-20) → dovish 75% (2026-03-23) → dovish 75% (2026-03-24) → dovish 75% (2026-03-25) → dovish 75% (2026-03-26) → dovish 75% (2026-03-27) → dovish 75% (2026-03-30) → dovish 75% (2026-03-31) → dovish 75% (2026-04-01) → dovish 75% (2026-04-02) → dovish 75% (2026-04-03) → dovish 75% (2026-04-06) → dovish 75% (2026-04-07) → dovish 75% (2026-04-08) → dovish 75% (2026-04-09) → dovish 75% (2026-04-10) → dovish 75% (2026-04-12) → dovish 75% (2026-04-13) → dovish 75% (2026-04-14) → dovish 75% (2026-04-15) → dovish 75% (2026-04-16) → dovish 75% (2026-04-17) → dovish 75% (2026-04-18) → dovish 75% (2026-04-19) → dovish 75% (2026-04-20) → dovish 75% (2026-04-21) → dovish 75% (2026-04-22) |
| himino-ryozo | deputy-governor | neutral | 43% | neutral 55% (2026-03-20) → neutral 55% (2026-03-23) → neutral 55% (2026-03-24) → neutral 55% (2026-03-25) → neutral 55% (2026-03-26) → neutral 55% (2026-03-27) → neutral 55% (2026-03-30) → neutral 55% (2026-03-31) → neutral 55% (2026-04-01) → neutral 55% (2026-04-02) → neutral 55% (2026-04-03) → neutral 55% (2026-04-06) → neutral 55% (2026-04-07) → neutral 55% (2026-04-08) → neutral 55% (2026-04-09) → neutral 55% (2026-04-10) → neutral 55% (2026-04-12) → neutral 55% (2026-04-13) → neutral 55% (2026-04-14) → neutral 55% (2026-04-15) → neutral 55% (2026-04-16) → neutral 60% (2026-04-17) → neutral 60% (2026-04-18) → neutral 60% (2026-04-19) → neutral 60% (2026-04-20) → neutral 60% (2026-04-21) → neutral 60% (2026-04-22) |
| koeda-junko ⚬ | board-member | hawkish | 80% | hawkish 80% (2026-03-20) → hawkish 80% (2026-03-23) → hawkish 80% (2026-03-24) → hawkish 80% (2026-03-25) → hawkish 80% (2026-03-26) → hawkish 80% (2026-03-27) → hawkish 80% (2026-03-30) → hawkish 80% (2026-03-31) → hawkish 80% (2026-04-01) → hawkish 80% (2026-04-02) → hawkish 80% (2026-04-03) → hawkish 80% (2026-04-06) → hawkish 80% (2026-04-07) → hawkish 80% (2026-04-08) → hawkish 80% (2026-04-09) → hawkish 80% (2026-04-10) → hawkish 80% (2026-04-12) → hawkish 80% (2026-04-13) → hawkish 80% (2026-04-14) → hawkish 80% (2026-04-15) → hawkish 80% (2026-04-16) → hawkish 80% (2026-04-17) → hawkish 80% (2026-04-18) → hawkish 80% (2026-04-19) → hawkish 80% (2026-04-20) → hawkish 80% (2026-04-21) → hawkish 80% (2026-04-22) |
| masu-kazuyuki ⚬ | board-member | neutral | 65% | neutral 65% (2026-03-20) → neutral 65% (2026-03-23) → neutral 65% (2026-03-24) → neutral 65% (2026-03-25) → neutral 65% (2026-03-26) → neutral 65% (2026-03-27) → neutral 65% (2026-03-30) → neutral 65% (2026-03-31) → neutral 65% (2026-04-01) → neutral 65% (2026-04-02) → neutral 65% (2026-04-03) → neutral 65% (2026-04-06) → neutral 65% (2026-04-07) → neutral 65% (2026-04-08) → neutral 65% (2026-04-09) → neutral 65% (2026-04-10) → neutral 65% (2026-04-12) → neutral 65% (2026-04-13) → neutral 65% (2026-04-14) → neutral 65% (2026-04-15) → neutral 65% (2026-04-16) → neutral 65% (2026-04-17) → neutral 65% (2026-04-18) → neutral 65% (2026-04-19) → neutral 65% (2026-04-20) → neutral 65% (2026-04-21) → neutral 65% (2026-04-22) |
| nakagawa-junko ⚬ | board-member | neutral | 50% | neutral 50% (2026-03-20) → neutral 50% (2026-03-23) → neutral 50% (2026-03-24) → neutral 50% (2026-03-25) → neutral 50% (2026-03-26) → neutral 50% (2026-03-27) → neutral 50% (2026-03-30) → neutral 50% (2026-03-31) → neutral 50% (2026-04-01) → neutral 50% (2026-04-02) → neutral 50% (2026-04-03) → neutral 50% (2026-04-06) → neutral 50% (2026-04-07) → neutral 50% (2026-04-08) → neutral 50% (2026-04-09) → neutral 50% (2026-04-10) → neutral 50% (2026-04-12) → neutral 50% (2026-04-13) → neutral 50% (2026-04-14) → neutral 50% (2026-04-15) → neutral 50% (2026-04-16) → neutral 50% (2026-04-17) → neutral 50% (2026-04-18) → neutral 50% (2026-04-19) → neutral 50% (2026-04-20) → neutral 50% (2026-04-21) → neutral 50% (2026-04-22) |
| takata-hajime | board-member | hawkish | 43% | hawkish 95% (2026-03-20) → hawkish 95% (2026-03-23) → hawkish 95% (2026-03-24) → hawkish 95% (2026-03-25) → hawkish 95% (2026-03-26) → hawkish 95% (2026-03-27) → hawkish 95% (2026-03-30) → hawkish 95% (2026-03-31) → hawkish 95% (2026-04-01) → hawkish 95% (2026-04-02) → hawkish 95% (2026-04-03) → hawkish 95% (2026-04-06) → hawkish 95% (2026-04-07) → hawkish 95% (2026-04-08) → hawkish 95% (2026-04-09) → hawkish 95% (2026-04-10) → hawkish 95% (2026-04-12) → hawkish 95% (2026-04-13) → hawkish 95% (2026-04-14) → hawkish 95% (2026-04-15) → hawkish 95% (2026-04-16) → hawkish 95% (2026-04-17) → hawkish 95% (2026-04-18) → hawkish 95% (2026-04-19) → hawkish 95% (2026-04-20) → hawkish 95% (2026-04-21) → hawkish 95% (2026-04-22) |
| tamura-naoki | board-member | hawkish | 43% | hawkish 90% (2026-03-20) → hawkish 90% (2026-03-23) → hawkish 90% (2026-03-24) → hawkish 90% (2026-03-25) → hawkish 90% (2026-03-26) → hawkish 90% (2026-03-27) → hawkish 90% (2026-03-30) → hawkish 90% (2026-03-31) → hawkish 90% (2026-04-01) → hawkish 90% (2026-04-02) → hawkish 90% (2026-04-03) → hawkish 90% (2026-04-06) → hawkish 90% (2026-04-07) → hawkish 90% (2026-04-08) → hawkish 90% (2026-04-09) → hawkish 90% (2026-04-10) → hawkish 90% (2026-04-12) → hawkish 90% (2026-04-13) → hawkish 90% (2026-04-14) → hawkish 90% (2026-04-15) → hawkish 90% (2026-04-16) → hawkish 90% (2026-04-17) → hawkish 90% (2026-04-18) → hawkish 90% (2026-04-19) → hawkish 90% (2026-04-20) → hawkish 90% (2026-04-21) → hawkish 90% (2026-04-22) |
| uchida-shinichi | deputy-governor | neutral | 43% | neutral 60% (2026-03-20) → neutral 60% (2026-03-23) → neutral 60% (2026-03-24) → neutral 60% (2026-03-25) → neutral 60% (2026-03-26) → neutral 60% (2026-03-27) → neutral 60% (2026-03-30) → neutral 60% (2026-03-31) → neutral 60% (2026-04-01) → neutral 60% (2026-04-02) → neutral 60% (2026-04-03) → neutral 60% (2026-04-06) → neutral 60% (2026-04-07) → neutral 60% (2026-04-08) → neutral 60% (2026-04-09) → neutral 60% (2026-04-10) → neutral 60% (2026-04-12) → neutral 60% (2026-04-13) → neutral 60% (2026-04-14) → neutral 60% (2026-04-15) → neutral 60% (2026-04-16) → neutral 60% (2026-04-17) → neutral 60% (2026-04-18) → neutral 60% (2026-04-19) → neutral 60% (2026-04-20) → neutral 60% (2026-04-21) → neutral 60% (2026-04-22) |
| ueda-kazuo | governor | neutral | 43% | neutral 80% (2026-03-20) → neutral 80% (2026-03-23) → neutral 80% (2026-03-24) → neutral 80% (2026-03-25) → neutral 80% (2026-03-26) → neutral 80% (2026-03-27) → neutral 80% (2026-03-30) → neutral 80% (2026-03-31) → neutral 80% (2026-04-01) → neutral 80% (2026-04-02) → neutral 80% (2026-04-03) → neutral 80% (2026-04-06) → neutral 80% (2026-04-07) → neutral 80% (2026-04-08) → neutral 80% (2026-04-09) → neutral 80% (2026-04-10) → neutral 70% (2026-04-12) → neutral 80% (2026-04-13) → neutral 80% (2026-04-14) → neutral 80% (2026-04-15) → neutral 80% (2026-04-16) → neutral 84% (2026-04-17) → neutral 84% (2026-04-18) → neutral 84% (2026-04-19) → neutral 84% (2026-04-20) → neutral 84% (2026-04-21) → neutral 84% (2026-04-22) |

## Policy Cycle

- **Current cycle:** neutral
- **Previous decision:** hold
- **Chair stance:** neutral

## Economic Indicators

| Indicator | Value | Date |
|-----------|-------|------|
| cpi | 1.3% | 2026-03-21 |
| unemployment | 2.5% | 2026-03-28 |
| policy-rate | 0.75% | 2026-03-19 |
| shunto-wages | 5.26% | 2026-03-14 |
| gdp | 0.3% | 2026-02-17 |

*No strong indicator signal at this cutoff.*

## Equilibrium

| Outcome | Probability |
|---------|-------------|
| hold | 63% |
| hike-25 | 16% |
| cut-25 | 10% |
| hike-50 | 8% |
| cut-50 | 4% |

**Direction probabilities:** cut 14% / hold 63% / hike 24%

## What Would Make This Forecast Wrong

- Japan March CPI prints April 24 (3 days before decision) — surprise above 3.5% would re-energize hawks and could flip the call
- Ueda press briefing post-G20 later this week — any walk-back of April 13 dovish pivot would shift equilibrium
- Yen breaks below 160/USD — political pressure for hike to defend currency intensifies
- Hormuz blockade escalation driving oil past $110/bbl — energy import cost spike could force BoJ hand either direction

## Summary Reasoning

The voting equilibrium includes 5 members (of 9 total actors tracked in `actors.edn`). The policy cycle is classified as **neutral**. The chair's stance is **neutral**. The equilibrium produces a **hold** forecast at 63% confidence, without a strong indicator signal.

## Macro Backdrop

As of Apr 17, 2026, the BoJ board dynamic has firmly shifted dovish. Ueda's April 13 speech (delivered by proxy in Tokyo) introduced explicit Middle East caution — 'vigilant' about oil prices and financial market instability — a clear tonal shift from March's guidance of continuing to raise rates. OIS hike probability dropped from ~45% to ~33% post-speech. On Apr 17, Ueda held a post-IMF press conference in Washington reinforcing the same framing, and a companion speech was delivered by Himino in Tokyo. Market-implied April hike probability slid further to ~10% after these remarks — a second leg of dovish repricing.

The Hormuz blockade announcement (Apr 12) pushed Brent past $103/bbl, acutely affecting Japan (90% energy imports). Shunto wages at 5.26% remain strong and support normalization, but Ueda has signaled clearly that the board will wait through the geopolitical shock.

Board splits ~4-5 hold (Ueda cautious, Uchida aligned, Himino aligned, Asada dovish, possibly Masu cautious) / 3-4 hike (Takata dissenter, Tamura, Koeda, possibly Nakagawa). Trade Minister Akazawa (Apr 12) quasi-endorsed a hike to support yen but was immediately rebuked by Finance Minister Katayama. Ex-BoJ official Momma: 'close-call meeting,' BoJ probably hasn't decided yet.

March CPI due April 24 (3 days before decision) could be decisive.

## Institutional Dynamic

*Context that the equilibrium math does not capture but should inform interpretation:*

The May meeting includes the Outlook Report, which publishes updated BoJ staff projections for growth and inflation. If the Outlook Report revises inflation projections upward (reflecting energy passthrough) while maintaining the 2% medium-term target narrative, hawks gain leverage for an earlier hike.

Asada's appointment by Takaichi is the first time in the current normalization cycle that a clearly dovish, politically-aligned member has joined the board — his presence may embolden Ueda to slow the normalization pace without appearing to bow to political pressure directly.

The March Summary of Opinions included a member suggesting a 'larger hike' might be needed, which is an unusually hawkish signal for a BoJ document.

## Key Uncertainty Flags

- **Sealed forecast.** Parameters locked. No post-seal revision.
- Voting member rosters are hand-coded in `actors.edn` for this specific decision. Any personnel changes not yet reflected are a coverage gap.

## Methodology Reference

This sealed forecast uses the methodology described in Casu, J. (2026), "Institutional Actor Modeling in Dodona: A Central Bank Rate Policy Case Study, 2024-2026." Parameters are locked as of the paper's submission date; no per-decision tuning.

The evidence used to generate this forecast is in the companion file `actors.edn` in this directory. Every stance includes a `:last-update` date and a primary-source citation in `:source`.

---

*Dodona is a symbolic cognitive reasoning system for institutional actor modeling. This note is a research output, not investment advice.*
