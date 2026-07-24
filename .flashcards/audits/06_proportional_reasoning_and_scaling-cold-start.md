# Cold-start audit — Chapter 6: Proportional reasoning and scaling

Isolated fresh-agent build, 2026-07-24. Sixteen scheduled cards
(12 `Q:/A:`, 1 `C:`, 3 `P:/S:`), three front figures.

## Chapter-boundary dependency ledger

Inbound knowledge allowed at the Chapter 6 boundary, exactly as resolved in
`.flashcards/prerequisites/graph.json` (no proposed edges beyond it; none
needed, so `unresolved` list is empty):

- **Local chapter 5 (direct prerequisite, full cards)**: tables with
  unit-bearing headers; independent versus dependent quantity; successive
  differences; two-axis graphs, axes, data points; steady rise / equal steps
  wording; trend versus scatter; trend line; anomalous points; interpolation
  and extrapolation with "about"; axis-start artifacts; the coin-mass table
  (2→11, 4→21, 6→32, 8→41, 10→52 g) and the water-depth table (100→2.1,
  200→3.9, 300→6.1, 400→8.0 cm), including the ch5 midway reading "about
  5 cm" between 200 and 300 mL.
- **Local chapters 1–4 (validator capability summaries)**: quantity, value,
  measurement, measurand, model; SI units, symbols, conversion; procedure,
  scale division, resolution, false precision; repeat variation, mean,
  wobble/scatter language, uncertainty, mistake-versus-variation,
  random/systematic error, bounded conclusions.
- **External `mathematics/quantitative-reasoning-and-arithmetic`**
  (capability summaries; chapter 10 fully staged): whole-number and decimal
  arithmetic; fractions such as \(\frac{1}{20}\) and one half; ratio, rate,
  and proportional-relationship *names* with their arithmetic; division as
  sharing; number lines; m/cm/mm/g/kg/L/mL/s units and conversion; rounding
  and reasonableness checks.
- **External `mathematics/elementary-algebra-and-functions` ch01
  (capability summary)**: variable, equation, substitution, coefficient,
  evaluating an expression.
- **Assumed tools**: none.

Frontier rules enforced while drafting: "slope" never used (ch5 taught
"steepness" only); symbolic per-unit notation (mL/s) reserved for Chapter 7 —
all per-unit values are spelled out ("g per coin", "mL per second");
"origin" is not inbound and is bridged on the front of 06-05 before use;
no motion/force/energy vocabulary; no area or geometry formulas; scheduled
blocks only establish prerequisites — headings and prose establish nothing.

## Front-by-front audit

Every domain-bearing term, symbol, representation, and premise on each front
(including figure alt text and labels) is classified as **inbound** (I),
**established earlier in this chapter by a scheduled block** (E-nn), or
**self-bridged on this front** (B).

| # | Card | Front dependencies and classification |
|---|---|---|
| 1 | 06-01 direct proportion | coin table rows, steady rise, trend line, zero-at-zero trend (I ch5); doubling/factor language, multiplication (I arith); "directly proportional" (B: defined on this front before the task); repeat-variation tolerance implied in "bear out" (I ch4) |
| 2 | 06-02 constant of proportionality | doubling test (E-01); division, ratio (I arith); per-unit phrase "g per coin" spelled out (I arith rate name + units); "constant of proportionality" (B: defined on this front); coin table rows (I ch5); wobble (I ch4) |
| 3 | 06-03 proportion equation | variable, equation, substitution (I algebra summary); constant of proportionality 5.2 g per coin (E-02); letters \(n, m\) introduced on the front (B) |
| 4 | 06-04 cloze \(y=kx\) | dependent/independent quantity (I ch5); constant of proportionality (E-02); equation form (E-03); the deleted span is the whole equation, so the visible text leaks nothing (C4) |
| 5 | 06-05 graph signature | axes, trend line, rising graph (I ch5); "origin" (B: defined on the front as the corner where both read zero); direct proportion (E-01); figure labels A/B/C and corner "0" only (V4: no answer leak) |
| 6 | 06-06 jar nonproportional | balance, readings, grams (I ch3/arith); equal steps / steady climb (I ch5); proportionality test (E-01, E-02); "nonzero start" named in the answer, not required on the front |
| 7 | 06-07 scale factor | direct proportion (E-01); water-depth row (I ch5); "scale factor" (B: defined on the front as any-factor generalization of E-01's doubling); decimals ×1.25 (I arith) |
| 8 | 06-08 door drawing | scale factor (E-07); "to scale" (B: defined on the front); cm, dimension reading (I ch3/arith); figure labels 200 cm/80 cm/10 cm/? plus not-to-scale note (V4: the "?" hides the answer; artwork deliberately not to scale so the factor cannot be read off the art) |
| 9 | 06-09 ratio invariance | scale drawing, one shared factor (E-08); ratio and equivalent ratios (I arith); doubling one dimension (I arith); the door's numbers (E-08) |
| 10 | 06-10 inverse proportion | division as equal sharing, products (I arith); cm ribbon (I arith units); "inversely proportional" (B: defined on the front); trade-off framing uses only inbound growth/decrease language (I ch5) |
| 11 | 06-11 constant-product test | inverse proportion and fixed product (E-10); mL, seconds (I arith units); "mL per second" spelled out (I arith rate name); steady rate wording (I ch5 "steady") |
| 12 | 06-12 falling graphs | falling trend, marked points, labeled values (I ch5); inverse proportion and product test (E-10, E-11); figure labels: axis marks 1–4 and point values 60/45/15 and 60/30/15 (V4: values are the working material, not the verdict) |
| 13 | 06-13 wobble versus drift | ratio test (E-02); repeat variation, scatter versus trend/direction (I ch4, ch5); grams per coin (E-02) |
| 14 | 06-14 analyzed IPEE, paper stack | markdown table, mm (I ch5, arith); proportionality decision + prediction (E-01..E-03, E-07); wobble judgment (E-13); IPEE headings (I arith problem cards) |
| 15 | 06-15 faded IPEE, photo | scaled enlargement, shared factor (E-07, E-08); cm (I); internal-ratio check appears only in S (E-09) |
| 16 | 06-16 independent mixed IPEE | direct test (E-01, E-02), nonzero-start diagnosis (E-06), inverse product test (E-10, E-11), claim repair (E-06, E-13); scoops/books/stickers contexts use only inbound units and sharing (I arith) |

Establishment order is strictly linear: 01 → 02 → 03 → 04 → 05 → 06 (direct
strand), 07 → 08 → 09 (scaling strand, built on 01/02), 10 → 11 → 12
(inverse strand), 13 (data-test strand, built on 02 and inbound ch4), then
problems 14–16 use only earlier-established chapter concepts. No front uses
a term before its explain → supported retrieval → application sequence
begins, and no future-facing example imports Chapter 7+ vocabulary.

## Figure audit

- `rising-graph-shapes` (06-05 front): discrimination target; labels A/B/C
  and "0" only; redundant non-color cue is line shape/position; title/desc
  present in the SVG; inspected rendered output — no clipping or overlap.
- `scaled-door-drawing` (06-08 front): the unknown width is a "?"; artwork
  intentionally not to scale (noted in the figure) so measuring the art
  cannot leak the factor; label overlap found on first render and fixed
  (caption moved down, note moved above the door); re-rendered and
  re-inspected — clean.
- `falling-graph-shapes` (06-12 front): labeled values are the premises the
  product test consumes; the verdict (which panel) is not marked; inspected
  rendered output — clean.
- Double-number-line figure: intentionally omitted (covered by the inbound
  arithmetic conversion-map grammar; no distinct scheduling decision).

## Verdict

All sixteen fronts resolve every dependency to inbound knowledge, an earlier
scheduled establishment point, or an explicit on-front bridge. No prerequisite
edge beyond the sandbox-resolved closure was needed or proposed.

cold_start_status: pass
unresolved_dependencies: 0
