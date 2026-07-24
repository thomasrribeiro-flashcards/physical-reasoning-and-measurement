# Cold-start audit — Chapter 9: Building and testing models

Scope: all 18 scheduled cards in `flashcards/09_building_and_testing_models.md`.
Method: for each front, every domain-bearing term, symbol, representation, and
implied mechanism was recorded and resolved against the allowed inbound
frontier *before* the answer was read. Only scheduled cards establish
knowledge; headings, prose, tables, and figures outside card blocks do not.

## Allowed inbound frontier

- **Chapter 8 scheduled cards (full):** estimate vs guess, reference value,
  decomposition, powers-of-ten form (values ≥ 1, whole exponents), order of
  magnitude, bounds/brackets, bound propagation, decision robustness, honest
  reporting, stated assumptions, one-way audit (rejects, never confirms).
- **Chapters 1–7 capability summaries:** system, model, assumption,
  prediction, test (ch1); SI units, prefixes, quantity values with units
  (ch2); procedure, resolution, zero error, false precision (ch3); repeated
  readings, wobble, mean, uncertainty interval, ±, random vs systematic,
  agreement-depends-on-purpose (ch4); tables, axes, axis scales, trends,
  interpolation vs extrapolation, graphical artifacts, wobble vs drift (ch5);
  direct proportion, y = k × x, doubling/constant-ratio test, scale factor,
  steepness (ch6); derived units (cm/h, g/s, mL), unit cancellation,
  same-dimension addition, dimensional consistency, unit check rejects but
  never confirms, check-one-limit (ch7).
- **External closures:** arithmetic (benchmarks, rounded-value intervals,
  IPEE headings, means, division) and algebra (variable, coefficient,
  constant term, substitution, expression evaluation).
- **Assumed tools:** none.
- **Not inbound, verified absent from all fronts and answers:** "slope"
  (only "steepness" used), scientific notation / negative exponents, formal
  statistics, force/energy/velocity/momentum/field/wave/thermal-mechanism/
  circuit vocabulary, equation-solving beyond substitution and arithmetic
  inverse reasoning (09-15 phrases the 240 g question as "needs 200 g more
  at 5 g/s"; 09-12 evaluates, never solves).

## In-chapter establishment order

| New term / capability | Established (bridged on front) | Later uses |
|---|---|---|
| quantitative model (quantities + relationship) | 09-01 | all later cards |
| parameter meaning; unit forcing | 09-02 | 09-03..09-18 |
| model fingerprint in a table | 09-03 (bridged: "leaves a fingerprint") | 09-06, 09-15 |
| equation ↔ graph shape | 09-04 | 09-09, 09-11 |
| representation consistency | 09-05 | — |
| fitting (form assumed, numbers measured) | 09-06 (bridged: "means reading its numbers from measured data") | 09-11, 09-15..09-18 |
| prediction-vs-interval agreement; consistent ≠ proven | 09-07 | 09-14, 09-16..09-18 |
| mismatch fault localization; cheap checks first | 09-08 | 09-18 |
| model comparison on data | 09-09 | 09-14, 09-17 |
| difference pattern → targeted revision | 09-10 | 09-18 |
| regime of usefulness | 09-11 (bridged: "the range of conditions over which its predictions actually match measurement") | 09-12, 09-17, 09-18 |
| impossible-prediction (one-way) check | 09-12 | — |
| purpose fit | 09-13 | — |
| discriminating test | 09-14 (bridged: "design the measurement that would decide") | 09-18 EVALUATE |

## Front-by-front scan

- **09-01** (3a05b5b4): model, simplified stand-in, system, test → ch1;
  "verbal model" and "quantitative model" defined on the front itself;
  cm, hours → ch2. Resolved.
- **09-02** (af54c449): equation \(L = 20 - 2t\); constant term,
  coefficient → algebra closure; cm, h → ch2; steady shortening → plain.
  Answer's unit cancellation and same-dimension addition → ch7. Resolved.
- **09-03** (badf3659): model from 09-02; data table, hourly differences →
  ch5; "fingerprint" bridged in-sentence; wobble vs drift (answer) → ch4/ch5.
  Resolved.
- **09-04** (71c60dad): model from 09-02; graphs, identical axes → ch5;
  figure shows unlabeled candidate shapes only (no answer leak). Resolved.
- **09-05** (1a087b72): table equal steps → ch5/09-03; curved graph, axis
  scales, artifact → ch5. Resolved.
- **09-06** (34f87020): "fitting" bridged on front before use; table → ch5;
  steady-shortening form → 09-02/09-03; assumed vs measured → ch8 stated
  assumptions; mean (answer) → ch4. Resolved.
- **09-07** (f8032131): model from 09-02; substitution → algebra;
  \(\pm\) interval → ch4; "on trial" plain; unit-check analogy (answer) →
  ch7. Resolved.
- **09-08** (1d7ef124): prediction, uncertainty interval, no overlap → ch4;
  zero error (answer) → ch3. Resolved.
- **09-09** (1e16e83d): proportional through the origin → ch6; ±0.2 cm →
  ch4; model forms → 09-02; figure shows data plus both candidate lines
  (the judgment is the retrieval act; no leak). Doubling test (answer) →
  ch6. Resolved.
- **09-10** (def2af1a): assumptions ("starts empty", steady flow) → ch1/ch8;
  mL, min → ch2/ch7; differences and their pattern → ch5/09-03; "revise"
  bridged by the front's own task statement. Resolved.
- **09-11** (3575c64b): "regime of usefulness" bridged on front before use;
  fitted → 09-06; figure shows data and line (reading the departure is the
  target; regime endpoints not printed). Extrapolation (answer) → ch5.
  Resolved.
- **09-12** (f5b4089e): model from 09-02; substitution → algebra; regime →
  09-11; one-way rejection logic → ch7/ch8. Resolved.
- **09-13** (2477b1b5): wobble ±0.2 cm/h → ch4/ch7; purpose-based adequacy →
  ch4 agreement-depends-on-purpose, extended to models here. Resolved.
- **09-14** (ad20181b): two model forms → 09-02/09-09; ±20 mL intervals →
  ch4; agreement testing → 09-07; "design the measurement that would
  decide" bridges the discriminating-test idea on the front. Resolved.
- **09-15** (28d0d38c, P/S): balance reading, g, s → ch2/ch3/ch7; table →
  ch5; model building and fitting → 09-01..09-06; prediction phrased as
  "needs 200 g more at 5 g/s" (no equation solving); IPEE headings →
  arithmetic closure. Resolved.
- **09-16** (de34771e, P/S): fitted model → 09-06; test against ± interval →
  09-07; substitution → algebra. Resolved.
- **09-17** (fa67e13b, P/S): candidate models → 09-09; constant-ratio test →
  ch6; interpolation inside tested range → ch5/09-11. Resolved.
- **09-18** (bbd9cfcd, P/S): fitted model and refit → 09-06; difference
  pattern → 09-10; regime → 09-11; audit's one-way logic → ch8; zero error →
  ch3; discriminating follow-up test → 09-14. Resolved.

## Result

Every front dependency maps to confirmed inbound knowledge or an earlier
scheduled establishment point in this chapter; every new term is bridged on
the front of its establishing card before any reuse.

cold_start_status: pass
unresolved_dependencies: 0
