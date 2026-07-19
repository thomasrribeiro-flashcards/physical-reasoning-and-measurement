# Pilot cold-start audit: systems, quantities, and models

cold_start_status: pass
unresolved_dependencies: 0

## Audit scope and learner contract

- Deck: physics/physical-reasoning-and-measurement
- Pilot: flashcards/01_systems_quantities_and_models.md
- Audited cards: 18 scheduled blocks in intended first-learning order
- Declared deck prerequisite:
  mathematics/elementary-algebra-and-functions
- Resolved transitive external closure:
  mathematics/quantitative-reasoning-and-arithmetic
- Assumed tools: none
- Allowed domain knowledge: none; all physics terminology is unseen
- Local inbound chapters: none

The staged schema-2 graph is the executable learner contract for this isolated
run. The staged algebra deck has no scheduled cards, so the pilot does not rely
on unverified symbolic-function vocabulary. Its calculation dependencies are
limited to scheduled arithmetic capabilities: whole-number and decimal
comparison, multiplication, less-than and greater-than signs, number–unit
measurements, simple unit conversion, and reasonableness checks.

No inbound edge was added. The recommended
mathematics/geometry-and-measurement deck remains unavailable and is not
assumed.

## Scan method

The chapter was scanned in scheduled order with answers withheld. For each
front, the parsing and attempt dependencies below were recorded before its
answer was checked. The answer was then inspected for terminology or procedures
that a later front might assume. Headings, prose outside blocks, and planning
tables were not counted as instruction.

The semantic scan caused six repairs before the final pass:

1. Front 01-02 now defines measuring apparatus, and its alt text carries the
   same A/B spatial information as the visible figure.
2. Front 01-04's answer no longer introduces unexplained magnitude wording.
3. Front 01-09 now states that the numerical record came from a ruler
   comparison, so a number and unit are not mistaken for proof of measurement.
4. Front 01-12 defines rigid as not bending before later use.
5. Front 01-17 defines schematic and explains its dimension arrows and
   not-to-scale convention before the visual decision.
6. Front 01-18 uses an ordinary board and the already-established stated model,
   avoiding extra display-panel and “size-only model” vocabulary.

## Front-by-front findings

| Front | Dependencies recorded before reading the answer | Allowed source or earlier establishment | Answer/back dependency check | Finding |
|---|---|---|---|---|
| 01-01 system and surroundings | Question; ordinary book/table; object/collection/region; inside/outside | Everyday language; the front defines system, system boundary, and surroundings | Answer uses only the three newly defined terms | pass |
| 01-02 boundary diagram | 01-01 system grammar; dashed candidate loops; A/B labels; book/ruler; measuring apparatus | 01-01; the front defines apparatus and loop meaning; Markdown alt and SVG description encode which objects each loop encloses | Answer uses prior surroundings and ordinary “measuring setup” | pass |
| 01-03 question-dependent boundary | Question and system boundary | 01-01 and 01-02 | Answer introduces no later required term | pass |
| 01-04 property versus quantity | Ordinary feature, title, height; number and unit | Number/unit is confirmed inbound; the front defines property and physical quantity in accessible language | Answer uses size/amount rather than unexplained metrology jargon | pass |
| 01-05 quantity versus value | Physical quantity; number and unit | 01-04 and confirmed inbound measurement-unit knowledge; front defines quantity value | Answer restates the target distinction without adding a later prerequisite | pass |
| 01-06 measurement and unit | Quantity value; ruler; comparison; guess | 01-05; front defines measurement and unit | Answer reinforces experimental comparison; no application precedes it | pass |
| 01-07 same quantity, different unit | Decimal equality; meter/centimeter conversion; physical length | Confirmed arithmetic closure; 01-04 through 01-06 | Answer distinguishes numerical value/unit from underlying quantity | pass |
| 01-08 measurand | Particular book, height, flat condition; measurement | 01-04 through 01-06; front defines measurand and supplies object/property/condition | Answer makes the target more specific but adds no required term | pass |
| 01-09 description versus measurement | Observation; descriptive record; ruler comparison; quantity value | 01-05, 01-06; front defines the observation contrast and states the experimental comparison | Answer uses already-established measured quantity value | pass |
| 01-10 simplified physical model | System; decorated box; rectangular outline; upright fit; purpose | 01-01; front defines physical model as purposeful simplified representation | Answer explains kept height/width and omitted decoration; no future-physics example | pass |
| 01-11 system versus model | Real box; rectangular drawing; system; model | 01-01 and 01-10 | Answer directly contrasts the established concepts | pass |
| 01-12 assumption and rigidity | Model; flat; rigid/not bending; accepted condition | 01-10; front defines assumption and rigid | Answer names model assumptions without new later dependency | pass |
| 01-13 purpose-dependent models | Same box; outer height/width; markings; useful model | 01-10 through 01-12 | Answer repeats the established height/width distinction and adds no later dependency | pass |
| 01-14 prediction | Model and assumptions; complete rows/slots; multiplication | 01-10 through 01-12; multiplication confirmed inbound; front defines prediction | Answer executes \(3\times4=12\) and repeats the stated completeness assumption | pass |
| 01-15 testability | Physical model; prediction; observation/measurement; possible disagreement | 01-09, 01-10, 01-14 | Answer defines the test relationship; no unseen mechanism is invoked | pass |
| 01-16 bounded mismatch inference | Prediction, observation, usable slot, strongest conclusion | 01-14 and 01-15; counts and comparison confirmed inbound | Answer names a mismatch and limits the inference; neither term is required unbridged later | pass |
| 01-17 analyzed fit schematic | System; rigid; model; assumption; prediction; less-than; measured height; dimension arrows; schematic/not-to-scale grammar | 01-01 through 01-16; less-than and unit comparison confirmed inbound; front explicitly teaches both visual conventions and supplies the model rule | Answer applies \(29\text{ cm}<31\text{ cm}\) and repeats the scope conditions | pass |
| 01-18 independent fit problem | Rigid board/opening; height; no tilting; ordered reasoning sequence; greater-than; model scope; IPEE headings on back | 01-01 through 01-17; comparison and IPEE structure confirmed in the scheduled arithmetic closure | Solution applies only established steps, checks the \(2\text{ cm}\) difference, and limits the conclusion to stated assumptions | pass |

## Dependency ledger result

The complete concept/representation ledger is maintained in CARD_README.md.
Every technical term, diagram convention, and procedure required by a front
maps either to the allowed arithmetic closure or to an explanation on that
front or an earlier scheduled card. No answer is the learner's first and only
access to knowledge that a later front requires.

The sequence establishes:

1. system, boundary, and surroundings;
2. property, quantity, quantity value, unit, measurement, and measurand;
3. descriptive observation versus measurement;
4. system versus model, simplification, assumption, and purpose;
5. prediction, test, and bounded mismatch inference;
6. analyzed then independent use of a simple comparison model.

## Figure audit

| Figure | Front role | Accessibility and leak check | Inspection |
|---|---|---|---|
| system-boundary-options | Choose a question-appropriate spatial boundary | TikZ source has non-empty title/description comments; SVG has viewBox, title, and description elements; Markdown alt reproduces the A/B enclosure information needed by a nonvisual learner. The image gives setup information but does not state which candidate satisfies the question. Dashes, labels, enclosure, and position make color redundant. | Full-size and 360-pixel-wide raster previews inspected; labels and dashed boundaries remain distinct. |
| upright-fit-model | Translate two measured heights and a stated rule into a prediction | TikZ source and SVG accessibility metadata are present. Front prose defines schematic, not-to-scale, dimension arrows, model rule, and assumptions before the image. Alt text supplies the same values and straight-upright arrangement; it does not state the prediction. Arrow direction, line style, labels, and geometry make color redundant. | Full-size and 360-pixel-wide raster previews inspected; 29 cm, 31 cm, the straight arrow, and not-to-scale note remain legible. |

Both figures were rendered with the deck figure renderer; editable TikZ and
matching accessible SVG are present. No photograph, generated raster asset,
hand-authored SVG exception, runtime TeX, or color-only cue is used.

## Planned versus actual pilot inventory

| Inventory | Planned | Actual | Reconciliation |
|---|---:|---:|---|
| Basic Q:/A: | 17 | 17 | matched |
| Cloze C: | 0 | 0 | matched; no target benefits from exact token deletion |
| Problem P:/S: | 1 independent after one analyzed basic-card example | 1 | matched |
| Figures | 2 front figures | 2 TikZ/SVG pairs | matched |
| Later-chapter cards or figures | 0 | 0 | matched; intentionally withheld by pilot gate |

No planned pilot target or earned figure opportunity is unexplained or missing.
Apparatus scale reading, graphs, temporal/before-after states, and a labeled
reasoning-cycle graphic remain intentionally omitted for the reasons recorded
in CARD_README.md.

## Validation evidence and isolated-run limitation

- Stable-ID check: pass; no missing stable IDs.
- Figure stale-output check: pass for two TikZ figures.
- Parser/markup validation: 18 cards (17 basic, 0 cloze, 1 problem), with zero
  parser warnings, KaTeX errors, image errors, identity errors, cloze lints, or
  frontmatter lints.
- Figure inspection: pass at full size and phone width.
- The full validator reports one prerequisite-resolution error because it looks
  for the declared algebra repository in the isolated workspace's parent
  directory. The machine-resolved staged graph and complete staged closure are
  present under .flashcards/prerequisites/ and were read. This sandbox-path
  limitation does not create an unexplained learner dependency and was not
  “repaired” by changing or adding an inbound edge.

## Pilot gate

The authored pilot has no unexplained front dependency and uses no later
physics concept as scaffolding. Chapters 2–10 remain planning rows only. Stop
for explicit human approval before authoring any later chapter.
