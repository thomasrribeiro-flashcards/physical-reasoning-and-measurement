# Physical Reasoning And Measurement card blueprint

This file records retrieval decisions specific to this deck. Universal card,
parser, identity, and figure rules remain in the staged standards.

## Learner model

- Level: foundational; physics vocabulary is unseen
- Confirmed mathematical prerequisite:
  `mathematics/elementary-algebra-and-functions`, whose resolved external
  closure includes arithmetic, decimals, ratios, comparisons, basic unit
  conversion, scale reading, and reasonableness checks
- Confirmed subject prerequisites: none
- Assumed tools: none
- Capabilities this deck should produce: move from a physical question to a
  chosen system, measurable quantities, a model, predictions, measurements,
  checks, and a bounded evidence claim
- Important exclusions: phenomenon-specific concepts such as force, velocity,
  energy, momentum, fields, waves, circuits, and thermal mechanisms; extended
  laboratory, derivation, coding, and statistical work remains outside SRS

The declared algebra deck is the machine-readable prerequisite; its staged copy
now contains one scheduled chapter (variables, expressions, substitution, and
evaluation). The pilot nevertheless relies only on elementary comparisons,
arithmetic, and measurement skills explicitly visible in the scheduled
transitive arithmetic closure, and assumes no symbolic-function vocabulary.

## Curriculum and prerequisite decisions

Chapter 1 has no local inbound chapter. Its exact external concept edges resolve
`measurement-unit` and `unit-conversion` to
`mathematics/quantitative-reasoning-and-arithmetic#10_measurement_estimation_and_decisions`
through the declared transitive deck closure. It establishes the grammar that every
later chapter may reuse: question-dependent system boundaries, physical
quantities and values, measurement targets, purposeful models, assumptions,
predictions, and tests. A chapter's earlier file number is not treated as an
edge unless its future frontmatter says so.

Rejected hard inbound edge: `mathematics/geometry-and-measurement` remains only a
recommended deck. Chapter 1 uses simple height comparisons and supplies its own
diagram grammar, so it does not need that unavailable deck. No unresolved edge
is proposed.

## Pilot concept-dependency ledger

Front labels refer to the planned and actual order in
`01_systems_quantities_and_models.md`.

| Concept or representation | Front(s) requiring it | Confirmed inbound source or first explanation | First supported retrieval | Later application | Status |
|---|---|---|---|---|---|
| Number comparison, `<`, multiplication, decimals, cm/m and 1 m = 100 cm, estimate ("roughly") versus measured value, counting | 01-05 through 01-08, 01-14, 01-15, 01-17 through 01-19 | Scheduled arithmetic closure: whole-number comparison, multiplication, decimals, and measurement/estimation chapters | Inbound | Throughout | confirmed inbound |
| Ruler and scale reading | 01-08, 01-10 | Scheduled arithmetic measurement chapter; 01-08 front re-bridges "instrument" in ordinary language | Inbound | 01-10, 01-19 | confirmed inbound |
| IPEE problem headings | 01-19 back only | Repeatedly established in scheduled arithmetic problem cards | Inbound | 01-19 | confirmed inbound |
| System; system boundary; surroundings | 01-01 onward | 01-01 front defines all three in ordinary language | 01-01 | 01-02 through 01-04, 01-11, 01-12, 01-19 | established |
| Boundary as an imagined, chooser-drawn line that may enclose separated objects | 01-02 onward | 01-02 front supplies the bridge before asking for the inference | 01-02 | 01-03, 01-04 | established |
| Dashed candidate-boundary loops and letter labels | 01-03 | 01-03 front explains the diagram grammar before asking for a choice | 01-03 | Future system diagrams | established |
| Question-dependent system choice | 01-04 onward | 01-03 answer justifies the choice by the stated question; 01-04 asks for the principle | 01-04 | 01-14, 01-19 | established |
| Property and physical quantity | 01-05 onward | 01-05 front contrasts a general feature with one reportable as number plus unit | 01-05 | 01-06 through 01-10, 01-19 | established |
| Quantity value; number–unit report | 01-06 onward | 01-06 front distinguishes the quantity from the report expressing it | 01-06 | 01-07, 01-08, 01-10, 01-18, 01-19 | established |
| Same quantity, different unit reports | 01-07 | 01-07 front supplies the exact identity and asks what changed | 01-07 | Chapters 2 and 7 | established |
| Measurement as a carried-out experimental comparison; instrument | 01-08 onward | 01-08 front defines both; arithmetic closure already established comparing to a unit | 01-08 | 01-09, 01-10, 01-16, 01-19 | established |
| Measurand: object, property, condition | 01-09 | 01-09 front defines it before asking for a missing specification | 01-09 | Chapters 3–4 | established |
| Observation versus measurement | 01-10 | 01-10 front explains that observation may be descriptive; measurement yields a quantity value | 01-10 | 01-16, 01-17 | established |
| Physical model as purposeful simplified stand-in | 01-11 onward | 01-11 front defines it before asking what makes the drawing a model | 01-11 | 01-12 through 01-19 | established |
| System versus model discrimination | 01-12 | Both terms established (01-01, 01-11) before the contrast | 01-12 | 01-19 | established |
| Assumption; rigid | 01-13 onward | 01-13 front defines both before the fabric-cube diagnosis | 01-13 | 01-18, 01-19 | established |
| Purpose decides which details a model keeps | 01-14 | 01-11 front establishes "keeps only the features the question needs"; 01-14 applies it | 01-14 | 01-19 | established |
| Model prediction | 01-15 onward | 01-15 front defines it before the jar-count computation | 01-15 | 01-16 through 01-19 | established |
| Model test must be able to disagree | 01-16 onward | 01-16 front defines the comparison before asking why it is genuine | 01-16 | 01-17, 01-19 | established |
| Mismatch supports only a bounded conclusion | 01-17 | 01-15 and 01-16 establish prediction and test; 01-17 asks for the inference | 01-17 | Chapters 4, 5, 9, and 10 | established |
| Schematic; dimension arrows; not-to-scale convention | 01-18 | 01-18 front explains all three cues before asking for a prediction | 01-18 | 01-19 and later technical diagrams | established |
| Upright-fit rule and its scope | 01-18 onward | 01-18 front states the rule; 01-19 front restates it faded for independent use | 01-18 | 01-19 evaluation checks scope explicitly | established |

Rejected examples for the pilot include falling objects, pushes, collisions,
moving vehicles, heating, springs, circuits, magnets, light, and sound. They
would import force, acceleration, energy, momentum, temperature-change
mechanisms, oscillation, field, circuit, ray, or wave vocabulary from later
decks. Simple boxes, shelves, rulers, counts, and length comparisons test the
same foundational decisions without those dependencies.

## Retrieval portfolio and interference map

Chapter 1 schedules distinct decisions for:

- selecting a system for a stated question and reading a system-boundary
  diagram;
- distinguishing property/quantity, quantity/value, system/model, and
  observation/measurement;
- identifying a measurand with object, property, and relevant condition;
- explaining why units can change while the underlying quantity does not;
- identifying simplifications and assumptions by purpose;
- making a prediction, recognizing testability, and interpreting a mismatch
  without overclaiming;
- carrying out an independent question → system → quantity → model → prediction
  → scope check on a new fit situation.

The nearest interference pairs are explicitly contrasted only after both sides
are established: system/surroundings, property/quantity, quantity/quantity
value, system/model, description/measurement, and prediction/observation.

## Chapter design ledger

Later rows are curriculum plans only; the pilot gate forbids authoring their
cards or figures now.

| Chapter | Retrieval targets and basic-card roles | Cloze candidates | Problem progression | Authentic representations and figure opportunities |
|---|---|---|---|---|
| 1. Systems, quantities, and models | Definitions by supported discrimination; boundary choice; representation translation; assumption and scope diagnosis; prediction and mismatch interpretation | None: every target needs a distinction or reason, not token insertion | Analyzed upright-fit example → independent fit problem with a scope check | Include candidate-boundary diagram and physical-situation-to-schematic fit diagram; omit apparatus scale, graph, and process-cycle figures for reasons below |
| 2. SI units and quantity values | Quantity/unit/symbol distinctions, prefix meaning, conversion direction, notation diagnosis | Possible exact symbols/prefix factors only after meaning is established | Worked conversion → faded multi-prefix conversion → mixed notation and conversion diagnosis | SI relationship table; prefix scale; unit-expression translations; figures selected during Chapter 2 design |
| 3. Measurement procedures and resolution | Procedure ordering, instrument choice, scale/digital reading, alignment and resolution errors | None anticipated; readings require interpretation | Analyzed ruler setup → completion reading → independent procedure choice → mixed instrument diagnosis | Ruler alignment, parallax views, analog scale, digital display, and apparatus schematic opportunities |
| 4. Repeated measurements and uncertainty | Repeat variation, interval/result meaning, mistake versus uncertainty, agreement for purpose | Possible compact result notation only after conceptual work | Analyzed repeats → summarize data → compare two results → diagnose overprecision | Dot plots, interval bars, repeated-reading table, before/after correction; no decorative apparatus |
| 5. Tables, graphs, and data patterns | Axis/column meaning, trend and interpolation, graph/table translation, artifact diagnosis | None anticipated | Read a worked graph → complete a plot → independently choose/interpret a display → mixed artifact check | Authentic tables, scatter plots, line graphs, competing axis choices, and residual-like difference plots at novice depth |
| 6. Proportional reasoning and scaling | Direct/inverse distinction, scale factors, ratio invariance, data test of a scaling claim | Possible compact proportional form after interpretation | Worked table → predict by scale factor → infer rule → discriminate proportional from merely increasing | Double-number line, proportional/nonproportional tables, graph families, scaled object diagrams |
| 7. Dimensions and derived quantities | Derived-unit construction, unit algebra, dimensional consistency, same-unit/same-kind distinction | Possible exact dimension/unit relations after derivation | Worked unit construction → completion cancellation → independent equation check → mixed false-positive check | Unit-cancellation maps, dimension trees, competing equations; geometry figures only if the chosen derived quantity requires them |
| 8. Estimation and order of magnitude | Reference choice, decomposition, bounds, powers-of-ten comparison, assumption reporting | Possible powers-of-ten benchmarks after meaning is established | Analyzed Fermi decomposition → completion estimate → independent estimate → compare two strategies | Scale ladders, bounding intervals, decomposition tree; photographs omitted unless an authentic visual estimate needs one |
| 9. Building and testing models | Translate representations, derive predictions, compare models, revise assumptions, identify regime and limitation | None anticipated | Worked model construction → faded prediction → independent model choice → mismatch-driven revision | System/model pairs, model flow, competing prediction graphs, regime maps, and before/after revisions |
| 10. Evidence, claims, and communication | Claim/evidence/reasoning links, consistency versus proof, uncertainty-aware reporting, critique and investigation design | None anticipated | Annotated argument → repair an incomplete claim → independent mini-investigation → mixed critique | Claim-evidence maps, compact results tables/plots, investigation schematic; avoid text-heavy decorative infographics |

### Chapter 1 figure opportunity inventory

| Opportunity | Decision | Retrieval role or reason |
|---|---|---|
| System boundary in a physical setup | Include: `system-boundary-options` | Learner must inspect which objects a dashed candidate boundary encloses and choose the boundary suited to the stated question. Text alone would remove the spatial decision. |
| Physical setup translated to a straight-upright fit model | Include: `upright-fit-model` | Learner must map two measured heights in a schematic to the model rule and make a prediction; “not to scale” prevents visual magnitude leakage. |
| Detailed object simplified into a generic outline | Omit as a separate figure | The included fit schematic already exercises this translation; another outline would duplicate the same scheduling decision. |
| Measuring-instrument alignment or scale reading | Omit from Chapter 1; reserve for Chapter 3 | It requires apparatus, alignment, and resolution grammar not needed to test system/model choice. |
| Quantity–number–unit relationship map | Omit | A short verbal contrast is clearer at this stage; a labeled map would mainly restate the answer. |
| Question → system → quantity → model → prediction cycle | Omit | The sequence is practiced through scheduled fronts and the problem; a labeled flowchart would be text-heavy and answer-revealing. |
| Graph, timeline, or before/after state | Omit | Chapter 1 has no graphical or temporal retrieval target. Graph grammar begins in Chapter 5. |

## Initial-learning path

Every new term first appears in a scheduled front that gives a minimal bridge
and asks for an inference or discrimination possible from that bridge. Later
fronts fade support in this order: system and boundary → property and quantity →
value, unit, measurement, and measurand → observation contrast → model and
assumption → prediction and test → analyzed schematic → independent problem.
Headings and figures outside card blocks are never counted as instruction.

The final problem asks for one integrated modeling decision. Its IPEE solution
names the system and quantity, applies the already-analyzed comparison rule,
computes the prediction, and checks both arithmetic and scope. It does not
introduce a new method on the back.

## Chapter 2 design ledger (SI units and quantity values)

Allowed inbound frontier for this chapter: the resolved external closure
(arithmetic capabilities including decimals, ratios, whole-number powers, and
the fully scheduled measurement chapter with meter/cm/km, gram/kg, liter/mL,
s/min/h, centi-/kilo-/milli- meanings, conversion direction, precision, and
number-needs-unit; algebra capabilities variable, equation, substitution,
expression evaluation) plus every concept scheduled in Chapter 1. Negative
exponents and scientific notation are *not* inbound; all prefix factors are
therefore stated as decimal fractions or plain products, and order-of-magnitude
language waits for Chapter 8.

Retrieval targets mapped to card forms:

| Target | Form | Ledger note |
|---|---|---|
| SI as the worldwide system; base units as starting references (including m, kg, s) | `Q:/A:` 02-01 | "SI" and "base unit" bridged on the front from inbound "agreed unit" |
| Unit symbols are fixed international marks, not abbreviations (no plural, no period) | `Q:/A:` 02-02 | notation diagnosis of "12 kms." |
| Quantity symbol (chosen variable) versus unit symbol (fixed) | `Q:/A:` 02-03 | bridges the algebra `variable` capability |
| Quantity value read as number × unit; space between number and symbol | `Q:/A:` 02-04 | extends Chapter 1 quantity/value split |
| Conversion as substitution of an equal unit relation; quantity unchanged | `Q:/A:` 02-05 | uses algebra `substitution`; re-grounds Chapter 1 card on 40 cm = 0.40 m |
| Prefix as fixed multiplier on any unit; symbol concatenation; build mm | `Q:/A:` 02-06 | generalizes inbound centi-/kilo-/milli- |
| micro- (µ) and mega- (M) meanings | `Q:/A:` 02-07 | supported comparison 1 µm vs 1 mm |
| Exact recall: micro factor; mega factor | `C:` 02-08, 02-09 | clozes only after meaning established, per blueprint |
| Case sensitivity of symbols (mg vs Mg) | `Q:/A:` 02-10 | interference pair established on both sides first |
| Kilogram contains a prefix; further prefixes attach to gram | `Q:/A:` 02-11 | notation diagnosis of "millikilogram" |
| Choose a prefix that makes the number readable | `Q:/A:` 02-12 | 0.004 m → 4 mm with a bounded number-range cue |
| Compose conversion factors along the prefix ladder; direction | `Q:/A:` 02-13 | figure card: trace cm → km on the ladder |
| Full multi-prefix conversion method | `P:/S:` 02-14 | analyzed IPEE: 2.4 km → cm through the base unit |
| Faded conversion | `P:/S:` 02-15 | EXECUTE/EVALUATE only: 52 000 cm → km |
| Prefix ladder scope: minute/hour are not prefixed seconds | `Q:/A:` 02-16 | discriminates tens-based prefixes from sixties-based time units |
| Mixed notation audit with a conversion-based check | `P:/S:` 02-17 | parts-label diagnosis; EVALUATE uses benchmarks and case sanity |

Problem progression: analyzed full IPEE (02-14) → faded (02-15) → mixed
diagnosis (02-17), with 02-13 as the supported representation-trace step before
independent execution. Intentionally omitted: the four remaining SI base units
(their kinds of quantity — temperature, electric current, amount of substance,
luminous intensity — are future-deck vocabulary; a bounded clause on 02-01
notes their existence without naming them); scientific notation (needs
negative exponents, not inbound); the liter's non-SI status beyond the scope
card 02-16 (deeper unit-system history adds no retrieval decision here).

### Chapter 2 figure opportunity inventory

| Opportunity | Decision | Retrieval role or reason |
|---|---|---|
| Prefix ladder mm–cm–m–km with stated unit equalities | Include: `prefix-ladder` (front of 02-13) | Learner must trace a two-step path and compose direction and factors; the equalities are setup, the composition is the retrieval. Also serves as the chapter's SI relationship representation. |
| Quantity-value anatomy diagram (number, space, prefix, unit symbol) | Omit | A labeled anatomy figure would restate the notation rules it is meant to test; verbal contrast plus the 02-17 audit problem exercises the same decision. |
| Aligned two-line conversion map (km/m) | Omit | Duplicates the inbound arithmetic figure grammar and skill; no new scheduling decision. |
| Object-size scale with µm-to-km benchmarks | Omit | Honest spacing needs a logarithmic axis, which is not established until Chapter 8; benchmarks are given verbally instead. |
| Prefix factor table as an image | Omit | Exact factors are retrieval targets (clozes), so a permanent table on a front would leak answers; the ladder figure carries the relational picture. |

## Planned versus actual inventory

| Chapter | Basic `Q:/A:` | Cloze `C:` | Problem `P:/S:` | Figures | Reconciliation |
|---|---:|---:|---:|---:|---|
| 1 planned | 18 | 0 | 1 | 2 front figures, each with editable TikZ and accessible SVG | baseline |
| 1 actual | 18 | 0 | 1 | 2 front figures, each with editable TikZ and accessible SVG | matched; the analyzed fit appears as a supported basic card (01-18) before the independent problem (01-19) |
| 2 planned | 12 | 2 | 3 | 1 front figure (prefix ladder), TikZ + SVG | baseline for the chapter-2 isolated build |
| 2 actual | 12 | 2 | 3 | 1 front figure (prefix ladder), TikZ + SVG | matched; clozes appear only after 02-07 establishes both new prefix meanings |
| 3–10 actual | 0 | 0 | 0 | 0 | intentionally withheld; later chapters are outside this build's boundary |

The pilot has no unexplained card-form, problem, or figure difference. The
absence of clozes remains intentional because the targets require discrimination,
explanation, prediction, or method execution rather than exact token recall.

## Figure policy

Chapter 1 uses one shared TikZ style and editable sources beside matching SVGs
under `figures/01_systems_quantities_and_models/`. Front alt text describes the
setup and diagram grammar without stating the answer. SVG `<title>` and `<desc>`
elements provide a fuller accessible description. Color is redundant with
dashes, shape, labels, and position.

## Sources and accuracy

The deck source register is in `README.md`. The BIPM SI Brochure and VIM govern
metrological distinctions; NIST provides a national-institute cross-check; AAPT
guidance selects the modeling, measurement, visualization, and communication
capabilities. Exact technical definitions are paraphrased into original
novice-facing prose without changing their decisive distinctions.

## Validation gate

Before handoff:

1. Run `flashcards deck stabilize . --check`.
2. Run `flashcards deck validate .`.
3. Inspect every changed SVG at full size and phone width.
4. Complete the front-by-front cold-start audit.
5. Reconcile planned and actual card, problem, and figure inventories.
6. Run `git diff --check` and review the complete diff.
7. Stop for explicit pilot approval; do not author Chapters 2–10.

## Chapter 3 design ledger (measurement procedures and resolution)

Allowed inbound frontier: Chapter 1 capability summary (system, quantity,
value, measurement, measurand, instrument, model terms), Chapter 2 scheduled
cards (SI, symbols, prefixes, notation, ladder conversion, IPEE), the scheduled
arithmetic closure (scale reading, precision claims of the last written place,
rounded-value intervals, conversion, mL/g/cm benchmarks), and the algebra
capability summary. Uncertainty vocabulary (intervals on results, mistakes
versus variation, repeated readings) is deliberately reserved for Chapter 4.

Retrieval targets mapped to card forms:

| Target | Form | Ledger note |
|---|---|---|
| Procedure versus measurand: what the how-recipe fixes | `Q:/A:` 03-01 | bridges from the inbound measurand capability |
| Recognizing a procedure; repeatability test | `Q:/A:` 03-02 | discrimination between vague and complete instructions |
| Scale division and division-size computation | `Q:/A:` 03-03 | re-grounds inbound scale grammar, adds the anchors-plus-steps rule |
| Two-reading (subtract) method | `Q:/A:` 03-04 | supported inference 9.5 − 3.0; feeds zero error and P1 |
| Zero error direction, size, and fix | `Q:/A:` 03-05 | broken-tip ruler prediction |
| Parallax: correct eye position and shift direction | `Q:/A:` 03-06 | figure card; geometry traced, not stated |
| Resolution definition; coarse versus fine ruler | `Q:/A:` 03-07 | honest claim: sub-division differences show unreliably, not never |
| Digital display steps and digital resolution | `Q:/A:` 03-08 | bridges "balance"; sub-step change usually invisible |
| Digital-exactness misconception | `Q:/A:` 03-09 | contrast after both members established |
| Record-to-resolution rule (34 vs 34.0 vs 34.00 mm) | `Q:/A:` 03-10 | extends inbound precision-claim card into procedure language |
| False precision from computation | `Q:/A:` 03-11 | 100 ÷ 3 shelves; echoes inbound conversion-adds-no-knowledge idea |
| Range; single-placement instrument choice | `Q:/A:` 03-12 | ruler-versus-tape method choice |
| Resolution matched to purpose | `Q:/A:` 03-13 | flour versus sub-gram tablet |
| Read-and-record with the two-reading method | `P:/S:` 03-14 | analyzed full IPEE on the ruler figure |
| Scale reading with division-size resolution | `P:/S:` 03-15 | faded IPEE (all headings, thin support) on the volume figure |
| Mixed procedure audit: zero error + parallax + false precision | `P:/S:` 03-16 | independent diagnosis integrating the chapter |

Cloze count is zero by design: every target here is a discrimination,
prediction, diagnosis, or method execution; no compact token merits exact
recall. Problem progression: analyzed (03-14) → faded (03-15) → independent
mixed (03-16), with supported single-step retrievals (03-03 through 03-06)
preceding them.

### Chapter 3 figure opportunity inventory

| Opportunity | Decision | Retrieval role or reason |
|---|---|---|
| Rod mid-scale on a millimeter ruler | Include: `ruler-offset-reading` (front of 03-14) | Learner must read both ends against real divisions and subtract; text would supply the readings and delete the task. |
| Pointer sighted from three eye positions | Include: `parallax-views` (front of 03-06) | The shift direction must be traced along drawn sight lines; this spatial inference is the retrieval target. |
| Liquid level against a labeled mL scale | Include: `volume-scale-reading` (front of 03-15) | Division-size computation plus counted-step reading on an authentic vertical scale; distinct from the ruler task. |
| Digital display drawing | Omit | A digital indication is purely textual (12.47 g); a drawing adds no spatial decision beyond the prose. |
| Apparatus schematic of the window/tape scenario | Omit | The audit target is procedural, not spatial; a drawing would either leak the errors or decorate. |
| Worn-ruler-tip close-up | Omit | The 0.2 cm shift is fully specified in prose; the prediction is arithmetic, not visual. |

### Chapter 3 planned versus actual inventory

| Chapter | Basic `Q:/A:` | Cloze `C:` | Problem `P:/S:` | Figures | Reconciliation |
|---|---:|---:|---:|---:|---|
| 3 planned | 13 | 0 | 3 | 3 front figures, TikZ + SVG | baseline for the chapter-3 isolated build |
| 3 actual | 13 | 0 | 3 | 3 front figures, TikZ + SVG | matched; no unexplained omission |

## Chapter 4 design ledger (repeated measurements and uncertainty)

Allowed inbound frontier: Chapter 3 scheduled cards (procedure, scale
division, two-reading method, zero error, parallax, resolution, digital
resolution, false precision, instrument range and choice), the Chapter 1–2
capability summaries (system/quantity/value/measurement/measurand/model
terms; SI, symbols, prefixes, conversion, notation), IPEE headings from the
scheduled arithmetic problem cards, and the scheduled external closure
(decimals, halving, number lines, measurement precision, rounded-value
intervals, reasonableness checks). The mean is *not* inbound and is taught on
a scheduled front from inbound addition and division. Formal statistics
(standard deviation, distributions, confidence) stays outside the deck; axis
graph grammar waits for Chapter 5 — the dot plot is bridged as dots above an
inbound number line.

| Target | Form | Ledger note |
|---|---|---|
| Repeat variation is normal; one reading hides it | `Q:/A:` 04-01 | bridged from ch3 procedure vocabulary |
| Dot plot reading: cluster and stray value | `Q:/A:` 04-02 | figure card; dot plot bridged on the front |
| Mistake versus variation; exclusion needs a cause | `Q:/A:` 04-03 | parallax slip reuses the ch3 mechanism |
| Mean as best value: computation plus rationale | `Q:/A:` 04-04 | mean taught here (add, divide by count) |
| Range/half-range of readings; instrument-range interference | `Q:/A:` 04-05 | explicit contrast with ch3 "range" |
| Spread comparison across two procedures | `Q:/A:` 04-06 | figure card; repeatability judgment |
| Uncertainty, interval claim, and the ± sign | `Q:/A:` 04-07 | bridges the external rounded-value interval |
| Exact reporting convention | `C:` 04-08 | one deletion, after 04-07 establishes the term |
| Resolution floor when scatter is zero | `Q:/A:` 04-09 | joins ch3 resolution to uncertainty |
| Consistent rounding of value and uncertainty | `Q:/A:` 04-10 | extends ch3 false precision |
| Averaging cannot remove a constant shift | `Q:/A:` 04-11 | ch3 broken-tip zero error revisited |
| Random versus systematic error, with remedies | `Q:/A:` 04-12 | same cause, either kind, by procedure |
| Agreement as interval overlap | `Q:/A:` 04-13 | figure card |
| Overlap means consistency, not equality | `Q:/A:` 04-14 | bounded-conclusion discrimination |
| Uncertainty judged against a purpose | `Q:/A:` 04-15 | decided versus undecided fit cases |
| Analyzed full summary with a justified exclusion | `P:/S:` 04-16 | reuses the dot-plot figure |
| Faded summary with nothing to exclude | `P:/S:` 04-17 | volume scale from ch3 |
| Compare two results for one measurand | `P:/S:` 04-18 | a gap exposes a hidden systematic error |
| Mixed audit: exclusion, overprecision, systematic claim | `P:/S:` 04-19 | integrates 04-03, 04-10, 04-11 |

Problem progression: analyzed (04-16) → faded (04-17) → independent
comparison (04-18) → mixed audit (04-19), preceded by supported single-step
retrievals. The single cloze is the chapter's only compact exact-recall
target; every other target needs discrimination, prediction, diagnosis, or
method execution.

### Chapter 4 figure opportunity inventory

| Opportunity | Decision | Retrieval role or reason |
|---|---|---|
| Dot plot of repeats with cluster and stray | Include: `repeat-dot-plot` (fronts of 04-02, 04-16) | cluster and outlier judgment is spatial; a printed list would delete the task |
| Two procedures' scatter on one shared scale | Include: `spread-comparison` (front of 04-06) | comparing spreads is the retrieval; row placement and dot shape are redundant non-color cues |
| Two uncertainty bars on one number line | Include: `interval-overlap` (front of 04-13) | overlap must be inspected, not stated; labels carry the ± values as setup |
| Repeated-reading table | Omit | readings are short inline lists; a table image adds no scheduling decision |
| Before/after correction figure | Omit | the 04-19 audit targets are procedural; a drawing would leak the diagnosis |
| Apparatus drawings | Omit | instruments were established visually in Chapter 3; decorative here |

### Chapter 4 planned versus actual inventory

| Chapter | Basic `Q:/A:` | Cloze `C:` | Problem `P:/S:` | Figures | Reconciliation |
|---|---:|---:|---:|---:|---|
| 4 planned | 14 | 1 | 4 | 3 front figures, TikZ + SVG | baseline for the chapter-4 isolated build |
| 4 actual | 14 | 1 | 4 | 3 front figures, TikZ + SVG | matched; validator total 35 deck cards = 16 (ch3) + 19 (ch4), no unexplained omission |

## Chapter 5 design ledger (tables, graphs, and data patterns)

Allowed inbound frontier: Chapter 4 scheduled cards (repeat variation, dot
plots, mistakes and exclusion-needs-cause, mean, reading range, uncertainty
intervals, ±, resolution floor, random/systematic error, agreement, purpose),
capability summaries for Chapters 1–3 (system/quantity/value/measurement/
measurand/model terms; SI, symbols, prefixes, conversion, notation; procedure,
scale division, resolution, false precision, instrument choice), IPEE headings
from the scheduled arithmetic problem cards, and the scheduled external closure
(number lines, decimals, subtraction/halving, averaging arithmetic, mL/g/cm
units, reasonableness checks). Two-axis graph grammar is *not* inbound — the
Chapter 4 dot plot used a single number line — so axes are taught here from the
inbound number line. Proportionality language waits for Chapter 6; only
"steady rise / equal steps" wording is used.

| Target | Form | Ledger note |
|---|---|---|
| Table grammar: column = quantity, header carries the unit once | `Q:/A:` 05-01 | bridges from quantity-value (number × unit) |
| Independent versus dependent quantity | `Q:/A:` 05-02 | who-fixes-the-value test; coin/balance context |
| Successive differences expose a pattern in a table | `Q:/A:` 05-03 | markdown table on the front; repeat variation explains wobble |
| Graph axes, axis roles, data point | `Q:/A:` 05-04 | axes bridged as two number lines; convention supported |
| Read a marked point against both axis scales | `Q:/A:` 05-05 | figure card; reuses ch3 scale-division skill |
| Axis scale must be a true number line | `Q:/A:` 05-06 | uneven-label diagnosis (0,5,10,20,40) |
| Trend despite scatter | `Q:/A:` 05-07 | figure card; collective behavior versus single points |
| Trend line versus dot-to-dot joining | `Q:/A:` 05-08 | figure card (two treatments); links to mean logic |
| Anomalous point handling | `Q:/A:` 05-09 | extends ch4 exclusion-needs-cause to graphs |
| Interpolation with an honest "about" | `Q:/A:` 05-10 | midway reading between 2 and 4 coins |
| Extrapolation and its weakening support | `Q:/A:` 05-11 | plant-growth contrast; bounded-conclusion echo |
| Axis-start artifact: read scale, not steepness | `Q:/A:` 05-12 | figure card (same data, two axes) |
| Table versus graph display choice | `Q:/A:` 05-13 | method-choice target |
| Analyzed table-pattern + interpolation | `P:/S:` 05-14 | full IPEE on the water-depth table |
| Faded graph interpolation | `P:/S:` 05-15 | thin support in all four stages; per-coin check |
| Independent mixed display audit | `P:/S:` 05-16 | four flaws: scale, dot-to-dot, chased anomaly, certain extrapolation |

Cloze count is zero by design (as planned): every target is a discrimination,
diagnosis, prediction, or method execution; no compact token merits exact
recall. Problem progression: analyzed (05-14) → faded (05-15) → independent
mixed audit (05-16), preceded by supported single-step retrievals.

### Chapter 5 figure opportunity inventory

| Opportunity | Decision | Retrieval role or reason |
|---|---|---|
| Coin-mass scatter graph with one circled point and guides | Include: `coin-mass-graph` (fronts of 05-05, 05-07, 05-15) | reading a point against two scales and judging a trend are spatial tasks; a printed table would delete them |
| Same points joined dot-to-dot versus one trend line | Include: `line-treatments` (front of 05-08) | the choice between treatments must be inspected; prose would state the difference it means to test |
| Same four readings on a 0-based and a zoomed axis | Include: `axis-start-comparison` (front of 05-12) | the conflicting visual impressions are the phenomenon under audit |
| Flawed graph with uneven scale, dot-to-dot line, chased anomaly | Include: `flawed-graph` (front of 05-16) | the audit requires spotting flaws in an actual drawn display, not a described one |
| Empty labeled axes as a plotting scaffold | Omit | plotting-by-hand belongs to notebook practice; the scheduling decision (axis roles) is 05-04's verbal target |
| Interpolation zoom-in construction | Omit | the midway reading is arithmetic once the trend is trusted; a construction drawing would restate the answer |
| Residual-style difference plot | Omit | planned early as "residual-like"; successive differences in the 05-03/05-14 tables carry the same decision at novice depth without new graph grammar |

### Chapter 5 planned versus actual inventory

| Chapter | Basic `Q:/A:` | Cloze `C:` | Problem `P:/S:` | Figures | Reconciliation |
|---|---:|---:|---:|---:|---|
| 5 planned | 13 | 0 | 3 | 4 front figures, TikZ + SVG | baseline for the chapter-5 isolated build |
| 5 actual | 13 | 0 | 3 | 4 front figures, TikZ + SVG | matched; validator total 35 deck cards = 19 (ch4) + 16 (ch5); no unexplained omission |

## Chapter 6 design ledger (proportional reasoning and scaling)

Allowed inbound frontier: Chapter 5 scheduled cards (tables, independent/
dependent quantities, successive differences, axes, data points, trends,
trend lines, anomalies, interpolation/extrapolation, axis-start artifacts,
display choice), capability summaries for Chapters 1–4 (quantity-value terms;
SI units and conversion; procedure, resolution, false precision; repeat
variation, mean, uncertainty, random/systematic error), the scheduled external
arithmetic closure (ratio, rate, proportional-relationship names; fractions,
decimals, percent; measurement units via the fully staged arithmetic
chapter 10), and the algebra capability summary (variable, equation,
substitution, evaluating an expression). "Slope" is *not* used — Chapter 5
established "steepness" only. Symbolic per-unit notation (mL/s) waits for
Chapter 7; per-unit values are spelled out ("grams per coin"). "Origin" is
bridged on the front that first needs it.

| Target | Form | Ledger note |
|---|---|---|
| Direct proportion: doubling test, zero-together | `Q:/A:` 06-01 | coin-mass table from ch5 reused |
| Constant of proportionality as a per-unit value | `Q:/A:` 06-02 | ratio test on the same table |
| Proportion equation and substitution prediction | `Q:/A:` 06-03 | m = 5.2 n; algebra summary supplies substitution |
| Exact form y = kx | `C:` 06-04 | one deletion, after 06-03 establishes the equation |
| Graph signature: straight line through the origin | `Q:/A:` 06-05 | figure card; "origin" bridged on the front |
| Steady rise with a nonzero start is not proportional | `Q:/A:` 06-06 | jar-plus-coins trap; doubling test fails |
| Scale factor as a multiplier within a relationship | `Q:/A:` 06-07 | water-depth table ×1.25, inside measured range |
| Scaled drawing: one factor for every length | `Q:/A:` 06-08 | figure card; door 200×80 cm → 10 cm tall |
| Ratio invariance under scaling | `Q:/A:` 06-09 | 200:80 = 10:4 = 2.5; shape preservation |
| Inverse proportion: one doubles, the other halves | `Q:/A:` 06-10 | ribbon-sharing context |
| Constant-product test for inverse proportion | `Q:/A:` 06-11 | 600 mL fill; products all 600 |
| Falling is not enough: inverse versus mere decrease | `Q:/A:` 06-12 | figure card; products 60,90,60 versus 60,60,60 |
| Wobble versus drift in a ratio list | `Q:/A:` 06-13 | ch4 repeat-variation logic applied to ratios |
| Analyzed proportional-data test and prediction | `P:/S:` 06-14 | full IPEE on a paper-stack table |
| Faded scale-factor enlargement | `P:/S:` 06-15 | photo 10×15 → 25 cm wide; thin support |
| Independent mixed discrimination and claim repair | `P:/S:` 06-16 | direct, nonzero-start, inverse, and a flawed claim |

Cloze count is one by design: y = kx is the chapter's only compact
exact-recall token; every other target is a discrimination, prediction,
diagnosis, or method execution. Problem progression: analyzed (06-14) →
faded (06-15) → independent mixed (06-16), preceded by supported
single-step retrievals.

### Chapter 6 figure opportunity inventory

| Opportunity | Decision | Retrieval role or reason |
|---|---|---|
| Three rising graphs: through-origin straight, nonzero-start straight, steepening curve | Include: `rising-graph-shapes` (front of 06-05) | picking the proportional signature out of near-neighbors is a visual discrimination; prose would state the answer |
| Real door beside its scale drawing with dimension arrows | Include: `scaled-door-drawing` (front of 06-08) | the two-object correspondence and the unknown width are spatial; the deliberate not-to-scale note keeps the artwork from leaking the factor |
| Two falling graphs with labeled values | Include: `falling-graph-shapes` (front of 06-12) | inverse-versus-merely-decreasing must be tested from labeled values on curves, not asserted |
| Double number line for scale factors | Omit | the arithmetic deck's conversion-map grammar already covers paired-scale reasoning; no new scheduling decision here |
| Proportional versus nonproportional table image | Omit | markdown tables are inbound from ch5 and carry the same decision without an image |

### Chapter 6 planned versus actual inventory

| Chapter | Basic `Q:/A:` | Cloze `C:` | Problem `P:/S:` | Figures | Reconciliation |
|---|---:|---:|---:|---:|---|
| 6 planned | 12 | 1 | 3 | 3 front figures, TikZ + SVG (≤4 allowed) | baseline for the chapter-6 isolated build |
| 6 actual | 12 | 1 | 3 | 3 front figures, TikZ + SVG | matched; 16 new cards; double-number-line figure intentionally omitted |

## Chapter 7 design ledger (dimensions and derived quantities)

Allowed inbound frontier: Chapter 6 scheduled cards (direct/inverse
proportion, constant of proportionality, y = kx, substitution prediction,
scale factor, constant-product test, per-unit values spelled out in words),
capability summaries for Chapters 1–5 (quantity-value terms, measurand,
SI units and conversion, resolution, mean and uncertainty, tables and
graphs), and the external arithmetic and algebra closures (ratio, rate,
unit rate, fractions and decimals, whole-number powers, array
representation, variable, equation, substitution). Symbolic slash
notation (mL/s) is introduced here, as reserved by the Chapter 6 ledger.
Area and volume units are *not* inbound (no geometry deck edge); cm² and
cm³ are built from unit-square and unit-cube counting bridged from
array representation and whole-number powers. "Dimension" is explicitly
disambiguated from Chapter 1's drawing-dimension arrows. Density is
in scope (not on the exclusion list); force, energy, and motion
vocabulary stay out.

| Target | Form | Ledger note |
|---|---|---|
| Derived quantity; mL/s slash notation | `Q:/A:` 07-01 | 90 mL in 30 s → 3 mL/s; first symbolic per-unit unit |
| Unit cancellation in rate × time | `Q:/A:` 07-02 | 3 mL/s × 40 s → 120 mL; s cancels |
| Unit of a proportionality constant | `Q:/A:` 07-03 | d = kV → cm/mL; bare counts carry no unit (m = 5.2 n) |
| Density as a derived quantity | `Q:/A:` 07-04 | mass ÷ volume; water about 1.0 g/mL |
| Area unit cm² from unit-square counting | `Q:/A:` 07-05 | figure card; 4 cm × 3 cm tile → 12 cm² |
| Volume unit cm³ from unit-cube layers | `Q:/A:` 07-06 | figure card; 4 × 3 × 2 → 24 cm³ |
| 1 mL = 1 cm³ exact link | `Q:/A:` 07-07 | 250 mL carton → 250 cm³ |
| Exact form 1 cm³ = 1 mL | `C:` 07-08 | one deletion, after 07-07 establishes the link |
| Squared conversion factor 1 m² = 10 000 cm² | `Q:/A:` 07-09 | figure card; (100 cm)² reasoning against the ×100 trap |
| Dimension as kind of quantity | `Q:/A:` 07-10 | 3 m = 300 cm reachable, 3 m² not; disambiguates drawing "dimensions" |
| Same-dimension addition rule | `Q:/A:` 07-11 | 1.2 m + 30 cm fixable; 5 g + 20 mL meaningless; division fine |
| Same unit, different quantity | `Q:/A:` 07-12 | ruler resolution 1 mm versus seed length 1 mm; measurand |
| Unit check rejects a wrong equation | `Q:/A:` 07-13 | t = V × r gives mL²/s, not s; repair V ÷ r |
| Unit check can only reject, never confirm | `Q:/A:` 07-14 | t = V/r and t = 2V/r both pass the check |
| Analyzed two-reading density determination | `P:/S:` 07-15 | full IPEE; 176 g − 84 g over 100 mL → 0.92 g/mL, not water |
| Faded rate-time prediction with unit conversion | `P:/S:` 07-16 | 2.5 mL/min for 1.5 h → 225 mL; h → min inside the chain |
| Independent equation screening by units | `P:/S:` 07-17 | three candidates, only t = V ÷ r survives; ch6 600 mL data as support |
| Mixed false-positive claim check | `P:/S:` 07-18 | unit-rejected pure number, surviving cm/mL, and a dimensionally clean formula that fails the data |

Cloze count is one by design: 1 cm³ = 1 mL is the chapter's only compact
exact-recall token; every other target is a construction, discrimination,
diagnosis, or method execution. Problem progression: analyzed (07-15) →
faded (07-16) → independent (07-17) → mixed false-positive (07-18),
with 07-18 enforcing the check-rejects-but-never-confirms limit on data.

### Chapter 7 figure opportunity inventory

| Opportunity | Decision | Retrieval role or reason |
|---|---|---|
| Rectangle tiled by unit squares with a shaded corner square | Include: `area-unit-squares` (front of 07-05) | counting squares to build cm² is spatial; the shaded 1 cm × 1 cm anchor is the point of the card |
| Oblique box packed with unit cubes, one shaded | Include: `volume-unit-cubes` (front of 07-06) | layer structure (4 × 3 per layer, 2 layers) must be seen, not asserted |
| Square meter with an exaggerated 1 cm square in one corner | Include: `square-meter-grid` (front of 07-09) | the 100 × 100 mismatch of scale is the visual argument against the ×100 trap |
| Unit-cancellation map with struck-through units | Omit | cancellation is typographic; KaTeX strike-through in the answer carries it without an image |
| Dimension tree (length/volume/time/mass) | Omit | classification is verbal; a tree would state the answer on the front |
| Competing candidate equations laid out side by side | Omit | plain text in the P: block is the working format the learner will actually face |

### Chapter 7 planned versus actual inventory

| Chapter | Basic `Q:/A:` | Cloze `C:` | Problem `P:/S:` | Figures | Reconciliation |
|---|---:|---:|---:|---:|---|
| 7 planned | 13 | 1 | 4 | 3 front figures, TikZ + SVG (≤4 allowed) | baseline for the chapter-7 isolated build |
| 7 actual | 13 | 1 | 4 | 3 front figures, TikZ + SVG | matched; 18 new cards; cancellation-map, dimension-tree, and equation-layout figures intentionally omitted |

## Chapter 8 design ledger (estimation and order of magnitude)

Allowed inbound frontier: Chapter 7 scheduled cards (mL/s slash notation,
unit cancellation, density with water about 1.0 g/mL, cm² and cm³,
1 mL = 1 cm³, 1 m² = 10 000 cm², two-reading method, unit check rejects
but never confirms), capability summaries for Chapters 1–6 (quantity
values, measurand, SI units and prefixes, resolution, rounded-value
intervals, mean and uncertainty interval, tables and graphs, direct
proportion and scale factor), and the external arithmetic and algebra
closures — in particular whole-number powers and the Chapter 10
arithmetic benchmarks (door handle ~1 m, fingernail ~1 cm, paper clip
~1 g, textbook ~1 kg, bottle ~1 L, spoon ~5 mL, bathtub ~200 L, ten
city blocks ~1 km, 60 s/min, 60 min/h). Scientific notation and
negative exponents are *not* inbound: powers-of-ten form is taught here
only for values at or above one, with whole-number exponents; sub-unit
sizes ride on inbound prefixes (mm, cm). The order-of-magnitude
boundary near 3 is bridged as "3 × 3 ≈ 10" because square roots are not
inbound. "Estimate" is explicitly contrasted with Chapter 4's measured
uncertainty interval: bounds here come from anchored judgment, not from
spread in repeated readings.

| Target | Form | Ledger note |
|---|---|---|
| Estimate versus unanchored guess; reference value | `Q:/A:` 08-01 | corridor from 3 door-widths; every estimate names its anchor |
| Reference-based single-step estimate | `Q:/A:` 08-02 | figure card; 5 floors × door ≈ 2 m → building ≈ 15 m |
| Decomposition into easier factors | `Q:/A:` 08-03 | 2.0 m paper stack; 500 sheets per 5 cm → 20 000 sheets |
| Diagnosing a useless decomposition | `Q:/A:` 08-04 | coin jar; renaming the unknown is not decomposing it |
| Leading digit × power of ten form | `Q:/A:` 08-05 | 20 000 = 2 × 10⁴; read 7 × 10³ back as 7000 |
| Order of magnitude; the ~3 boundary | `Q:/A:` 08-06 | 200 → 10², 40 000 → 10⁵; 3 × 3 ≈ 10 bridge |
| Counting orders on a scale ladder | `Q:/A:` 08-07 | figure card; fingernail (1 cm) to city block (100 m) = 4 steps |
| Lower and upper bounds from anchors | `Q:/A:` 08-08 | car 3–6 m via door comparisons; contrast with ch4 interval |
| Overconfident versus honest bracket | `Q:/A:` 08-09 | figure card; narrow 5.8–6.2 fails at 6.9 m, wide 4–8 holds |
| Propagating bounds through a product | `Q:/A:` 08-10 | 180 × 80 and 220 × 120 → 14 000–26 000, one order 10⁴ |
| Estimate-driven decision robustness | `Q:/A:` 08-11 | worst case 18 × 25 cm = 4.5 m still fits the 5 m roll |
| Honest precision in reporting | `Q:/A:` 08-12 | calculator 3061.224… → report about 3 × 10³ |
| Reporting assumptions with the estimate | `Q:/A:` 08-13 | two pinned versions; an estimate is a small model |
| Order-of-magnitude audit of a claim | `Q:/A:` 08-14 | barrel 20 000 L vs bathtub 200 L → two orders → reject; audit rejects, never confirms |
| Analyzed anchored mass estimate | `P:/S:` 08-15 | full IPEE; bathtub 200 L → 200 000 mL × 1.0 g/mL → about 200 kg, bracket 150–300 kg |
| Faded rate decomposition over a day | `P:/S:` 08-16 | 15/min × 1440 min → about 2 × 10⁴ breaths; bracket 12–18/min |
| Independent decomposition with bounds | `P:/S:` 08-17 | 300 books × 3 cm (2–5 cm) → 9 m shelf run, bracket 6–15 m; inverse check |
| Mixed strategy comparison | `P:/S:` 08-18 | anchored 9 × 10⁴ versus bare "a million"; one order apart; trust the anchored chain |

Cloze count is zero by design: every chapter target is a judgment,
construction, diagnosis, or multi-step procedure, and the only compact
tokens in reach (10³ = 1000 and the everyday benchmarks) are inbound
arithmetic capabilities, not new facts owed a deletion card. Problem
progression: analyzed (08-15) → faded (08-16) → independent (08-17) →
mixed strategy discrimination (08-18), with 08-18 also exercising the
audit-rejects-never-confirms limit against a rival estimate.

### Chapter 8 figure opportunity inventory

| Opportunity | Decision | Retrieval role or reason |
|---|---|---|
| Five-story building with an unlabeled street door | Include: `building-floors` (front of 08-02) | reading a size off a visible reference is spatial; printing any number would leak the anchor step |
| Powers-of-ten scale ladder with two marked rungs | Include: `scale-ladder` (front of 08-07) | counting equal ×10 steps between marked rungs is the retrieval act; shape-coded markers give a non-color cue |
| Two bounding brackets against a tape-measure dot | Include: `bracket-comparison` (front of 08-09) | containment versus miss must be seen on a common number line to make overconfidence concrete |
| Decomposition tree for a factor chain | Omit | the authentic working format is the written factor chain with unit cancellation from Chapter 7; a tree adds no spatial content |
| Photographs of reference objects | Omit | benchmarks are inbound as verbal anchors; no exact-geometry or scale-critical target requires raster imagery |

### Chapter 8 planned versus actual inventory

| Chapter | Basic `Q:/A:` | Cloze `C:` | Problem `P:/S:` | Figures | Reconciliation |
|---|---:|---:|---:|---:|---|
| 8 planned | 14 | 0 | 4 | 3 front figures, TikZ + SVG (≤4 allowed) | baseline for the chapter-8 isolated build |
| 8 actual | 14 | 0 | 4 | 3 front figures, TikZ + SVG | matched; 18 new cards; decomposition-tree and photograph figures intentionally omitted |
