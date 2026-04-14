# Dodona Outlook: BoJ April 2026

**Note generated:** 2026-04-13
**Decision date:** 2026-04-27
**14 days before decision — OUTLOOK (not for publication)**

---

## Summary

**Predicted direction:** hold

**Direction confidence:** 56% [45%, 65%]

*This is an outlook, not a sealed forecast. The decision is more than two weeks away; material new evidence may arrive before the seal date.*

## Actor Stance Snapshot

Cutoff: 2026-04-27. All evidence below predates this date. Strict temporal holdout enforced at the data layer.

| Actor | Role | Stance | Confidence | Basis |
|-------|------|--------|-----------|-------|
| adachi-seiji | board-member | neutral | 43% | boj-pub |
| himino-ryozo | deputy-governor | neutral | 77% | forecast-2026-04-13-boj |
| nakagawa-junko | board-member | neutral | 43% | boj-pub |
| nakamura-toyoaki | board-member | dovish | 43% | boj-pub |
| noguchi-asahi | board-member | dovish | 43% | boj-pub |
| takata-hajime | board-member | hawkish | 53% | forecast-2026-04-13-boj |
| tamura-naoki | board-member | hawkish | 77% | forecast-2026-04-13-boj |
| uchida-shinichi | deputy-governor | neutral | 77% | forecast-2026-04-13-boj |
| ueda-kazuo | governor | neutral | 92% | forecast-2026-04-13-boj |

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

**Indicator signal:** cut at strength 0.5

## Equilibrium

| Outcome | Probability |
|---------|-------------|
| hold | 56% |
| cut-25 | 16% |
| cut-50 | 12% |
| hike-25 | 11% |
| hike-50 | 5% |

**Direction probabilities:** cut 28% / hold 56% / hike 15%

## Convergence Conditions

- **Chair stance:** neutral
- **Equilibrium direction:** hold
- **Indicator direction:** cut
- **Previous decision:** hold

## Summary Reasoning

The system evaluated 9 voting members in a policy cycle currently classified as **neutral**. The chair's stance is **neutral**. The equilibrium produces a **hold** prediction at 56% confidence, supported by a cut indicator signal at strength 0.5.

## Macro Backdrop

As of Apr 13, 2026 (Apr 14 Tokyo time), the BoJ board dynamic has shifted dovish. Ueda's April 13 speech (delivered by proxy in Tokyo) introduced explicit Middle East caution — 'vigilant' about oil prices and financial market instability — a clear tonal shift from March's guidance of continuing to raise rates. OIS hike probability dropped from ~45% to ~33% post-speech. The Hormuz blockade announcement (Apr 12) pushed Brent past $103/bbl, acutely affecting Japan (90% energy imports). Shunto wages at 5.26% remain strong and support normalization, but Ueda is signaling the board will wait through the geopolitical shock. Board splits ~4-5 hold (Ueda cautious, Uchida aligned, Himino aligned, Asada dovish, possibly Masu cautious) / 3-4 hike (Takata dissenter, Tamura, Koeda, possibly Nakagawa). Trade Minister Akazawa (Apr 12) quasi-endorsed a hike to support yen but was immediately rebuked by Finance Minister Katayama. Ex-BoJ official Momma: 'close-call meeting,' BoJ probably hasn't decided yet. March CPI due April 24 (3 days before decision) could be decisive.

## Institutional Dynamic

*Context that the equilibrium math does not capture but should inform interpretation:*

The May meeting includes the Outlook Report, which publishes updated BoJ staff projections for growth and inflation. If the Outlook Report revises inflation projections upward (reflecting energy passthrough) while maintaining the 2% medium-term target narrative, hawks gain leverage for an earlier hike. Asada's appointment by Takaichi is the first time in the current normalization cycle that a clearly dovish, politically-aligned member has joined the board — his presence may embolden Ueda to slow the normalization pace without appearing to bow to political pressure directly. The March Summary of Opinions included a member suggesting a 'larger hike' might be needed, which is an unusually hawkish signal for a BoJ document.

## Key Uncertainty Flags

- **Outlook mode**: this is not a sealed prediction. The decision is more than two weeks away.
- Voting member rosters are hand-coded in `actors.edn` for this specific forecast. Any personnel changes not yet reflected are a coverage gap.

## Market Consensus Snapshot (April 13, 2026)

*Data collected: April 13, 2026 (post-Ueda speech)*

| Source | Hold | Hike 25bp | Hike 50bp | Cut | Notes |
|--------|------|-----------|-----------|-----|-------|
| [Polymarket](https://polymarket.com/event/bank-of-japan-decision-in-april) | 83% | 15% | <1% | <1% | $645K volume (thin market) |
| OIS-implied (Bloomberg) | ~67% | ~33% | — | — | Post-Ueda; was ~45% hike pre-speech, ~60% last Friday |

### Dodona vs Market

| Outcome | Dodona | OIS (institutional) | Polymarket (retail) | Divergence |
|---------|--------|--------------------|--------------------|------------|
| Hold | **56%** | 67% | 83% | **Dodona less confident in hold than both markets** |
| Hike | **16%** | 33% | 15% | **Dodona less confident in hike than OIS** |
| Cut | **28%** | <1% | <1% | **Dodona sees a large dovish tail neither market prices** |

**Key development: market converging toward Dodona.** On April 12, OIS priced ~60% hike. After Ueda's April 13 dovish speech ("vigilant" on Middle East, oil risks), OIS dropped to ~33% hike. Dodona called hold at 60% on April 12, before the Ueda speech. The market is now moving in Dodona's direction. However, Dodona's 28% cut tail is a signal neither prediction market prices — this reflects the model's assessment that if the Hormuz blockade worsens (Brent already $103+), even some neutral members could flip dovish given Japan's 90% energy import dependency. March CPI due April 24 (3 days before decision) could be decisive.

## Methodology Reference

This outlook uses the methodology described in Casu, J. (2026), "Institutional Actor Modeling in Dodona: A Central Bank Rate Policy Case Study, 2024-2026."

Parameters are locked as of the hindcast paper submission. No adjustment has been made for this prediction.

The evidence used to generate this outlook is in the companion file `actors.edn` in this directory.

---

*Dodona is a symbolic cognitive reasoning system for institutional actor modeling. This note is a research output, not investment advice.*
