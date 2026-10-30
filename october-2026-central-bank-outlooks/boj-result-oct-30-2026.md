# Dodona Result: BoJ October 2026 (boj-2026-10-30)

Scores the sealed forecasts in `boj-forecast-oct-30-2026.md`, `boj-t2-oct-30-2026.md` and `boj-t1-oct-30-2026.md`. Those notes are left
exactly as they were published. This is a separate document, so they keep their original timestamps.

**Announced 2026-10-30: HOLD**, with the uncollateralized overnight call rate kept at around 1.25%, by **an 8–1 vote**. One member,
Takata Hajime, dissented for a **hike to around 1.5%**: "with underlying CPI inflation having reached the price stability target, the
situation had shifted to a new phase in which the Bank needs to step up the pace of bringing the policy interest rate closer to the
neutral interest rate". The proposal was defeated by a majority vote.
Separately, by a unanimous vote, the Bank raised the pace of its ETF sales from about 330 to about 860 billion yen a year (book value),
from January 2027.
Source: Bank of Japan, "Statement on Monetary Policy", 30 October 2026
(https://www.boj.or.jp/en/mopo/mpmdeci/mpr_2026/k261030a.pdf).

| Seal | Evidence cutoff (UTC) | Modal | P(hold) | P(tighten) | Direction scored |
|---|---|---|---|---|---|
| T-14 | — | MISSED | | | not scored |
| T-7 | 2026-10-23 11:00 | hold | 92.0% | 4.9% | correct |
| T-2 | 2026-10-28 11:00 | hold | 99.1% | 0.6% | correct |
| **T-1 S (scored)** | 2026-10-29 11:00 | **hold** | **99.1%** | 0.6% | **correct** |
| T-1 G (comparison) | — | MISSED | | | not scored |

Seal SHA-256s are listed in the forecast notes.

## Notes

- The direction was right at every sealed horizon.
- **The hike dissent was not in the forecast.** One of nine members voted for a 25 bp hike. The seals put 0.6% on any tighten at T-2 and T-1, down from 4.9% at T-7. The forecasts give a direction only, with no vote
  split, so the dissent could not be scored. A board leaning 8–1 is not the 99% certainty the seals expressed. As at the FOMC this
  month (two hike dissents), the vote is information the forecast does not yet carry.
- The 99.1% hold is a known near-certainty defect, declared in the T-2 and T-1 notes.
