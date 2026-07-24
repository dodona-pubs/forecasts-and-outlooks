# Shadow-Week Prognostics — the day-to-day collation

The running ledger of every frozen call and daily read across the four July decisions —
the convergence-history record the sealed notes reference. One dated section per day;
rows are append-only (corrections annotate, never rewrite). Forecast ops execute at
development boundaries only; each day's row is written at the day's batch point.

Scoreboard: **ECB ✓ (1/1)** · FOMC 07-29 pending · BoE 07-30 pending · BoJ 07-31 pending.

---

## 2026-07-22 (Wed)

- **ecb-2026-07-23 SEALED at T-1** (cutoff 19:00Z): modal **HOLD** @ DFR 2.25, margin
  0.418, hike-25 tail 26.8% (SMA-corroborated). Note sealed to GitHub by the user
  (timestamp witness). Artifact: `results/shadow/ecb-2026-07-23.ddn`.

## 2026-07-23 (Thu)

- **ecb-2026-07-23 SCORED: CORRECT** — held at 2.25 "after some officials considered
  hike"; the 26.8% tail was a live minority position (the wire confirmed the
  distribution's shape, not just its mode). Scorer's hold-vocabulary bug caught by this
  first live grading; fixed same morning (`acd012f`).
- **Early production-grade seals** (the horizon-firewall rehearsal — frozen ~21:30Z,
  before any decision-week wire wave; artifacts in `results/shadow-early/`):
  - fomc-2026-07-29 @ T-6: **HOLD @ 3.75 — DEGENERATE (hold = 1.0 flat)**. Recorded
    as-sealed; the collapsed-route class flagged as an open lead — Monday's T-1 pair on
    the same decision tests whether the collapse is horizon-dependent.
  - boe-2026-07-30 @ T-7: **HOLD @ 3.75**, margin 0.426 (hold 0.634 / cut-25 0.145 /
    hike-25 0.091).
  - boj-2026-07-31 @ T-8: **HOLD @ 0.841**, margin 0.359 (hold 0.602 / hike-25 0.193 /
    cut-25 0.079 — the hike tail persisting from June, honestly).
- Wire-consensus monitor: at seal time the FOMC/BoE/BoJ decision-week waves have not
  formed (the firewall working as stated); the June proving run showed the reader fires
  correctly when waves exist (11-0 / 26-0 on the June hikes). First monitor reads land
  with tomorrow's batch.
- Development context: §13 projection license measured-neutral (shelf); §14 velocity
  refused at design; §15 consensus reader BUILT and June-measured — detection VALIDATED
  (unanimous fires, zero false fires, base floor byte-proven), consumption at the frozen
  ×3 REFUTED (0.84-class holds don't move); license-2 (unanimity-decisive mass-swap)
  pre-registered, implementation next.

## Upcoming

- Mon 07-28: FOMC T-1 freeze (at-job 2) → the first two-horizon pair with the T-6 seal.
- Wed 07-29 ~11:30 PDT: score FOMC (both horizons). Thu: BoE T-1 → score. Fri: BoJ T-1 →
  score.
- ~Aug-1: the four-decision post-mortem (per-decision mechanism attribution WITH the
  horizon axis).
