# Pilot cold-start audit — Chapter 1 (regenerated pilot)

Deck: `physics/physical-reasoning-and-measurement`
Chapter audited: `flashcards/01_systems_quantities_and_models.md` (19 cards: 18 `Q:/A:`, 0 `C:`, 1 `P:/S:`)
Audit date: 2026-07-22
Method: adversarial front-only simulation in first-learning order. For each
front, every domain-bearing word, representation, and implied process was
recorded and classified **before** the answer was inspected; answers were then
checked for terms that later fronts might silently assume. Headings, prose, and
figure content outside scheduled `Q:/A:` and `P:/S:` blocks were given no
instructional credit.

## Frozen learner contract

- Confirmed prerequisite deck: `mathematics/elementary-algebra-and-functions`
  (staged copy schedules one chapter: variables, expressions, substitution,
  evaluation).
- Machine-resolved external closure: `mathematics/quantitative-reasoning-and-arithmetic`
  (complete: numbers, comparison and `<`/`>`, arithmetic operations, decimals,
  fractions, ratios, percents, estimate versus exact ("about"/"roughly"),
  rounding, measurement as number-plus-unit, cm/m/g/kg/L/mL, conversions
  including 1 m = 100 cm, false precision, reasonableness checks, scale/ruler
  reading, tables, IPEE problem headings).
- Chapter 1 explicit concept edges: `measurement-unit` and `unit-conversion`,
  both provided by the arithmetic deck's chapter 10 in the staged closure.
- Confirmed subject (physics) knowledge: none. All physics vocabulary is
  treated as unseen.
- Assumed tools: none. No inbound edge beyond the sandbox-resolved closure was
  added; no unresolved edge was proposed.

## Front-by-front findings

Front labels 01-01 … 01-19 follow file order. "Inbound" = arithmetic/algebra
closure above; "01-NN" = established by that scheduled front.

| Front (card-id prefix) | Target decision | Dependencies found on the front | Source of each | Verdict |
|---|---|---|---|---|
| 01-01 (ed58aef2) | Classify unchosen objects as surroundings | system, system boundary, surroundings (all defined on this front); box/shelf/closet (ordinary) | self-bridged on front | pass |
| 01-02 (7b7f1595) | Infer that one boundary may enclose separated objects | system, boundary (01-01); imagined/chooser-drawn (bridged on front) | 01-01 + front bridge | pass |
| 01-03 (1aa00cc9) | Choose the boundary suited to the stated question (figure) | system boundary (01-01); chooser-drawn (01-02); dashed-loop and letter-label grammar (explained on front); alt text uses only established words | 01-01, 01-02 + front bridge | pass |
| 01-04 (192d8b16) | Explain question-dependence of system choice | system (01-01); boundary chosen for a question (01-02, 01-03) | 01-01–01-03 | pass |
| 01-05 (a3849f0e) | Discriminate property from physical quantity | property, physical quantity (defined on front); number-with-unit, cm | front bridge; inbound | pass |
| 01-06 (2655ebe3) | Separate quantity from quantity value | quantity (01-05); quantity value (defined on front); number, unit, centimeter | 01-05 + front bridge; inbound | pass |
| 01-07 (41b502e9) | Identify what changes between unit reports | quantity value (01-06); 1 m = 100 cm exact identity; decimals | 01-06; inbound | pass |
| 01-08 (479582d1) | Identify the measurement result and why | measurement, instrument (defined/bridged on front); ruler, unit markings, estimate ("roughly") | front bridge; inbound (scale reading, estimate vs exact) | pass |
| 01-09 (10dd8e1b) | Name a missing measurand specification | measurand (defined on front: object/property/condition); measurement (01-08); quantity (01-05) | front bridge; 01-08; 01-05 | pass |
| 01-10 (c56da2b9) | State what a measurement adds over a description | observation (defined on front); measurement (01-08); quantity value (01-06); taller-than comparison | front bridge; 01-08; 01-06; inbound | pass |
| 01-11 (b4b274e7) | Explain what makes a drawing a model | physical model (defined on front); system (01-01) | front bridge; 01-01 | pass |
| 01-12 (3eadac7a) | Discriminate system from model | system (01-01); model (01-11); quantity value label (01-06) | established earlier | pass |
| 01-13 (71da68d5) | Diagnose the threatened assumption | assumption, rigid (both defined on front); model (01-11) | front bridge; 01-11 | pass |
| 01-14 (8399d662) | Select the purpose-relevant detail | model keeps question-needed features (01-11); cm; width comparison | 01-11; inbound | pass |
| 01-15 (dc9e1660) | Compute the model's prediction | model prediction (defined on front); model, assumptions (01-11, 01-13); 3 × 4 multiplication | front bridge; 01-11, 01-13; inbound | pass |
| 01-16 (20595df8) | Justify why the comparison is a genuine test | model test (defined on front: must be able to disagree); prediction (01-15); observed/measured (01-08, 01-10); count | front bridge; 01-15; 01-08/01-10; inbound | pass |
| 01-17 (4247702d) | State the bounded conclusion a mismatch supports | prediction (01-15); test comparison (01-16); counts 12 vs 10 | 01-15, 01-16; inbound | pass |
| 01-18 (61281564) | Read the schematic and predict from labels, not drawn size (figure) | schematic, double-headed dimension arrow, "not to scale" (all explained on front); rigid (01-13); model rule supplied on front; quantity values, `<` comparison | front bridge; 01-13; 01-06; inbound | pass |
| 01-19 (67e1b5bd) | Independent fit prediction with reasoning check (P/S) | rigid (01-13); model/prediction (01-11, 01-15); upright-fit rule (01-18, restated faded on front); cm comparison | 01-13, 01-11, 01-15, 01-18; inbound | pass |

Answer-side scan: each back leads with the direct answer and uses only terms
inbound or established on or before its own front. The only method shown on a
back that later fronts rely on is the upright-fit comparison, which 01-18
establishes as an analyzed example before 01-19 requires it independently. The
`S:` block's IPEE headings are inbound from the arithmetic deck's problem
cards; "measurand" and "quantity value" in the solution were established at
01-09 and 01-06.

## Figure audit

| Figure | Checks |
|---|---|
| `system-boundary-options.svg` (front of 01-03) | TikZ source beside same-named SVG; `viewBox`, `role="img"`, `aria-labelledby`, `<title>`, `<desc>` present. Dashed loops + letter labels give a redundant non-color cue. Label "A" sits directly above its own loop; "book" label clear of loop B's edge. Legible at 900 px and 360 px. Alt text describes both candidates without naming the correct one. |
| `upright-fit-model.svg` (front of 01-18) | Same structural checks pass. Dimension arrows combine color, double-headed shape, and text labels (redundant cues). Extension guides do not overlap the shelf boards. "not to scale" note present; the box is deliberately drawn taller than the gap, and the alt text states this appearance so a non-sighted learner faces the same trap a sighted learner must reject. Legible at 900 px and 360 px. |

## Repairs made during the audit cycle

- Figure `system-boundary-options`: repositioned label "A" directly above its
  own loop (was ambiguously near loop B's edge) and moved "book" below loop
  B's bottom edge (dashes previously ran through the word).
- Figure `upright-fit-model`: gap extension guides shortened so they start
  clear of the shelf boards' right ends.
- No card-front repairs were required: no hidden prerequisite, future-facing
  example, blocked dependency, or multi-idea front was found in the final text.

## Inventory reconciliation

Planned (CARD_README design ledger): 18 `Q:/A:`, 0 `C:`, 1 `P:/S:`, 2 figures.
Actual: 18 `Q:/A:`, 0 `C:`, 1 `P:/S:`, 2 figures. Matched; zero clozes remain
intentional (every target requires discrimination, explanation, prediction, or
method execution rather than token recall). All 11 frontmatter `provides`
concepts are established by scheduled fronts. Rejected example families
(motion, force, energy, heating, circuits, light, sound) were kept out; all
scenarios use static objects, lengths, and counts within the inbound closure.

## Status

Every dependency row above is confirmed inbound, established earlier, or
minimally self-bridged on its own front. No row is blocked or unresolved.

```text
cold_start_status: pass
unresolved_dependencies: 0
```
