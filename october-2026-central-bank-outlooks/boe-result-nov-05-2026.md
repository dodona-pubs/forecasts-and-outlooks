# Dodona Result: BoE November 2026 (boe-2026-11-05)

Scores the sealed forecasts in `boe-forecast-nov-05-2026.md` (T-14 and T-7) and the T-2 and T-1 seals listed below. That note is left
exactly as it was published. This is a separate document, so it keeps its original timestamp.

**Announced 2026-11-05: HIKE of 25 bp.** Bank Rate rose from 3.75% to 4%, by **an 8–1 vote**:
- Eight members voted for the increase: Andrew Bailey, Sarah Breeden, Swati Dhingra, Megan Greene, Clare Lombardelli, Huw Pill,
  Dave Ramsden and Alan Taylor.
- Catherine L Mann voted against, **preferring a 50 bp increase to 4.25%**.

The Committee's reason: "the degree of inflationary pressure in the pipeline is now sufficient to warrant an increase in Bank Rate.
Activity data in recent months have generally been stronger than expected, adding to the case for modestly tighter monetary policy."

Source: Bank of England, "Bank rate increased to 4% - November 2026 Monetary Policy Summary and Minutes", 5 November 2026
(https://www.bankofengland.co.uk/monetary-policy-summary-and-minutes/2026/november-2026).

| Seal | Evidence cutoff (UTC) | Modal | P(hold) | P(tighten) | P(hike-25) | Direction scored |
|---|---|---|---|---|---|---|
| T-14 | 2026-10-22 20:00 | hold | 66.3% | 17.7% | 11.1% | incorrect |
| T-7 | 2026-10-29 20:00 | tighten | 10.6% | 86.9% | 54.3% | correct |
| T-2 | 2026-11-03 20:00 | tighten | 10.8% | 86.7% | 54.2% | correct |
| **T-1 S (scored)** | 2026-11-04 20:00 | **tighten** | **10.8%** | **86.7%** | **54.2%** | **correct** |
| T-1 G (comparison) | — | MISSED | | | | not scored |

## The T-2 and T-1 seals

Both were sealed and hashed on the production store before the London Stock Exchange opened, which is the seal deadline. No note was
published for either before the announcement, so they are listed here.

| Seal | Written (UTC) | Seal deadline (UTC) | Code (fe-cb) | Path on the production store | SHA-256 | Bytes |
|---|---|---|---|---|---|---|
| T-2 | 2026-11-04 00:38 | 2026-11-04 08:00 | 1.80.0 | `results/campaign-2026-10/boe-2026-11-05/T-2.ddn` | `018788600168442d67b2ebb855eb927cb4666cf09ce702c4b7b1c22338c3296e` | 40,481 |
| T-1 S | 2026-11-05 01:38 | 2026-11-05 08:00 | 1.80.0 | `results/probation-145/boe-2026-11-05.S.ddn` | `b9f89237f31345c06453c40520da7cee69982ea05872bca369687ad7e26504aa` | 40,372 |
| T-1 G | MISSED at the due pass | | | `results/probation-145/boe-2026-11-05.G.MISSED.ddn` | `27ba59c3d984c27d336c860db376898ab87c75ce76e332db5256636f1706cd73` | 185 |

The T-2 and T-1 S distributions are identical to the rounding shown:

| Outcome | T-2 | T-1 S |
|---|---|---|
| cut-75 | 0.5% | 0.5% |
| cut-50 | 0.6% | 0.6% |
| cut-25 | 1.5% | 1.5% |
| hold | 10.8% | 10.8% |
| **hike-25** | **54.2%** | **54.2%** |
| hike-50 | 18.1% | 18.1% |
| hike-75 | 14.4% | 14.4% |

Bank Rate in the model at T-2 and T-1: 3.75%. Market pricing in the model: 3.97%, as of 3 November.

## Notes

- **The direction was right at T-7, T-2 and T-1, and wrong at T-14.** T-14 called hold at 66.3%. Every outlook and seal made from the 24 October
  cutoff (T-12) on called tighten, at 85–87%.
- **The size matched too, but it is not scored.** The modal outcome at T-7, T-2 and T-1 was a 25 bp hike (54.2–54.3%), the size the Bank
  chose. Scoring is by direction.
- **The test named in the T-7 note came out for the press term.** The committee read (nine voters weighted by their vote histories)
  stayed at hold, 65.5% at T-1, and every member voted to raise Bank Rate. The call came from the press consensus for a tighten, applied as a
  measured likelihood ratio of 28. This is the first out-of-sample case in which the press term was right against the committee read.
  It is one decision. As the T-7 note said, a correct call here shows the model read the consensus correctly, not that it knew more than
  the consensus.
- **The committee read was out of date.** The seals carried three members' stances, Bailey's, Breeden's and Dhingra's, from signals older
  than the model's 91-day staleness bound, as neutral; all three voted to hike. The seals read Mann, Pill and Taylor as hawkish. Mann
  dissented for 50 bp; Pill and Taylor voted for 25 bp.
- **The dissent was not in the forecast.** The seals give a direction distribution only, with no vote split, so the 8–1 split and the
  50 bp dissent are not scored. The seals put 18.1% on a 50 bp hike. No member voted for 75 bp. The T-7 note declared the 14.4% on a
  75 bp hike too heavy, and that stands. Forecasting the vote split is open work, as it was after the FOMC and BoJ results this month.
- **Measured confidence.** From fe-cb 1.80.0 each seal states how often this engine's earlier forecasts for the same bank, in the same
  10-point probability band, were right. The T-2 and T-1 S both read: 2 of 2 earlier BoE forecasts in the 80–90% band were right (95% interval
  34.2–100%). That record covers the years the model was developed on, so it is in-sample, and it is thin.
- **One price input failed to refresh at the T-1 seal.** The download of the Bank's OIS curve failed with a transient error, and the
  seal used the last stored curve (3 November). The Bank's file held no newer curve at the time, so the forecast was not affected. The
  seal file does not yet record a failed refresh, and the refresh does not retry. Both are being fixed.
- **The comparison arm (G) was not made**, as at the ECB and BoJ. Its consensus graphs are rebuilt only for banks whose meeting calendar
  is fully captured, which today is the FOMC only.
- Everything consumed was knowable at each seal's cutoff.

## The October 2026 campaign

This closes the campaign. The scored seal (T-1 S) was right on direction for all four decisions:

| Decision | Announced | T-1 S |
|---|---|---|
| FOMC 2026-10-28 | hold (two dissents for a 25 bp hike) | hold, correct |
| ECB 2026-10-29 | hold | hold, correct |
| BoJ 2026-10-30 | hold (one dissent for a hike) | hold, correct |
| BoE 2026-11-05 | 25 bp hike (one dissent for 50 bp) | tighten, correct |

The earlier seals did worse: FOMC T-7 (hike) and BoE T-14 (hold) were wrong. None of the four forecasts carried the dissents.
