# Cold-start audit — Chapter 2: SI units and quantity values

Date: 2026-07-24. Mode: build (chapter intentionally blanked; designed from scratch).
Scope: `flashcards/02_si_units_and_quantity_values.md` (17 scheduled blocks: 12 Q/A, 2 C, 3 P/S)
and its one figure `figures/02_si_units_and_quantity_values/prefix-ladder.svg`.

Procedure: simulated a first-time learner reading fronts in file order. For each front,
every domain-bearing term, symbol, representation, and implied mechanism was recorded and
mapped to a confirmed source **before** the answer/solution body was inspected. Only
scheduled blocks (Q/A, C, P/S) count as establishment points; section headings, prose
outside blocks, and figure captions satisfy nothing.

## Allowed inbound frontier (chapter boundary)

Per the machine-resolved prerequisite graph (edge mode: explicit):

| Source | Access | Knowledge admitted |
|---|---|---|
| Local ch. 1 `01_systems_quantities_and_models` | full card bodies | system, boundary, surroundings, property vs physical quantity, quantity value, "40 cm and 0.40 m report the same quantity" (card `41b502e9`), measurement, instrument, measurand, observation vs measurement, model/assumption/prediction/test, schematic conventions, one prior IPEE problem |
| `mathematics/quantitative-reasoning-and-arithmetic#10_measurement_estimation_and_decisions` | full card bodies (exact declared provider: measurement-unit, unit-conversion) | measuring by repeated copies of a unit; agreed units; meter (m); centi- = one hundredth, cm; kilo- = one thousand, km; gram, kilogram, 1 kg = 1000 g; liter (L), milli- = one thousandth, mL; 1 min = 60 s, 1 h = 60 min with symbols s/min/h; scale reading and precision; conversion direction (to smaller unit multiply, to larger unit divide); "a number needs a unit"; personal benchmarks; the word "prefixes" (card `c5515974`); IPEE headings |
| `mathematics/quantitative-reasoning-and-arithmetic` chs. 1–9 | declared capabilities only | whole-number and decimal arithmetic (all four operations), place value, decimal fractions (tenths through millionths as decimals), rounding, ratio/rate, percent, signed numbers, whole-number powers |
| `mathematics/elementary-algebra-and-functions#01_variables_and_expressions` | declared capabilities only | variable, algebraic expression, equation, term, coefficient, substitution, expression evaluation, verbal translation |
| Assumed tools | — | none |

Not admitted (and not used): negative exponents, scientific notation, order-of-magnitude
language, the four remaining SI base units beyond a bounded "exist, met later" clause,
any later chapter of this deck.

## Front-by-front audit

Numbering follows file order. "Est. N" = established by scheduled block N of this chapter.

1. **`5a1c2f76` Q (SI, base unit)** — agreed unit (arith ch10); meter/m, cm, km (arith ch10);
   kilogram, second (arith ch10). Seven as a whole number is inbound. New terms *SI* and *base unit* are defined on this front
   itself before being asked about. The answer's word "prefix" is inbound (arith ch10
   `c5515974`) and is re-glossed inline ("a fixed fraction or multiple"). No unexplained term.
2. **`3f7e9b24` Q (unit symbols; plural/period diagnosis)** — symbols m, kg, s, cm, km
   (arith ch10); *unit symbol* defined on this front; "abbreviation" is ordinary language.
   The flawed sign "12 kms." is the diagnostic target, not assumed knowledge.
3. **`8c4d1e57` Q (quantity symbol vs unit symbol)** — variable (algebra ch1 capability);
   physical quantity, duration/height as quantities (ch1); unit symbol (Est. 2); the
   notation \(t = 30\text{ s}\) is decoded on the front itself.
4. **`6b2a8f93` Q (value = number × unit; spacing)** — quantity value (ch1); measuring by
   repeated unit (arith ch10); multiplication and decimal 2.5 (arith capabilities). The
   product reading is taught on this front; the question retrieves it immediately.
5. **`9d5f3a68` Q (conversion = substitution of equals)** — 40 cm = 0.40 m (ch1 `41b502e9`);
   number × unit (Est. 4); substitution (algebra ch1 capability); centi- = one hundredth
   (arith ch10) and the relation 1 cm = 0.01 m is additionally supplied on the front;
   decimal multiplication (arith).
6. **`2e8b6c41` Q (prefix defined; build mm)** — centi-, kilo-, milli-, mL (all arith ch10);
   the formal term *prefix* and symbol-concatenation rule are taught on this front;
   thousandth as decimal (arith). Retrieval target (mm) is constructed, not presumed.
7. **`7f1c5d29` Q (micro-, mega-)** — prefix (Est. 6); both new factors are stated on the
   front as decimals/whole numbers (0.000001; 1 000 000 — arith capability); µm hair
   benchmark supplied; mm (Est. 6). Comparison uses only supplied factors.
8. **`4a9e7b35` C (micrometer cloze)** — micro-/µm and the hair benchmark (Est. 7).
   Deletion `[millionth]` retrieves the factor established one block earlier. C-after-meaning
   rule satisfied.
9. **`1d6c4f82` C (megagram cloze)** — mega-/M (Est. 7); gram (arith ch10); car-mass
   benchmark is supplied by the sentence itself. Deletion `[million]` retrieves Est. 7.
10. **`5e3a9d17` Q (case sensitivity: mg vs Mg)** — milli- (arith ch10, Est. 6), mega-
    (Est. 7), gram (arith ch10); prefix-symbol concatenation (Est. 6). Case-sensitivity
    rule is taught on this front; the question asks for its consequence. 5000 kg follows
    from 1 kg = 1000 g (arith ch10).
11. **`0b8f2c64` Q (kilogram anomaly; no stacking)** — kilogram = kilo + gram (arith ch10);
    1 kg = 1000 g (arith ch10); milli- (Est. 6). The no-stacking rule is taught on this
    front. Answer's µg uses micro- (Est. 7).
12. **`6f4b8e21` Q (choose a readable prefix)** — mm and its factor (Est. 6); cm
    (arith ch10); decimal 0.004 (arith). The 0.1–1000 readability convention is stated on
    the front; the task is application.
13. **`3c7d5a94` Q + figure (cm → km along the ladder)** — figure alt text names only
    mm/cm/m/km and their pairwise relations, all inbound (arith ch10) or Est. 6; conversion
    direction to-larger-divides (arith ch10); composing two factors by multiplication
    (arith). Figure carries no answer text for the asked question (the overall factor
    100 000 must be composed, not read off). Alt text does not leak the composed factor.
14. **`8a2f6d48` P/S (2.4 km → cm, full IPEE)** — IPEE format (arith ch10 + ch1);
    1 km = 1000 m, 1 m = 100 cm (arith ch10); to-smaller-multiplies (arith ch10);
    substitution view (Est. 5). S begins at **IDENTIFY**; direct result is the first
    sentence of EXECUTE. No prelude.
15. **`9e6b3f75` P/S (52 000 cm → km, faded)** — same relations, opposite direction
    (arith ch10); worked analogue Est. 14. Retained headings only (**EXECUTE**,
    **EVALUATE**); S begins at first retained heading; result first in EXECUTE.
16. **`2d9c7e53` Q (min/h are not prefixed units)** — 1 min = 60 s, 1 h = 60 min and
    symbols (arith ch10); prefix-as-tens-multiplier (Est. 6); the flawed ×100 reasoning is
    the diagnostic target. Answer arithmetic 2.5 × 60 (arith).
17. **`7b5e9a26` P/S (notation audit)** — spacing rule (Est. 4); no-plural/no-period
    (Est. 2); case sensitivity (Est. 10); mm (Est. 6), g/kg (arith ch10); benchmark
    sanity checks (arith ch10; fingernail/paper-clip/textbook comparisons supplied in
    text); Mm absurdity check uses mega- (Est. 7). S begins at **IDENTIFY**; corrected
    label is the first sentence of EXECUTE.

## First-use scan (new terms, symbols, representations, procedures)

| Item | First explanation | Supported retrieval | Later application |
|---|---|---|---|
| SI (International System of Units) | 1 (front) | 1 | 2, 17 |
| base unit | 1 (front) | 1 | 11 |
| unit symbol (fixed mark; no plural/period) | 2 (front) | 2 | 3, 17 |
| quantity symbol (writer's variable) | 3 (front) | 3 | — (contrast card; deliberate leaf) |
| value = number × unit; space convention | 4 (front) | 4 | 5, 12, 17 |
| conversion as substitution of equals | 5 (front) | 5 | 14 (PLAN/EVALUATE) |
| prefix (formal), symbol concatenation | 6 (front) | 6 (build mm) | 7, 10, 12, 16 |
| micro- (µ), mega- (M) | 7 (front) | 7, 8 (C), 9 (C) | 10, 11, 17 |
| case sensitivity of symbols | 10 (front) | 10 | 17 |
| no prefix stacking; kilogram anomaly | 11 (front) | 11 | — (bounded rule; leaf) |
| readable-prefix convention (0.1–1000) | 12 (front) | 12 | — (convention; leaf) |
| multi-step ladder conversion (compose factors) | 13 (front + figure) | 13 | 14, 15 |
| sixties-based time units are not prefixed | 16 (front) | 16 | — (discrimination card; leaf) |

Every deletion in both C blocks targets material established in an earlier scheduled block
(Est. 7). Both P/S blocks that retain IDENTIFY begin S at IDENTIFY; the faded block begins
at EXECUTE; all three place the direct result as the first sentence inside EXECUTE. No A:
or S: body begins with a bare number and period.

## Unresolved dependencies and proposed edges

None. No new inbound prerequisite edge was needed; the chapter uses only the declared
local edge `chapter:01_systems_quantities_and_models` plus the staged external closure.

cold_start_status: pass
unresolved_dependencies: 0
