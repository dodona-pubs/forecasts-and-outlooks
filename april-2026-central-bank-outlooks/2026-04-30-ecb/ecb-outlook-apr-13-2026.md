# Dodona Outlook: ECB April 2026

**Note generated:** 2026-04-13
**Decision date:** 2026-04-30
**17 days before decision — OUTLOOK (not for publication)**

---

## Summary

**Predicted direction:** hold

**Direction confidence:** 40% [32%, 46%]

*This is an outlook, not a sealed forecast. The decision is more than two weeks away; material new evidence may arrive before the seal date.*

## Actor Stance Snapshot

Cutoff: 2026-04-30. All evidence below predates this date. Strict temporal holdout enforced at the data layer.

| Actor | Role | Stance | Confidence | Basis |
|-------|------|--------|-----------|-------|
| cipollone-piero | executive-board | neutral | 77% | forecast-2026-04-13-ecb |
| elderson-frank | executive-board | neutral | 43% | forecast-2026-04-13-ecb |
| lagarde-christine | president | hawkish | 45% | forecast-2026-04-13-ecb |
| lane-philip | chief-economist | neutral | 87% | forecast-2026-04-13-ecb |
| schnabel-isabel | executive-board | neutral | 88% | forecast-2026-04-13-ecb |

## Policy Cycle

- **Current cycle:** neutral
- **Previous decision:** hold
- **Chair stance:** hawkish

## Economic Indicators

| Indicator | Value | Date |
|-----------|-------|------|
| hicp | 2.5% | 2026-04-01 |
| unemployment | 6.1% | 2026-04-01 |
| deposit-rate | 2.00% | 2026-03-19 |
| gdp | 0.2% | 2026-03-07 |

*No strong indicator signal at this cutoff.*

## Equilibrium

| Outcome | Probability |
|---------|-------------|
| hold | 40% |
| hike-25 | 35% |
| hike-50 | 15% |
| cut-25 | 10% |
| cut-50 | 0% |

**Direction probabilities:** cut 10% / hold 40% / hike 50%

## Convergence Conditions

- **Chair stance:** hawkish
- **Equilibrium direction:** hike
- **Indicator direction:** none
- **Previous decision:** hold

## Summary Reasoning

The system evaluated 5 voting members in a policy cycle currently classified as **neutral**. The chair's stance is **hawkish**. The equilibrium produces a **hold** prediction at 40% confidence, without a strong indicator signal.

## Macro Backdrop

As of Apr 12, 2026, the ECB Governing Council faces the same stagflationary pressure as other central banks from the Iran war energy shock. Euro area HICP was 2.2% in March (flash) — still near target — but April data will first reflect the energy spike. The GC held at March 19 citing uncertainty. Since then, rhetoric has shifted hawkish: Lagarde warned of acting on 'even not-too-persistent' overshoot; Nagel called an April hike 'certainly an option'; Villeroy said the next move is 'highly likely upwards'; de Guindos framed April as 'hold-or-hike.' Schnabel is the notable brake ('no rush'). The debate is April vs June timing for a first hike, not direction. Stournaras and Centeno represent the dovish minority. Net: hold is the baseline for April with a meaningful hike tail, and June is priced as the more likely first-hike date if data continues deteriorating.

## Institutional Dynamic

*Context that the equilibrium math does not capture but should inform interpretation:*

Two personnel transitions are imminent: de Guindos departs June 1 (replaced by Vujcic as VP), and Knot has already been replaced by Sleijpen at DNB. Vujcic's hawkish stance means the VP seat shifts hawkish. The rotation system means not all 19 NCB governors vote at each meeting, which can shift the GC's effective center of gravity unpredictably. Lagarde's hawkish framing is notable — she typically signals consensus rather than leading opinion, suggesting the GC majority is genuinely open to hikes if data warrants.

## Key Uncertainty Flags

- **Outlook mode**: this is not a sealed prediction. The decision is more than two weeks away.
- Voting member rosters are hand-coded in `actors.edn` for this specific forecast. Any personnel changes not yet reflected are a coverage gap.
- **Thin actor coverage**: fewer than 6 voting members have current stance data.

## Market Consensus Snapshot (April 13, 2026)

*Data collected: April 13, 2026*

| Source | Hold | Hike | Cut | Notes |
|--------|------|------|-----|-------|
| [Polymarket](https://polymarket.com/event/ecb-interest-rates-april-2026) | 92.5% | 7.5% | <1% | $513K volume; hike contract has disproportionate volume ($181K) |

### Dodona vs Market

| Outcome | Dodona | Market | Divergence |
|---------|--------|--------|------------|
| Hold | **40%** | 92.5% | **Dodona much less confident in hold** |
| Hike | **50%** | 7.5% | **Dodona sees 7x the hike probability** |
| Cut | **10%** | <1% | Dodona sees a dovish tail |

**Largest divergence: hike probability.** Dodona assigns 50% to a hike vs market's 7.5%. Key new evidence: Villeroy (Apr 13) reports firms doubling planned price increases — the second-round effect that GC members identified as the trigger for tightening. Hormuz blockade (Apr 12) pushed Brent past $103, moving toward ECB's adverse scenario ($119 oil). March HICP flash 2.5% (up from 1.9%). Lagarde/Lane/Schnabel all speaking at IMF Spring Meetings this week — watch for pre-quiet-period signals.

## Methodology Reference

This outlook uses the methodology described in Casu, J. (2026), "Institutional Actor Modeling in Dodona: A Central Bank Rate Policy Case Study, 2024-2026."

Parameters are locked as of the hindcast paper submission. No adjustment has been made for this prediction.

The evidence used to generate this outlook is in the companion file `actors.edn` in this directory.

---

*Dodona is a symbolic cognitive reasoning system for institutional actor modeling. This note is a research output, not investment advice.*
