# Dodona Outlook: FOMC April 2026

**Note generated:** 2026-04-13
**Decision date:** 2026-04-29
**16 days before decision — OUTLOOK (not for publication)**

---

## Summary

**Predicted direction:** hold

**Direction confidence:** 61% [49%, 70%]

*This is an outlook, not a sealed forecast. The decision is more than two weeks away; material new evidence may arrive before the seal date.*

## Actor Stance Snapshot

Cutoff: 2026-04-29. All evidence below predates this date. Strict temporal holdout enforced at the data layer.

| Actor | Role | Stance | Confidence | Basis |
|-------|------|--------|-----------|-------|
| barr-michael | governor | neutral | 43% | forecast-2026-04-13-fomc |
| bowman-michelle | vice-chair-supervision | dovish | 59% | forecast-2026-04-13-fomc |
| cook-lisa | governor | hawkish | 50% | forecast-2026-04-13-fomc |
| hammack-beth | president-cleveland | hawkish | 43% | forecast-2026-04-13-fomc |
| jefferson-philip | vice-chair | neutral | 77% | forecast-2026-04-13-fomc |
| kashkari-neel | president-minneapolis | hawkish | 43% | forecast-2026-04-13-fomc |
| logan-lorie | president-dallas | hawkish | 43% | forecast-2026-04-13-fomc |
| miran-stephen | governor | dovish | 43% | forecast-2026-04-13-fomc |
| paulson-anna | president-philadelphia | hawkish | 43% | forecast-2026-04-13-fomc |
| powell-jerome | chair | neutral | 88% | forecast-2026-04-13-fomc |
| waller-christopher | governor | neutral | 89% | forecast-2026-04-13-fomc |
| williams-john | president-ny | neutral | 77% | forecast-2026-04-13-fomc |

## Policy Cycle

- **Current cycle:** neutral
- **Previous decision:** hold
- **Chair stance:** neutral

## Economic Indicators

| Indicator | Value | Date |
|-----------|-------|------|
| cpi | 3.3% | 2026-04-10 |
| unemployment | 4.3% | 2026-04-03 |
| core-pce | 3.0% | 2026-03-28 |
| pce | 3.0% | 2026-03-28 |
| fedfunds | 3.625% | 2026-03-18 |
| gdp | 0.5% | 2026-04-09 |

**Indicator signal:** hike at strength 0.4

## Equilibrium

| Outcome | Probability |
|---------|-------------|
| hold | 61% |
| hike-25 | 16% |
| hike-50 | 11% |
| cut-25 | 9% |
| cut-50 | 4% |

**Direction probabilities:** cut 12% / hold 61% / hike 27%

## Convergence Conditions

- **Chair stance:** neutral
- **Equilibrium direction:** hold
- **Indicator direction:** hike
- **Previous decision:** hold

## Summary Reasoning

The system evaluated 12 voting members in a policy cycle currently classified as **neutral**. The chair's stance is **neutral**. The equilibrium produces a **hold** prediction at 61% confidence, supported by a hike indicator signal at strength 0.4.

## Macro Backdrop

As of Apr 10, 2026, the FOMC faces a stagflationary shock: the US-Iran war (began late Feb 2026, ceasefire rejected as of Apr 6) pushed gasoline above $4/gal and drove March headline CPI to +0.9% m/m (largest since 2022), 3.3% y/y. Core PCE held at 3.0% y/y in Feb, still 100bp above target after five years of overshoot. The labor market is 'low hire, low fire' — unemployment drifted down to 4.3% in March on a bounceback print, but Feb was a payroll decline and committee members describe balance as 'precarious.' Tariffs remain a second-order inflation driver. Political pressure on Fed independence is intense: Trump has signaled Kevin Warsh will replace Powell (term ends May 2026) and likely swap into Miran's expired-but-unfilled Board seat. The dot plot still projects one 2026 cut but the committee is explicitly in wait-and-see mode; market-implied odds for an Apr 29-30 cut collapsed after the Iran shock. Bottom line: hold is the overwhelming baseline, with Miran dissenting dovishly and Hammack floating a hawkish hike option.

## Institutional Dynamic

*Context that the equilibrium math does not capture but should inform interpretation:*

April 29-30 is Powell's second-to-last FOMC meeting (term ends May 2026; June is his final). Trump has signaled Kevin Warsh as replacement. To the extent Powell's neutrality reflects institutional resistance to political pressure rather than purely data-driven hold conviction, this meeting carries an asymmetric incentive for him to anchor the hold one more time before stepping down. The model treats Powell's stance as a single signal regardless of motivation, but the interpretation matters: if his successor (Warsh, dovish-leaning under Trump's stated preference) takes the chair in June, board doves Miran and Bowman gain a like-minded chair, and the post-Powell pivot to cuts could come fast. The April outlook is therefore best read as 'Powell's last hold,' with the dovish pivot expected in June or July rather than now. This institutional context is not captured in the equilibrium math itself.

## Key Uncertainty Flags

- **Outlook mode**: this is not a sealed prediction. The decision is more than two weeks away.
- Voting member rosters are hand-coded in `actors.edn` for this specific forecast. Any personnel changes not yet reflected are a coverage gap.

## Market Consensus Snapshot (April 13, 2026)

*Data collected: April 13, 2026*

| Source | Hold | Hike | Cut | Notes |
|--------|------|------|-----|-------|
| [Polymarket](https://polymarket.com/event/fed-decision-in-april) | 98% | 1% | 1% | $79.8M volume |
| CME FedWatch | ~98% | ~2% | ~0% | Futures-implied |
| Kalshi (KXFEDDECISION-26APR) | ~97% | ~2% | ~1% | Three large hike-25 buys at $0.01 (100:1 payout) noted Apr 10; no additional large buys reported since |

### Dodona vs Market

| Outcome | Dodona | Market | Divergence |
|---------|--------|--------|------------|
| Hold | **61%** | 97-98% | **Dodona much less confident in hold** |
| Hike | **27%** | 1-2% | **Dodona sees 14-27x the hike probability** |
| Cut | **12%** | 0-1% | Dodona sees a dovish tail |

**Largest divergence: hike probability.** Dodona assigns 27% to a hike vs markets' ~1-2%. Key new evidence this cycle: Miran (Apr 13) argues inflation expectations are anchored and the commodity shock should be "looked through" — reinforcing the dovish case. But four hawkish regional presidents + Hammack's explicit hike-floating + March CPI +0.9% m/m maintain Dodona's hike tail.

## Methodology Reference

This outlook uses the methodology described in Casu, J. (2026), "Institutional Actor Modeling in Dodona: A Central Bank Rate Policy Case Study, 2024-2026."

Parameters are locked as of the hindcast paper submission. No adjustment has been made for this prediction.

The evidence used to generate this outlook is in the companion file `actors.edn` in this directory.

---

*Dodona is a symbolic cognitive reasoning system for institutional actor modeling. This note is a research output, not investment advice.*
