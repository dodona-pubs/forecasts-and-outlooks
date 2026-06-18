# Dodona — June 2026 Central-Bank Campaign Post-Mortem

**Published:** 2026-06-18 · **Scope:** the four marquee decisions of the June 2026 live campaign —
ECB (Jun 11), BoJ (Jun 16), FOMC (Jun 17), BoE (Jun 18). All forecasts were **sealed before the
decision** (strict temporal holdout) and are scored here against the realized outcomes.

> This is an honest post-mortem, not a results announcement. The headline number (2 of 4 correct on
> direction) is the *least* important thing in it. What matters is **why** — and the why is the same
> across all four.

---

## 1. Scoreboard

| Decision | Sealed forecast | Outcome | Result |
|----------|-----------------|---------|--------|
| **ECB** 2026-06-11 | HOLD ~76% | **HIKE** +25bp → 2.25% | ❌ miss |
| **BoJ** 2026-06-16 | HOLD 63.2% | **HIKE** +25bp → 1.00% (7–1) | ❌ miss |
| **FOMC** 2026-06-17 | HOLD 48.3% | **HOLD** 3.50–3.75% (19–0, hawkish dots) | ✅ hit |
| **BoE** 2026-06-18 | HOLD 70.0% | **HOLD** 3.75% (7–2, 2 hawk dissents) | ✅ hit |

**2 hits / 2 misses on direction.** But the engine **leaned HOLD on all four** — realized
macro data was benign at every bank (inflation cooling or below target). It never forecast a hike at
any of them. So the record is not "the model called two right and two wrong." It is: **the model made
one call — *hold* — four times, and the world agreed twice.**

---

## 2. The single root cause: one shock, seen by no one here

Every one of the four decisions turned on the **same** driver — the Middle East / Iran-war **energy
shock** and its pass-through to *future* inflation — and the engine consumed **none** of it. The only
thing that varied was **timing**:

- The shock was **peaking** around the ECB and BoJ meetings (oil elevated, war ongoing) → both banks
  made **forward, risk-management hikes** on *projected* inflation while *realized* inflation was
  benign (ECB on a 3% year-ahead forecast; BoJ at 1.4% core CPI, below target, citing yen at 160 and
  crude spillover). The engine, reading realized CPI + committee tone, was "data-correct" to say HOLD
  — and **missed both**.
- The shock was **receding** by the FOMC and BoE meetings — a Middle East peace deal was announced in
  the days before, Brent fell from a ~$100 average toward ~$79 (per the BoE minutes) — so both banks
  **held**. The engine **hit both**.

**Name the gap plainly: we captured *realized* inflation and never captured *forward* inflation** —
even though every one of these banks *told us*, in its own published materials, that forward inflation
was the thing it was acting on: the ECB's **3% year-ahead forecast**, the FOMC's **dot-plot and rising
SEP projections**, Ueda's **"upward deviation in underlying inflation,"** and the BoE minutes' own
**"CPI… is expected to rise later this year."** None of that was hidden or exotic. It was standard,
published central-bank forward data — the single most important input to a rate decision — and it was
simply **not in our forecast**. We read where inflation *had been* and never read where the
decision-makers *said it was going*.

The conclusion is uncomfortable and precise:

> **The engine's accuracy was set by a signal it does not read.** It leaned hold throughout; it was
> right exactly when the (unseen) forward signal also pointed to hold, and wrong exactly when it
> pointed to a hike. Its 2–2 is not a measure of the committee-vote model — that model was fine — it
> is a measure of which way an input the engine *chose not to acquire* happened to point.

This is the **historical-vs-forward** gap, live and four-for-four: central banks set policy on
*projected* inflation; an engine that reads only the *realized* past can say where an actor has been,
not where it is about to go.

---

## 3. Per-decision detail

**ECB — miss (HOLD ~76% → HIKE).** A widely-expected, market-priced "insurance hike" against the
Iran-war energy shock, on a 3% year-ahead inflation forecast, while realized employment/wages/lending
did not support a hike. The same-day "fresh-stance" re-run made us *more* confident-wrong (71%→76%) —
a reminder that refreshing a backward-looking input cannot fix a forward-looking blind spot.

**BoJ — miss (HOLD 63.2% → HIKE 7–1).** Hiked to the highest rate since 1995 on yen-at-160 + crude
spillover into *future* underlying inflation; Governor Ueda had **telegraphed it in a June speech** the
frozen stance classifier never saw (#52). Mechanically, the committee model read **7 of 10 members as
neutral; they voted 7–1 to hike** — the stance reads were stale/wrong. Worst of the four: direction
*and* committee structure both missed.

**FOMC — hit, but by alignment, not by sight (HOLD 48.3% → HOLD 19–0).** A genuine *hawkish hold*: the
dot-plot lurched hawkish (median now projecting hikes) as inflation rose to 3.6%/3.3% on energy. Two
honest notes: (a) **calibration win** — the near-coin-flip 48.3% hold / 42% hike captured the real
two-sidedness; the fat tail was *appropriate*, not noise; (b) **the hold's likely driver was
political** — Trump publicly pressured against a hike ("I'm living with Kevin… shouldn't be penalized
by raising rates"), and the Fed held. That is the reverse-Stackelberg case the engine has a *detector*
for but leaves unwired. We were right because the committee math and the (unseen) political pressure
happened to point the same way.

**BoE — the clean hit (HOLD 70.0% → HOLD 7–2).** Right *by sight*: held on realized data the engine
reads (CPI cooling to 2.8%, labour market loosening) with the forward energy risk already receding.
And the **committee-structure read was essentially correct** — the engine modeled **2 hawks of 9** with
**21.2% hike mass**; the MPC voted **7–2 with exactly those 2 dissenting for a hike** (21.2% ≈ 2/9 =
22.2%). The one decision in four where the engine succeeded on its own terms, structure and all.

---

## 4. What this maps to (root causes → known gaps)

Every failure traces to acquisition/coverage, not to the committee-vote reasoning:

1. **We never captured forward inflation — a basic, published input we left on the table.** The
   engine read *realized* CPI only; the banks' own inflation **projections** (SEP/dot-plot, ECB staff
   forecast, each bank's "inflation expected to rise" guidance) were never a live input. The
   projection layer that would carry them is *built but shadow* (§5.8); the geopolitical/energy channel
   that drives them is *ingested but orphaned* (§1.1); policy intent is *flattened to tone*. This is
   not a subtle coverage gap — it is the most important single input to a rate decision, and we did
   not acquire it.
2. **The stance derive-step was frozen** at the 2026-06-09 snapshot for the whole campaign (#52), so
   the engine could not even see fresh communications — e.g. Ueda's June hike signal.
3. **The political axis is unmodelled.** The FOMC decision turned on executive pressure the engine
   neither detects (reverse-Stackelberg classifier dark, §5.6.1) nor *forecasts*.
4. **T-7 sealing is fragile in volatile conditions.** A 7-day-out seal commits before a fast-moving
   geopolitical/political situation resolves; with a mercurial administration the load-bearing input
   can swing inside the window, and the seal published falsely-precise numbers against a moving target.

---

## 5. What this changes — inputs to the post-campaign design review

These are not patches; they are the agenda for the architecture re-work (FE arch §0.4):

- **Pair every forecast with a forward view** (§0.4 historical+forward): wire the projection layer
  live, add a market-implied forward path (OIS/breakevens/FX-forward — distinct from prediction-market
  *outcome* prices), a geopolitical/energy-forward consumer, and policy-intent (not tone) extraction.
- **Forecast the political actor-set as a co-equal axis** (§0.4, new): model the
  President/administration as actors, *project* their posture to the decision moment, and couple it via
  the policy-commitment channel. **Mercurial actors must widen the published bounds**, and the seal/
  drift mechanism (§6.2) needs a **political-volatility re-forecast trigger** — a hold contingent on a
  volatile political input is not a tight 70%.
- **Wire the reverse-Stackelberg detector** (§5.6.1) — its canonical case (Trump→Warsh) shaped a
  marquee decision while it sat dark.
- **Close the cadence/coverage gaps**: re-run stance derivation in-cadence (#52); the consumer-coupled
  acquisition contract with a freshness gate (#50); UTC decision-instants in the calendar (§2.2).

---

## 6. Honesty coda

This was a **real failure, and the cause was basic**: we did not capture the forward-looking data —
above all **forward inflation** — that these banks publish and act on. That is an acquisition miss, not
bad luck; and a 91.4% hindcast could not warn us *because the hindcast scores the same realized-only
inputs*. The committee-vote reasoning was sound — on BoE it reproduced the 7–2 split from modelled
structure — but **a sound reasoner on a one-sided input set is wrong live, and being well-calibrated on
the two we got right does not offset missing the two we got wrong.** The fix is not a better committee
model; it is to give the engine the *forward* and *political* halves of the picture the actors
themselves act on. That is the work, and this campaign is its mandate.

*Forecasts sealed pre-decision; outcomes from official sources (incl. the BoE June MPC minutes). No
forecast was revised after the fact; the daily outlook docs and their seals remain in this directory,
scored as-is.*
