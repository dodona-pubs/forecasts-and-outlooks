# Thornhill Shadow Forecast: ECB July 2026

**Frozen:** 2026-07-22 19:20 UTC (cutoff 2026-07-22 19:00 UTC)
**Decision date:** 2026-07-23 (Governing Council; announcement ~12:15 UTC)
**SHADOW forecast — day-before-cutoff freeze, scored post-announcement, never revised.**

This is a write-once record produced by the 1.3.2-12 §8 cutoff-freeze harness during the
July-2026 shadow week. It is not a live published call; the July campaign runs shadow-only
by design. The canonical artifact (full exact-rational distribution, complete reasoning
chain, store/config identity) is `results/shadow/ecb-2026-07-23.ddn` on the production
store; this note is its human-readable rendering, written 2026-07-22.

---

## Summary

**Modal outcome: HOLD** — Deposit Facility Rate stays at 2.25%.

**Margin:** 0.418 over the runner-up (hike-25).

| Direction | Probability |
|-----------|------------|
| Hold | 69.8% |
| Tighten | 28.0% |
| Ease | 2.1% |

## Full distribution

| Outcome | Probability |
|---------|------------|
| cut-75 | 0.3% |
| cut-50 | 0.6% |
| cut-25 | 1.2% |
| **hold** | **69.8%** |
| hike-25 | 26.8% |
| hike-50 | 0.8% |
| hike-75 | 0.4% |

## The read

The hold is priced and corroborated: the freshest knowable consumable priced expectation —
the ECB's own Survey of Monetary Analysts round published 2026-06-15, which post-dates the
June 11 surprise hike — implies a July move of exactly 0.000 at DFR 2.25.

The 26.8% on hike-25 is not noise. It is the June energy-shock residue: the Middle-East
conflict's commodity spike (March 2026 onward) drove the June surprise-hike cluster
(ECB +25 on 06-11, BoJ +25 on 06-16, two BoE dissents for hikes on 06-18), and the
committee's post-June communications still carry hawkish stance mass. The distribution
reads "hold, with a real one-in-four continuation risk" — not a complacent hold. If the
Governing Council hikes again tomorrow, that tail is where the honest uncertainty lived.

## Evidence cutoff

Everything consumed was knowable at **2026-07-22 19:00 UTC** (the day-before-EOB
discipline). No same-day or announcement-day data enters. The store's manifest-licensed
read served derive-version 14 (the enforced sidecar handshake + derive-manifest tuple);
guidance items exist in-store at v14 but are **unconsumed** (the §9 consumption license is
pre-registered, not yet measured — this forecast's mechanism set is the committed 120/140
baseline configuration plus the priced-expectations license).

## Market comparison

None included. Per standing doctrine, prediction-market reads (Kalshi/Polymarket) are
comparison-only and were not collected for this shadow freeze; regulated/official priced
sources (the SMA leg above) are the only consumables. Declared absent, not omitted.

## Differences from the tng-family sealed forecasts (declared)

- Single day-before freeze; no T-7 seal, no convergence history (the daily-outlook cadence
  is not running during shadow week).
- Full seven-outcome distribution rather than direction buckets.
- Shadow scoring: `(score-shadow-forecast "ecb-2026-07-23" ACTUAL)` after the announcement;
  the post-decision line will be appended below, never edited above.

## Post-decision

*(to be appended after the 2026-07-23 announcement — outcome, direction-scored result,
and whether the hike tail or the hold carried.)*
