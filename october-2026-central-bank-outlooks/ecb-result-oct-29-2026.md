# Dodona Result: ECB October 2026 (ecb-2026-10-29)

Scores the sealed forecasts in `ecb-forecast-oct-29-2026.md` and `ecb-t1-oct-29-2026.md`. Those notes are left exactly as they were
published. This is a separate document, so they keep their original timestamps.

**Announced 2026-10-29: HOLD.** The deposit facility, main refinancing operations and marginal lending facility rates remain at 2.50%,
2.65% and 2.90%. The press release states no vote.
Source: ECB press release "Monetary policy decisions", 29 October 2026
(https://www.ecb.europa.eu/press/pr/date/2026/html/ecb.mp261029~9a493adf17.en.html).

| Seal | Evidence cutoff (UTC) | Modal | P(hold) | Direction scored |
|---|---|---|---|---|
| T-14 | — | MISSED | | not scored |
| T-7 | 2026-10-22 19:00 | hold | 92.6% | correct |
| T-2 | 2026-10-27 19:00 | hold | 100% | correct |
| **T-1 S (scored)** | 2026-10-28 19:00 | **hold** | **100%** | **correct** |
| T-1 G (comparison) | — | MISSED | | not scored |

The T-7 and T-1 SHA-256s are listed in their notes. The T-2 was sealed on the production store at 2026-10-27 19:42 UTC but was not
published in a note before the announcement: `results/campaign-2026-10/ecb-2026-10-29/T-2.ddn`, SHA-256
`552907503637e3616a537cb54f52260529c27cb6f90b7efdb55f6640c99353b2`, 43,883 bytes.

## Notes

- The direction was right at every sealed horizon. The 100% hold at T-2 and T-1 remains a defect, not earned confidence: an honest
  forecast never puts zero probability on a move, and the same reading would have been just as certain had the Council moved.
- Press coverage of the decision cites the energy shock as an inflation driver and puts a December hike in focus (Morningstar
  headline, 2026-10-29). The seals carried 7.3% on a hike at T-7 and none at T-1, so the model's view of the hike case narrowed while
  the press widened it. This is recorded for the near-certainty investigation.
- The same day, the ECB announced that President Lagarde will step down on 7 February 2027, with her successor appointed by the
  European Council (ECB press release, 29 October 2026). The October seals had no view of this. The coming ECB forecasts must
  account for a departing President and a pending succession.
