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

The declared algebra deck is the machine-readable prerequisite, but its staged
copy contains no scheduled cards. The pilot therefore uses only elementary
comparisons and arithmetic that are explicitly visible in the scheduled
transitive arithmetic closure. It does not assume symbolic-function vocabulary.

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
| Number comparison, multiplication, decimals, `<`, and units | 01-06, 01-07, 01-14, 01-17, 01-18 | Scheduled arithmetic closure: whole-number comparison, multiplication, decimals, and `measurement-estimation-and-decisions` | Inbound | 01-07, 01-14, 01-17, 01-18 | confirmed inbound |
| IPEE problem headings | 01-18 back only | Repeatedly established in scheduled arithmetic problem cards | Inbound | 01-18 | confirmed inbound |
| System; system boundary; surroundings | 01-01 onward | 01-01 front defines all three in ordinary language | 01-01 | 01-02, 01-03, 01-11, 01-17, 01-18 | established |
| Dashed candidate-boundary loops and option labels | 01-02 | 01-02 front explains the diagram grammar before asking for a choice | 01-02 | Future system diagrams | established |
| Property and physical quantity | 01-04 onward | 01-04 front contrasts a general feature with a feature that has comparable size/amount and a number plus reference | 01-04 | 01-05 through 01-09, 01-17, 01-18 | established |
| Quantity value; number–unit pairing | 01-05 onward | 01-05 front distinguishes the quantity from a value used to express it | 01-05 | 01-06, 01-07, 01-17, 01-18 | established |
| Unit as agreed reference; measurement as experimental comparison | 01-06 onward | 01-06 front supplies the bridge; arithmetic closure already establishes measurement and unit operationally | 01-06 | 01-07 through 01-09, 01-15 through 01-18 | established |
| Same quantity expressed in different units | 01-07 | 01-07 front gives an equivalent-unit example | 01-07 | Chapters 2 and 7 | established |
| Measurand | 01-08 onward | 01-08 front defines it as the particular quantity intended to be measured and specifies object/property/condition | 01-08 | 01-09, Chapters 3–4 | established |
| Descriptive observation versus measurement | 01-09 | 01-09 front explains that an observation may be descriptive while a measurement supplies a quantity value | 01-09 | 01-15, 01-16 | established |
| Physical system versus model; simplification | 01-10 onward | 01-10 front defines a model as a purposeful simplified representation | 01-10 | 01-11 through 01-18 | established |
| Assumption | 01-12 onward | 01-12 front defines it as a condition accepted while using a model | 01-12 | 01-13, 01-17, 01-18 | established |
| Purpose-dependent relevance | 01-13 onward | 01-10 and 01-13 fronts explain that useful details depend on the question | 01-13 | 01-17, 01-18 | established |
| Prediction | 01-14 onward | 01-14 front defines a prediction as the observable or measurable result expected if the model and assumptions apply | 01-14 | 01-15 through 01-18 | established |
| Model test; prediction–observation comparison | 01-15 onward | 01-15 front defines a test through a comparison that could disagree | 01-15 | 01-16, 01-18 | established |
| Mismatch does not identify its own cause | 01-16 onward | 01-16 front supplies the measured and predicted values and asks for the bounded inference | 01-16 | Chapters 4, 5, 9, and 10 | established |
| Dimension arrows and schematic-not-to-scale convention | 01-17 | 01-17 front explicitly explains both cues before asking for a prediction | 01-17 | 01-18 and later technical diagrams | established |
| Straight, upright fit model and scope limit | 01-17 onward | 01-17 front states the rule and assumptions; 01-17 answer models the prediction | 01-17 | 01-18 independent application and evaluation | established |

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

## Planned versus actual inventory

| Chapter | Basic `Q:/A:` | Cloze `C:` | Problem `P:/S:` | Figures | Reconciliation |
|---|---:|---:|---:|---:|---|
| 1 planned | 17 | 0 | 1 | 2 front figures, each with editable TikZ and accessible SVG | baseline |
| 1 actual | 17 | 0 | 1 | 2 front figures, each with editable TikZ and accessible SVG | matched; the analyzed fit appears as a supported basic card before the independent problem |
| 2–10 actual | 0 | 0 | 0 | 0 | intentionally withheld by pilot gate; no unexplained omission |

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
