# Dodona Forecast: FOMC October 2026 (fomc-2026-10-28)

**Decision:** 2026-10-28, FOMC statement at 18:00 UTC.
**Sealed forecasts, write-once, scored after the announcement and never revised.** This note renders the seals made before the
announcement. Each artifact (the full exact-rational distribution, the reasoning chain, and the store and config identity) stays on
the production store. The SHA-256 below commits to its bytes. Later lines are appended in separate commits; the text above them is
never edited.

The October 2026 campaign seals at **T-14, T-7 and T-1** (decided 2026-10-16). T-1 is a pair:
- **S** reads the served press, and is the SCORED forecast.
- **G** reads the press consensus graphs, and is the comparison arm.

---

## Seals

| Horizon | Evidence cutoff (UTC) | Written (UTC) | Code (fe-cb) | Modal | Ease | Hold | Tighten |
|---|---|---|---|---|---|---|---|
| T-14 | — | — | — | **MISSED**: the window closed without a seal; never made late | | | |
| T-7 | 2026-10-22 01:00 | 2026-10-22 01:52 | 1.55.1 | **hike-25** | 23.4% | 10.1% | 66.5% |
| **T-1 S (scored)** | 2026-10-28 01:00 | 2026-10-28 01:58 | 1.70.0 | **HOLD** | 23.4% | **60.2%** | 16.4% |
| T-1 G (comparison) | 2026-10-28 01:00 | 2026-10-28 03:38 | 1.70.0 | HOLD | 1.4% | 97.7% | 1.0% |

## Full distributions

| Outcome | T-7 | **T-1 S** | T-1 G |
|---|---|---|---|
| cut-75 | 5.0% | 5.0% | 0.3% |
| cut-50 | 5.0% | 5.0% | 0.3% |
| cut-25 | 13.4% | 13.5% | 0.8% |
| hold | 10.1% | **60.2%** | 97.7% |
| hike-25 | 60.0% | 10.1% | 0.6% |
| hike-50 | 3.2% | 3.2% | 0.2% |
| hike-75 | 3.2% | 3.2% | 0.2% |

## Artifacts (SHA-256 of the sealed file)

| Seal | Path on the production store | SHA-256 | Bytes |
|---|---|---|---|
| T-7 | `results/campaign-2026-10/fomc-2026-10-28/T-7.ddn` | `0404d43f609d768d457c5493ffd3a6880660420a67621dff24092173433267e9` | 79,666 |
| T-1 S | `results/probation-145/fomc-2026-10-28.S.ddn` | `a2b9ccc39d1a872c962a0eaa64f64385e14173dd97022a26e62316598340f57a` | 129,698 |
| T-1 G | `results/probation-145/fomc-2026-10-28.G.ddn` | `cc64a04eb81bc2152096a5bb7a0a95acd42c5efdd103228fb1512a7ce8cd1a46` | 129,187 |

## Notes (declared)

- **The call moved from hike (T-7) to hold (T-1).** Between the two seals the code moved from fe-cb 1.55.1 to 1.70.0, including the 1.4.24
  press read adopted 2026-10-25 (the press counts only stories about THIS meeting). Which change moved the call is NOT traced in this note.
  The T-7 seal stands as sealed and will be scored as sealed.
- The daily ladder's T-2 forecast (cutoff 2026-10-27 01:00 UTC, not a seal horizon) read the same as T-1 S: ease 23.4%, hold 60.2%,
  tighten 16.4%.
- **S vs G:** the two arms differ only in how the press is read. The served stories leave a quarter of the mass on cuts. The consensus graphs
  read hold as near-certain.
- Everything consumed was knowable at each seal's cutoff. Market prices enter only as regulated or official priced sources.
- Scoring is by direction (ease / hold / tighten) against the announced decision.

## Post-decision

(appended after the announcement, in a separate commit)
