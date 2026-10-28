# Dodona Forecast: BoJ October 2026 (boj-2026-10-30)

**Decision:** 2026-10-30, Policy Board statement (no fixed release time; usually around 03:00 UTC).
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
| T-7 | 2026-10-23 11:00 | 2026-10-24 00:46 | 1.59.1 | **HOLD** | 3.1% | 92.0% | 4.9% |
| T-1 | 2026-10-29 11:00 | (pending) | | | | | |

## Full distribution (T-7)

| Outcome | T-7 |
|---|---|
| cut-50 | 1.4% |
| cut-25 | 1.7% |
| **hold** | **92.0%** |
| hike-25 | 3.6% |
| hike-50 | 1.2% |

## Artifacts (SHA-256 of the sealed file)

| Seal | Path on the production store | SHA-256 | Bytes |
|---|---|---|---|
| T-7 | `results/campaign-2026-10/boj-2026-10-30/T-7.ddn` | `847087a20e553bb8e5734a51455be2113751a230ead79703c0ee6d76a5b0cbae` | 488,288 |

## Notes (declared)

- **The policy rate input changes between T-7 and T-1.**
  - At T-7 the model read the BoJ policy rate from the monthly-average call-rate series, which gave 1.043. That average lags the decided
    rate.
  - From fe-cb 1.72.0 (adopted 2026-10-27) it reads the BoJ's own stated target, 1.25%. The T-1 seal is made under that change.
  - The adoption rested on the full forecast board (no marquee decision lost; forward decisions 12 of 12) and on traces of every row that
    moved.
- Everything consumed was knowable at each seal's cutoff. Scoring is by direction against the announced decision.

## T-1

(appended after the T-1 seal, in a separate commit)

## Post-decision

(appended after the announcement, in a separate commit)
