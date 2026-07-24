+++
order = 3
subject = "physics"
authoring_model = "claude-fable-5"
authoring_reasoning_effort = "high"
tags = ["physical-reasoning", "measurement-procedures", "scale-reading", "resolution", "instrument-choice"]
prerequisites = ["chapter:02_si_units_and_quantity_values"]
provides = [
  "measurement-procedure",
  "scale-division",
  "zero-error",
  "parallax-error",
  "resolution",
  "digital-resolution",
  "false-precision",
  "instrument-range",
  "instrument-choice",
]
+++

# Measurement procedures and resolution

## Specifying the how

<!-- card-id: b4e29c71-8a3d-4f56-9e12-c7a05d84f631 -->
Q: Chapter 1 defined a measurand by naming the object, the property, and the relevant conditions — *what* is to be measured. Knowing the measurand still leaves open *how* the value is obtained. A **measurement procedure** is the recipe that fixes the how: which instrument to use, how instrument and object are placed together, where the reader's eye goes, and how the reading is recorded. Two students share one fully specified measurand — "the length of this table along its longer edge" — and one ruler, yet they can still obtain different values. What does that show the measurand alone does not fix?
A: The procedure. The measurand names what is measured but not how: instrument placement, alignment with the edge, eye position, and the recording rule are all left open, and different choices there shift the value. A complete measurement needs a specified measurand *and* a specified procedure.

<!-- card-id: 7d3f8a25-1c69-4b84-a7f3-52e91c06d8b7 -->
Q: Compare two instructions for the same measurand, a potted plant's height: (a) "measure how tall the plant is"; (b) "stand the pot on a flat floor, hold the ruler upright beside the stem with its zero mark at the floor, and read the mark level with the highest leaf tip." Which instruction is a measurement procedure, and what test decides?
A: Only (b). The test is repeatability: a procedure fixes the instrument, the placement, and the reading rule so completely that a different person following it on the same measurand should obtain nearly the same value. Instruction (a) leaves every one of those choices open.

## Reading a marked scale

<!-- card-id: 2f6b4d93-9e17-4a52-b8c6-04d7f3a92e58 -->
Q: A measuring tool's scale carries labeled marks with equal small steps between them. The gap from one mark to the next is a **scale division**, and its value is found from the labels: divide the difference between neighboring labeled values by the number of steps between them. A container's scale is labeled every 50 mL, with five equal steps from one label to the next. What is each division worth?
A: Each division is worth **10 mL**, because \(50 \div 5 = 10\). Every unnumbered mark's value then follows by counting divisions from the nearest label — the labels give the anchors, and the division size gives the steps.

<!-- card-id: 9a5c7e14-6f28-4d91-83b5-e70a2c94f16d -->
Q: The usual ruler procedure aligns one end of the object with the zero mark and reads the other end. When the zero mark cannot be used — a damaged ruler end, or an object lying mid-scale — there is a substitute: take a reading at *each* end of the object and subtract. A rod lies along a ruler with its left end at the 3.0 cm mark and its right end at the 9.5 cm mark. What is the rod's length, and why does this method not need the zero mark at all?
A: The rod is **6.5 cm** long: \(9.5 - 3.0 = 6.5\). A length is a difference between two scale positions, so any starting mark works — the subtraction cancels wherever the rod happens to start, and the zero mark loses its special role.

<!-- card-id: 5e8d2b47-3a96-4c15-9f4e-b81c6d05a273 -->
Q: The tip of a ruler has broken off: everything before the 0.2 cm mark is gone, so the ruler's physical edge now falls exactly at the 0.2 cm position. A student, not noticing, presses this edge against one end of a rod and treats the scale reading at the rod's other end as its length. An instrument fault like this, which shifts *every* reading by the same fixed amount, is a **zero error**. Is the student's result too large or too small, by how much, and what procedure removes the error without repairing the ruler?
A: Too large by 0.2 cm — the rod's near end actually sits at the 0.2 cm position, so the far-end reading is the true length plus 0.2 cm. The two-reading method removes it: read both ends and subtract, and the constant shift cancels out.

<!-- card-id: c1a94f68-7d25-4e83-b6f9-38e50a7c12d4 -->
Q: A pointer — the needle or edge that indicates the value on a scale — often sits a small distance in front of the scale rather than touching it. The figure shows the tip of such a pointer above a scale, sighted from three eye positions; each dashed line of sight passes through the pointer tip and continues until it meets the scale.

![A horizontal scale with labeled marks at twenty, thirty, and forty and equal small steps between them. The tip of a pointer floats a short distance above the scale, directly over the thirty mark. Well above the scale sit three eye positions: one to the left, one directly above the pointer tip, and one to the right. From each eye a dashed sight line passes through the pointer tip and continues down to the scale, meeting it at three different points labeled a, b, and c from left to right.](../figures/03_measurement_procedures_and_resolution/parallax-views.svg)

Because the pointer floats in front of the scale, the mark that *appears* aligned with it depends on where the eye is — a **parallax error**. Which sighted point is the correct reading, and is the value seen by the left-hand eye too high or too low?
A: Point **b**, seen from the eye directly above the pointer: only a line of sight square to the scale meets it at the pointer's true position. The left eye's sight line slants rightward through the tip and lands past it at c, a too-high value; the right eye errs low at a. A careful procedure therefore places the eye directly in front of the pointer, perpendicular to the scale.

## Resolution

<!-- card-id: e7b25c94-4f81-4d36-a2c8-91f4e6b07d35 -->
Q: Different instruments answer the same question with different fineness. **Resolution** is the smallest difference in the measured quantity that an instrument can actually show. On a marked scale the divisions set it: positions are reported by their nearest mark. One ruler has marks only at whole centimeters; another adds marks at every millimeter. Two bolts differ in length by 3 mm. Which ruler reliably shows that the bolts differ, and why is the other unreliable for that job?
A: The millimeter ruler — its divisions are smaller than the 3 mm difference, so the two bolt ends reach different nearest marks. On the centimeter ruler a 3 mm difference is smaller than one division, so the two bolts will often share the same nearest mark and read as equal; whether the difference ever shows depends on where the ends happen to fall, not on the instrument detecting it.

<!-- card-id: 4c8e6a31-2b57-4f94-8d1a-c5f39e28b746 -->
Q: A digital instrument displays its value directly as digits, and the display changes in jumps: the last displayed place moves in steps of one, and nothing smaller can appear. Its resolution is the step of that last place. A digital balance — an instrument that measures mass — shows 12.47 g. State its resolution, and describe what the display does if the mass on it increases by only 0.002 g.
A: The resolution is **0.01 g**, one step in the last displayed place. A 0.002 g increase is smaller than one step, so the display usually stays at 12.47 g; only if the true value was already near a step boundary can it tick once to 12.48 g. Either way the display can never show the change in finer detail than its last digit.

<!-- card-id: a9f47d82-5e63-4b19-b3d7-620c8f45e9a1 -->
Q: A student compares a needle balance, whose pointer can rest anywhere between two marks, with a digital balance showing crisp digits, and concludes: "the digital one is exact; the needle one is approximate." What is wrong with this conclusion?
A: Both are approximate. The digital display reports the value only to the nearest step of its last digit, so the true mass lies somewhere within that step — the display hides the in-between instead of showing it. Crisp digits mean the *display* moves in jumps, not that the mass is known exactly; no instrument reads with unlimited fineness.

## Honest recording

<!-- card-id: 6d2a9e57-8c14-4f72-95b8-d3e60a71f428 -->
Q: A recorded value should claim exactly as much fineness as the instrument delivered: record the reading to the instrument's resolution — the nearest division — and no further. A bolt is measured on a ruler with millimeter divisions, and its end lies nearest the 34 mm mark. Which written report matches the procedure — 34 mm, 34.0 mm, or 34.00 mm — and what do the other two wrongly claim?
A: Report **34 mm**. A written measurement's last place claims its precision: 34.0 mm claims a reading to tenths of a millimeter, and 34.00 mm to hundredths — fineness a millimeter-division ruler never delivered. The report should stop where the instrument stops.

<!-- card-id: 3b7f5c28-9a46-4d15-a6e2-84b09c37f5d6 -->
Q: Digits can outrun knowledge when arithmetic manufactures them. A board is measured with a centimeter-division tape — a flexible ruler — as 100 cm, and it must be cut into three equal shelves. A calculator gives \(100 \div 3 = 33.333\ldots\), and a student records each shelf as "33.333 cm." A report whose written fineness exceeds what was measured shows **false precision**. Why are the trailing 3s not real measurement information, and what report is honest?
A: The board's length is known only to the nearest centimeter, so a third of it cannot be known to a thousandth of a centimeter: the extra digits came from the division, not from any comparison with the board. An honest report stays at the input's fineness — about **33 cm** per shelf — because no calculation can make a result finer than the measurement it started from.

## Choosing an instrument

<!-- card-id: f5c31e86-2d79-4a48-b1c5-96e42d07a8f3 -->
Q: Besides resolution, an instrument has a **range**: the span of values it can measure at all, from the smallest to the largest. A room's width, roughly 4 m, must be measured. Available: a 30 cm ruler with millimeter divisions, and a 5 m measuring tape, also with millimeter divisions. The ruler's divisions are just as fine — so why is the tape still the better instrument here?
A: Because of range: the room is far longer than the ruler, so the ruler would have to be laid down end over end a dozen times, and every repositioning is a fresh chance of misalignment — small errors that add up. The 5 m tape covers the whole width in one placement, one alignment, one reading. Prefer an instrument whose range covers the measurand in a single use.

<!-- card-id: 8e4b7f13-6c92-4a57-88d4-1f7a3e65c9b2 -->
Q: An instrument suits a task only if its resolution is fine enough for the decision the value must support. A kitchen balance shows mass in steps of 1 g. Two tasks: (a) weigh out about 250 g of flour, where being off by a few grams changes nothing; (b) find the mass of a single vitamin tablet of well under 1 g. Which task can this balance serve, and why does it fail the other?
A: It serves task (a): 1 g steps easily support a decision that tolerates a few grams either way. It fails (b): the whole tablet is smaller than one display step, so the balance would show 0 g or 1 g — no useful value at all. Match the resolution to the fineness the purpose actually needs.

## Problems

<!-- card-id: d6a83f29-4e57-4b16-9a3d-c72e08d5f194 -->
P: The figure shows a metal rod lying along a ruler whose labeled marks are centimeters, with millimeter divisions between them. The rod does not touch the ruler's zero mark. Find the rod's length and record it as the instrument supports.

![A metal rod drawn as a shaded bar lying just above a ruler scale. The ruler's labeled marks run from two to eight centimeters with ten small millimeter steps between neighboring labels. The rod's left end is aligned with the labeled 2 mark, and its right end lies between the labeled 7 and 8 marks, four small steps past the 7.](../figures/03_measurement_procedures_and_resolution/ruler-offset-reading.svg)

S: **IDENTIFY:** A length measurement by the two-reading method: the rod lies mid-scale, so its length is the difference between the scale readings at its two ends. The divisions are millimeters — 0.1 cm — which sets both the reading fineness and the honest report.

**PLAN:** Read each end to the nearest division, subtract the smaller reading from the larger, and record the result to the millimeter, the ruler's resolution.

**EXECUTE:** The rod is **5.4 cm** long. Its left end reads 2.0 cm and its right end reads 7.4 cm — four divisions of 0.1 cm past the 7 mark — so its length is \(7.4 - 2.0 = 5.4\text{ cm}\).

**EVALUATE:** A count agrees: the 2 mark to the 7 mark spans 5 whole centimeters, plus four millimeter divisions gives 5.4 cm. The report matches the instrument: written to tenths of a centimeter, exactly one ruler division, with no invented finer digits.

<!-- card-id: 1c9e5b74-7f38-4d62-b5f1-a08d4c26e7b9 -->
P: A container's printed scale is labeled every 10 mL, with five equal divisions between neighboring labels. The liquid's level is read with the eye directly in front of it. What volume does the scale show, and to what fineness should it be recorded?

![An upright vessel holding shaded liquid. Along its side runs a vertical scale labeled from zero to eighty milliliters at every ten, with five equal small steps between neighboring labels. The flat top surface of the liquid lines up with the second small mark above the sixty label.](../figures/03_measurement_procedures_and_resolution/volume-scale-reading.svg)

S: **IDENTIFY:** A scale reading: label anchors plus counted divisions, with the division size setting the resolution.

**PLAN:** Find the division size from the labels, then count divisions from the last label below the liquid's level.

**EXECUTE:** The scale shows **64 mL**, recorded to the nearest 2 mL: each division is worth \(10 \div 5 = 2\text{ mL}\), and the level sits two divisions above the 60 label, so \(60 + 2 \times 2 = 64\text{ mL}\).

**EVALUATE:** The level lies below the halfway point between 60 and 70, and 64 is indeed below 65 — consistent. A report such as 64.0 mL would claim tenths this scale cannot show.

<!-- card-id: 07f6d8a3-5b29-4c81-92e6-4dbf17a35c68 -->
P: A student measures a window's width to order a curtain rod, using a 3 m measuring tape with centimeter divisions. The tape's end piece is bent, so the tape cannot be trusted near its zero mark. The student nonetheless presses the bent end against the window's left edge, stands off to one side while sighting where the right edge crosses the tape, reads 142 cm there, and reports the width as "1.42000 m." Identify every procedure and reporting error, and state how to fix each.

S: **IDENTIFY:** A procedure audit: each stage of the measurement — instrument condition, placement, eye position, and the written report — must be checked against the rules for trustworthy readings.

**PLAN:** Follow the measurement in order — zero end, then sighting, then the recorded value — and match each fault found to its fix.

**EXECUTE:** There are **three errors**. First, a zero error: starting from the bent end shifts every reading by an unknown amount, so the original 142 cm cannot yet be accepted as the width — fix it with the two-reading method, aligning the left edge with a clear mark such as 10 cm and subtracting the two scale readings. Second, a parallax error: sighting the right edge from off to one side makes the mark that appears aligned depend on the eye's position — fix it by reading with the eye directly in front of that edge, square to the tape. Third, false precision: 1.42000 m claims fineness a centimeter-division tape never delivered — record the corrected result only to the nearest centimeter (equivalently, to hundredths of a meter).

**EVALUATE:** Each fix ties an error to its rule: subtraction cancels a constant zero shift, a square line of sight lands on the true mark, and the report's last written place matches the centimeter division. The corrected width should also be checked against the rough expectation of a window a little wider than a meter and against the tape's 3 m range.
