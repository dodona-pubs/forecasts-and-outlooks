# Dodona Forecast: BoE November 2026 (boe-2026-11-05)

**Decision:** 2026-11-05, Monetary Policy Committee announcement at 12:00 UTC.
**Sealed forecasts, write-once, scored after the announcement and never revised.** This note renders the seals made before the
announcement. Each artifact stays on the production store, and the SHA-256 below commits to its bytes. Later seals and the
post-decision line are appended in separate commits; the text above them is never edited.

The October 2026 campaign seals at **T-14, T-7 and T-1** (decided 2026-10-16). T-1 is a pair:
- **S** reads the served press, and is the SCORED forecast.
- **G** reads the press consensus graphs, and is the comparison arm.

---

## Seals

| Horizon | Evidence cutoff (UTC) | Written (UTC) | Code (fe-cb) | Modal | Ease | Hold | Tighten |
|---|---|---|---|---|---|---|---|
| T-14 | 2026-10-22 20:00 | 2026-10-22 20:34 | 1.58.0 | **HOLD** | 16.0% | 66.3% | 17.7% |
| T-7 | 2026-10-29 20:00 | 2026-10-29 20:40 | 1.73.0 | **TIGHTEN** | 2.6% | 10.6% | 86.9% |
| T-1 | 2026-11-04 20:00 | (pending) | | | | | |

## Full distribution

| Outcome | T-14 | T-7 |
|---|---|---|
| cut-75 | 3.0% | 0.5% |
| cut-50 | 3.4% | 0.6% |
| cut-25 | 9.6% | 1.5% |
| hold | **66.3%** | 10.6% |
| hike-25 | 11.1% | **54.3%** |
| hike-50 | 3.7% | 18.1% |
| hike-75 | 3.0% | 14.4% |

Bank Rate in the model at T-14 and T-7: 3.75%.

## Artifacts (SHA-256 of the sealed file)

| Seal | Path on the production store | SHA-256 | Bytes |
|---|---|---|---|
| T-14 | `results/campaign-2026-10/boe-2026-11-05/T-14.ddn` | `2ee1e13e68fcd360a16736944fdb7d01242d2ab6ee7c53ab69464a3eecfffba4` | 47,087 |
| T-7 | `results/campaign-2026-10/boe-2026-11-05/T-7.ddn` | `0a364ba0a269c61851249044cd6bddf85ac4695ce67ce919c217ba5907de903d` | 62,474 |

## Notes (declared)

- **The daily outlooks have since moved to TIGHTEN at about 87%** (T-9, 2026-10-27, not a seal). The move is driven by press consensus on
  three stories, against a committee read of hold (65.1%):
  - a Reuters poll in which 54 of 63 economists expected a hike at this meeting;
  - a report that a hike was set to come;
  - a report conditional on energy prices staying high.

  UK market pricing (3.95% against a 3.75% Bank Rate) points the same way. The T-7 seal on 2026-10-29 is the first SEAL to carry that read.
- Everything consumed was knowable at each seal's cutoff. Scoring is by direction against the announced decision.

## T-7

Sealed 2026-10-29 20:40 UTC from evidence cut off at 20:00 UTC, before the London Stock Exchange reopened (2026-10-30 08:00 UTC).
**Modal TIGHTEN, 86.9%** (hike-25 54.3%); hold 10.6%. The press-consensus read described above carried into the seal.

- **The tail is too heavy.** 14.4% on a 75 bp hike is not a credible reading of the evidence, which speaks of a 25 bp move. The
  probability is spread up the hike ladder by the same press mechanism that drives the modal. This is recorded with the open
  near-certainty and press-weighting issues.
- One of the three stories behind the tighten read is conditional on energy prices staying high. The model counts it as a plain hike
  call; treating the condition as evidence of its own is open work.
- **Correction (2026-10-29):** this note first gave the T-7 cutoff as 2026-10-28. T-7 for a 5 November decision is 29 October, the date
  the seal was actually made; the cutoff and the date in the notes above are corrected.

## T-1

(appended after the T-1 seal, in a separate commit)

## Post-decision

(appended after the announcement, in a separate commit)
