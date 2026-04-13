# Dodona Outlook: BoJ May 2026

**Note generated:** 2026-04-12
**Decision date:** 2026-04-27
**25 days before decision — OUTLOOK (not for publication)**

---

## Summary

**Predicted direction:** hold

**Direction confidence:** 60% [48%, 69%]

*This is an outlook, not a sealed forecast. The decision is more than two weeks away; material new evidence may arrive before the seal date.*

## Actor Stance Snapshot

Cutoff: 2026-04-27. All evidence below predates this date. Strict temporal holdout enforced at the data layer.

| Actor | Role | Stance | Confidence | Basis |
|-------|------|--------|-----------|-------|
| himino-ryozo | deputy-governor | neutral | 43% | forecast-2026-04-12-boj |
| takata-hajime | board-member | hawkish | 43% | forecast-2026-04-12-boj |
| tamura-naoki | board-member | hawkish | 43% | forecast-2026-04-12-boj |
| uchida-shinichi | deputy-governor | neutral | 43% | forecast-2026-04-12-boj |
| ueda-kazuo | governor | neutral | 87% | forecast-2026-04-12-boj |

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
| shunto-wages | 5.9% | 2026-03-14 |
| gdp | 0.3% | 2026-02-17 |

**Indicator signal:** cut at strength 0.5

## Equilibrium

| Outcome | Probability |
|---------|-------------|
| hold | 60% |
| cut-25 | 15% |
| cut-50 | 11% |
| hike-25 | 9% |
| hike-50 | 4% |

**Direction probabilities:** cut 26% / hold 60% / hike 14%

## Convergence Conditions

- **Chair stance:** neutral
- **Equilibrium direction:** hold
- **Indicator direction:** cut
- **Previous decision:** hold

## Summary Reasoning

The system evaluated 5 voting members in a policy cycle currently classified as **neutral**. The chair's stance is **neutral**. The equilibrium produces a **hold** prediction at 60% confidence, supported by a cut indicator signal at strength 0.5.

## Macro Backdrop

As of Apr 12, 2026, the BoJ Policy Board faces a uniquely Japanese version of the Iran war dilemma. Japan imports ~90% of its energy, making it acutely vulnerable to the oil/gas price spike. However, headline CPI fell to 1.3% in February (below 2% target) due to government energy subsidies. Shunto wage demands at 5.9% are the strongest in decades, supporting the BoJ's normalization thesis. The board splits 3 hawks (Takata, Tamura, Koeda) / 4 neutrals (Ueda, Uchida, Himino, Nakagawa — with Ueda and Masu leaning hawkish) / 1 dove (Asada, new Takaichi appointee). Takata dissented at the March meeting for a hike to 1.0%. PM Takaichi has voiced reservations about hikes directly to Ueda. The market was pricing ~69% probability of a hike at the next meeting before the Iran shock. The neutral rate is discussed openly at 1.0%-2.5%, well above the current 0.75%. Bottom line: hold is the likely baseline for May given Iran uncertainty + political pressure, but the normalization direction is intact and a hike at the June or subsequent meeting remains the expected trajectory.

## Institutional Dynamic

*Context that the equilibrium math does not capture but should inform interpretation:*

The May meeting includes the Outlook Report, which publishes updated BoJ staff projections for growth and inflation. If the Outlook Report revises inflation projections upward (reflecting energy passthrough) while maintaining the 2% medium-term target narrative, hawks gain leverage for an earlier hike. Asada's appointment by Takaichi is the first time in the current normalization cycle that a clearly dovish, politically-aligned member has joined the board — his presence may embolden Ueda to slow the normalization pace without appearing to bow to political pressure directly. The March Summary of Opinions included a member suggesting a 'larger hike' might be needed, which is an unusually hawkish signal for a BoJ document.

## Key Uncertainty Flags

- **Outlook mode**: this is not a sealed prediction. The decision is more than two weeks away.
- Voting member rosters are hand-coded in `actors.edn` for this specific forecast. Any personnel changes not yet reflected are a coverage gap.
- **Thin actor coverage**: fewer than 6 voting members have current stance data.

## Market Consensus Snapshot (April 12, 2026)

| Source | Hold | Hike-25 | Hike-50 | Cut | Notes |
|--------|------|---------|---------|-----|-------|
| [Polymarket](https://polymarket.com/event/bank-of-japan-decision-in-april) | 38% | 55% | 3% | <1% | $565K volume (highest of four CBs); genuinely split market |
| Reuters survey (44 economists) | ~50-55% | ~27% (April specific) | — | — | June preferred (32%), then July (30%), then April (27%) |
| OIS-implied | ~38% | ~62% | — | — | Consistent with Polymarket lean toward hike |
| ING | Hold (base case Oct hike) | — | — | — | Could accelerate to Q2 if yen past 160 |
| Nomura / BofA | Hold in April | June hike (base) | — | — | Terminal 1.50% |
| Ex-BoJ officials (Apr 2-8) | — | April hike "likely" | — | — | Two former officials stated publicly |

### Dodona vs Market

| Outcome | Dodona | Market range | Divergence |
|---------|--------|-------------|------------|
| Hold | **60%** | 38-55% | **Dodona more confident in hold than Polymarket/OIS** |
| Hike | **14%** | 55-62% (Polymarket/OIS) | **Dodona sees far less hike probability** |
| Cut | **26%** | <1% | **Dodona sees a large dovish tail markets don't** |

**Largest divergence: hike direction.** Markets are pricing 55-62% for a hike — Dodona sees only 14%. The divergence comes from Dodona's actor-level model weighting the political pressure from PM Takaichi, Asada's dovish appointment, and the Iran-war energy shock against a Japan that imports 90% of its energy. Markets are pricing the strong Shunto wage data (5.9%) and the hawks' (Takata, Tamura, Koeda) normalization signals; Dodona is giving more weight to the institutional constraints that could prevent the hawks from carrying a majority. The 26% cut tail reflects Dodona's assessment that if the energy shock worsens, even some neutral members could flip dovish.

**This is the most contested of the four decisions** — the market itself is nearly split, and Dodona disagrees with the market lean. If BoJ holds, Dodona called it against the market. If BoJ hikes, the market called it and Dodona overweighted the dovish institutional pressures.

## Methodology Reference

This outlook uses the methodology described in Casu, J. (2026), "Institutional Actor Modeling in Dodona: A Central Bank Rate Policy Case Study, 2024-2026."

Parameters are locked as of the hindcast paper submission. No adjustment has been made for this prediction.

The evidence used to generate this outlook is in the companion file `actors.edn` in this directory.

---

*Dodona is a symbolic cognitive reasoning system for institutional actor modeling. This note is a research output, not investment advice.*
