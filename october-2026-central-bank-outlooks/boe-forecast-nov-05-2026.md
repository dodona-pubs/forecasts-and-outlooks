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
| T-7 | 2026-10-28 20:00 | (pending) | | | | | |
| T-1 | 2026-11-04 20:00 | (pending) | | | | | |

## Full distribution (T-14)

| Outcome | T-14 |
|---|---|
| cut-75 | 3.0% |
| cut-50 | 3.4% |
| cut-25 | 9.6% |
| **hold** | **66.3%** |
| hike-25 | 11.1% |
| hike-50 | 3.7% |
| hike-75 | 3.0% |

Bank Rate in the model at T-14: 3.75%.

## Artifacts (SHA-256 of the sealed file)

| Seal | Path on the production store | SHA-256 | Bytes |
|---|---|---|---|
| T-14 | `results/campaign-2026-10/boe-2026-11-05/T-14.ddn` | `2ee1e13e68fcd360a16736944fdb7d01242d2ab6ee7c53ab69464a3eecfffba4` | 47,087 |

## Notes (declared)

- **The daily outlooks have since moved to TIGHTEN at about 87%** (T-9, 2026-10-27, not a seal). The move is driven by press consensus on
  three stories, against a committee read of hold (65.1%):
  - a Reuters poll in which 54 of 63 economists expected a hike at this meeting;
  - a report that a hike was set to come;
  - a report conditional on energy prices staying high.

  UK market pricing (3.95% against a 3.75% Bank Rate) points the same way. The T-7 seal on 2026-10-28 is the first SEAL to carry that read.
- Everything consumed was knowable at each seal's cutoff. Scoring is by direction against the announced decision.

## T-7

(appended after the T-7 seal, in a separate commit)

## T-1

(appended after the T-1 seal, in a separate commit)

## Post-decision

(appended after the announcement, in a separate commit)
