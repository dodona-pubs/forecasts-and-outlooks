# Dodona Forecast: ECB October 2026 (ecb-2026-10-29)

**Decision:** 2026-10-29, Governing Council press release at 12:15 UTC.
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
| T-14 | — | — | — | **MISSED**: the window closed without a seal; never made late | | | |
| T-7 | 2026-10-22 19:00 | 2026-10-22 19:37 | 1.58.0 | **HOLD** | 0.1% | 92.6% | 7.3% |
| T-1 | 2026-10-28 19:00 | (pending) | | | | | |

## Full distribution (T-7)

| Outcome | T-7 |
|---|---|
| cut-75 | 0.0% |
| cut-50 | 0.0% |
| cut-25 | 0.1% |
| **hold** | **92.6%** |
| hike-25 | 7.2% |
| hike-50 | 0.1% |
| hike-75 | 0.0% |

The model's deposit facility rate at T-7: 2.50%.

## Artifacts (SHA-256 of the sealed file)

| Seal | Path on the production store | SHA-256 | Bytes |
|---|---|---|---|
| T-7 | `results/campaign-2026-10/ecb-2026-10-29/T-7.ddn` | `52923e71f42befdee611f5573bff4e3ae85017ee9f5ee6d0d5bbfcc74e415534` | 59,110 |

## Notes (declared)

- The daily outlooks since T-7 (not seals) have read hold at 100%. That near-certainty is a known open issue: a fix (a course prior)
  was tested on 2026-10-27 and failed its gate.
- Everything consumed was knowable at each seal's cutoff. Scoring is by direction against the announced decision.

## T-1

(appended after the T-1 seal, in a separate commit)

## Post-decision

(appended after the announcement, in a separate commit)
