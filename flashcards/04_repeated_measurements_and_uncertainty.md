+++
order = 4
subject = "physics"
authoring_model = "claude-fable-5"
authoring_reasoning_effort = "high"
tags = ["physical-reasoning", "repeated-measurements", "uncertainty", "random-error", "systematic-error"]
prerequisites = ["chapter:03_measurement_procedures_and_resolution"]
provides = [
  "repeat-variation",
  "reading-dot-plot",
  "measurement-mistake",
  "mean-value",
  "reading-range",
  "measurement-uncertainty",
  "uncertainty-interval",
  "plus-minus-notation",
  "resolution-uncertainty-floor",
  "random-error",
  "systematic-error",
  "result-agreement",
  "uncertainty-for-purpose",
]
+++

# Repeated measurements and uncertainty

## Why careful repeats still differ

<!-- card-id: 3f7a9c52-8e14-4b6d-9a27-c5e80f4d17b3 -->
Q: A student measures one rod's length five times, following the same fully specified procedure each time: the same millimeter-division ruler, the same two-reading method, the same eye position square to the scale. The recorded values are 12.3 cm, 12.4 cm, 12.4 cm, 12.5 cm, and 12.3 cm. Nothing about the rod changed between repeats. This small back-and-forth among honest repeats is called **repeat variation**. Why can all five differing values be faithful readings of one unchanged rod?
A: Because no procedure controls everything perfectly. Each repeat differs in tiny uncontrolled ways — the ruler lies a hair differently against the rod, each end falls between marks and rounds to a different nearest division, the eye shifts minutely — and each such difference nudges the reading up or down by a division or so. The scatter is a normal property of careful measurement, not evidence of carelessness; a single reading merely hides it, giving no hint how much the value would shift on another try.

<!-- card-id: 9b2e6d84-1f57-4c93-8d46-a70b3e59c218 -->
Q: Repeated readings are easiest to judge when displayed. A **dot plot** places one dot above a number line for each reading, at that reading's value; equal readings stack their dots vertically. The figure shows six recorded lengths of one rod.

![A number line of lengths in centimeters running from twelve to thirteen, with labeled marks every two tenths and small unlabeled steps at every tenth. Six dots sit above the line: several gather close together left of the middle, stacking where readings repeat, while one dot sits alone farther to the right.](../figures/04_repeated_measurements_and_uncertainty/repeat-dot-plot.svg)

From the plot, over what interval of values do the readings cluster, and which single reading stands apart from that cluster?
A: The readings cluster from **12.3 cm to 12.5 cm** — five of the six dots crowd there, with 12.4 cm the most frequent value. The reading at **12.9 cm** stands apart, four tenths beyond the cluster's edge.

<!-- card-id: 6c4f8a17-5d92-4e38-b1c6-08f4a25d97e3 -->
Q: Two different things can put a reading away from the others. Repeat variation scatters honest readings over a small band. A **mistake** is different: an identifiable slip in carrying out the procedure — misreading a mark, miscopying a digit, sighting from the wrong place — whose value reports the slip rather than the measurand. Six readings of a rod cluster from 12.3 cm to 12.5 cm, except one reading of 12.9 cm; the student remembers that on that one reading the eye was well off to one side, so the mark that appeared level with the rod's end lay past its true position. What may be done with the 12.9 cm value, and why must the clustered readings all be kept?
A: The 12.9 cm reading may be set aside (or better, retaken), because it has an identified cause — a parallax slip — so it carries information about the slip, not the rod. The clustered values have no such cause: their spread *is* the measurement's normal repeat variation, and dropping any of them would understate the doubt. A reading is never excluded merely for being inconveniently far from the rest; only an identified or strongly suspected slip justifies removal.

## One best value and a size for the scatter

<!-- card-id: e2d75b39-4a86-4f12-9c58-b3d90a67e4f1 -->
Q: Once mistakes are removed, the repeats must still be condensed into one **best value**. The usual choice is the **mean**: add all the kept readings and divide by how many there are. For the kept readings 12.3, 12.4, 12.4, 12.5, and 12.4 cm, compute the mean, and state why it makes a better single value than picking any one reading.
A: The mean is **12.4 cm**: the sum is \(12.3 + 12.4 + 12.4 + 12.5 + 12.4 = 62.0\), and \(62.0 \div 5 = 12.4\). Repeat variation pushes individual readings sometimes high and sometimes low, so in the sum those nudges partly cancel; the mean therefore sits centrally in the cluster, while any single reading might happen to sit at the scatter's edge.

<!-- card-id: 7a1c5e93-6b28-4d74-a3f9-51e604c8b2d7 -->
Q: The size of the scatter deserves a number of its own. The **range of a set of readings** is the largest kept value minus the smallest — not to be confused with an instrument's range, which is the span of values the instrument can measure at all. For kept readings running from 12.3 cm to 12.5 cm, compute the range and half the range, and state what these numbers describe.
A: The range is **0.2 cm** \((12.5 - 12.3)\) and half the range is **0.1 cm**. They describe how widely this measurement's honest repeats scattered — the size of its repeat variation. They say nothing about the instrument's measurable span; that other "range" belongs to the tool, this one to the data.

<!-- card-id: c8e34f61-9d05-4a29-b7e4-2c6f90d135a8 -->
Q: Two students measure the mass of the same steel bolt on the same digital balance, each repeating four times, but following different procedures. The figure shows both sets of readings as dot plots on one shared scale.

![Two aligned dot plots of mass readings in grams, one labeled procedure A above one labeled procedure B, sharing the same horizontal scale with labeled marks every two tenths of a gram and small steps at every tenth. The four dots of procedure A sit close together; the four dots of procedure B, drawn as diamonds, spread across a visibly wider stretch of the scale.](../figures/04_repeated_measurements_and_uncertainty/spread-comparison.svg)

Which procedure shows the larger repeat variation, and what does that imply about trusting a single reading taken with it?
A: Procedure **B** — its readings spread over 0.8 g (44.8 to 45.6 g), four times the 0.2 g spread of procedure A (45.1 to 45.3 g). A single reading from B could therefore sit several tenths of a gram from the best value, while a single reading from A stays within about a tenth: the smaller the scatter, the more repeatable the procedure and the more one reading can be trusted.

## Reporting a result with its uncertainty

<!-- card-id: 4d9b2c78-3e51-4f86-92a4-e7c1058d63b9 -->
Q: A single rounded reading already stands for a whole band of true values, not a point. Repeats sharpen this idea into a reportable one: a complete result pairs the best value with a **measurement uncertainty** — a number stating how far, either way, the true value might reasonably lie from the best value. A simple choice of uncertainty for repeated readings is half their range. The result is written with the sign \(\pm\), read "plus or minus": \((12.4 \pm 0.1)\text{ cm}\). What exactly does the report \((12.4 \pm 0.1)\text{ cm}\) claim about the rod's true length?
A: Under this simple half-range estimate, values from **12.3 cm to 12.5 cm** are treated as reasonably compatible with the measurement — within 0.1 cm on either side of the best value 12.4 cm. That band is the result's **uncertainty interval**. It is an honest summary of the observed repeats and the stated procedure, not a guarantee that the true value lies inside or a claim that one exact value is known.

<!-- card-id: b5f68d24-7c93-4b17-a8d2-90e3f6c45a71 -->
C: A complete repeated-measurement result compresses into one line: best value, then \(\pm\), then a number. In a report such as \((12.4 \pm 0.1)\text{ cm}\), the number after the \(\pm\) sign is the measurement's [uncertainty] — the amount either way, around the best value, within which the true value is believed to lie.

<!-- card-id: 1e8c4a95-2d67-4c38-b9f1-56a80d29e7c4 -->
Q: A bolt's length is measured five times on a ruler with millimeter divisions, and every repeat reads exactly 34 mm — the range of the readings is zero. A student concludes the uncertainty is therefore zero. Why is that wrong, and what is the smallest honest uncertainty here?
A: Each identical reading still only claims the *nearest division*: a true length anywhere between 33.5 mm and 34.5 mm reads as 34 mm, so perfect agreement among repeats cannot make the result finer than the scale. The uncertainty is at least about **0.5 mm** — half a division. Half the range sets the uncertainty only when the scatter is wider than this resolution band; the instrument's fineness is the floor beneath which no amount of agreement can push the doubt.

<!-- card-id: 8f3d6b52-4e19-4d85-a2c7-31b9e604f5d8 -->
Q: A student's kept readings are 12.3, 12.4, 12.4, 12.5, and 12.3 cm. The calculator gives the mean as \(61.9 \div 5 = 12.38\) cm, half the range is 0.1 cm, and the student reports \((12.38 \pm 0.1)\text{ cm}\). What is wrong with this report, and what is the honest version?
A: The best value claims a finer place than the doubt allows: when the uncertainty is a whole tenth of a centimeter, a hundredths digit in the best value is noise — false precision manufactured by the division. Round the best value to the same decimal place as the uncertainty and report \((12.4 \pm 0.1)\text{ cm}\). A result's last written place and its uncertainty must tell the same story about fineness.

## What repetition can and cannot fix

<!-- card-id: 5c2a9e47-8f36-4a91-b4d8-c07e15f3a926 -->
Q: A ruler's broken tip places its physical edge at the 0.2 cm mark, and a student, unaware, presses that edge against the rod's end as if it were zero. Hoping to be careful, the student repeats the reading ten times and averages, reasoning that "averaging removes error." Why does the mean of the ten readings still miss the true length, and by how much?
A: Averaging tames only scatter: nudges that go up on some repeats and down on others partly cancel in the sum. The broken tip instead shifts *every* reading up by the same 0.2 cm, so the shifts add identically and the mean lands exactly 0.2 cm too large. A constant one-way shift survives any amount of repetition; it is removed only by fixing the procedure — here, the two-reading method, whose subtraction cancels the shift.

<!-- card-id: d7b41f85-6c29-4e53-9a86-14d2c8b790e5 -->
Q: The two behaviors of measurement error have standard names. Variation that shifts each repeat differently — sometimes up, sometimes down, with no fixed direction — is **random error**; an effect that pushes every reading the same way by a consistent amount is **systematic error**. Two students repeatedly read the level of liquid against a container's printed scale. Student P's eye lands in a somewhat different position on every reading; student Q always stands the same distance to the left of the level. Classify each student's parallax effect, and name the remedy each one calls for.
A: Student P's effect is **random error** — the apparent mark shifts a different way each repeat, so it scatters the readings and partly cancels in the mean; repetition plus averaging tames it. Student Q's is **systematic error** — always sighting from the left shifts every reading the same way, so the mean is shifted by the same amount and averaging is powerless; only correcting the procedure (eye square to the scale) removes it. The same physical cause becomes either kind depending on how the procedure is carried out.

## Comparing results and serving a purpose

<!-- card-id: 2a6e8c31-9b74-4d16-85f3-e9c40a27d6b8 -->
Q: Two students measure the same rod and report their results on the number line below, each as a dot at the best value with a bar spanning the uncertainty interval.

![A number line of lengths in centimeters from twelve to thirteen with labeled marks every two tenths. Above it sit two results, one over the other: each is drawn as a dot at its best value with a horizontal bar through the dot spanning its interval, the ends of each bar marked by short vertical caps. The lower result is labeled A, twelve point four plus or minus zero point one centimeters; the upper is labeled B, twelve point six plus or minus zero point two centimeters.](../figures/04_repeated_measurements_and_uncertainty/interval-overlap.svg)

Two results **agree** when their uncertainty intervals share at least one common value. Do results A and B agree, and what feature of the plot decides it?
A: **Yes**, they agree: A's interval runs 12.3–12.5 cm and B's runs 12.4–12.8 cm, so the bars overlap between 12.4 and 12.5 cm — lengths that both results allow as the true value. Overlap of the bars is the deciding feature; a visible gap between the bars would mean disagreement.

<!-- card-id: f4c92d68-1a85-4b37-96e2-7d508c3f1ae9 -->
Q: Agreement between two measurement results is a bounded conclusion. What does overlap of two uncertainty intervals actually establish — and why does overlap establish much less when both uncertainties are large?
A: Overlap establishes only *consistency*: given each result's stated doubt, both could be describing the same true value. It does not show the two best values are equal. When uncertainties are large the intervals are wide, so almost any pair of results overlaps and surviving the comparison rules little out; the check has force only when the uncertainties are small. A *gap* is the more decisive outcome: it signals a real difference between the measurands or an unrecognized error somewhere.

<!-- card-id: 9d5f7a23-4c68-4e92-b1a5-38f60d94c7e2 -->
Q: A board is measured as \((75.0 \pm 0.5)\text{ cm}\). It must slide into a slot between two fixed cabinet walls; the slot's width is known far more finely than the board, so treat it as exact. For slot width 76.0 cm, and separately for slot width 75.2 cm, does the result already decide whether the board fits — and what must happen before an undecided case can be settled?
A: For the 76.0 cm slot the result decides: even the largest length in the interval, 75.5 cm, clears 76.0 cm, so the board fits no matter where in the interval the true value lies. For the 75.2 cm slot it does not decide: the interval 74.5–75.5 cm contains lengths that fit and lengths that do not. Settling that case requires a smaller uncertainty — a finer or more careful measurement. An uncertainty is never small "in itself"; it is small enough or not relative to the decision it must support.

## Problems

<!-- card-id: 6b8e2f49-7d13-4a56-98c4-e2a75f08d391 -->
P: A student measures a rod's length six times with the two-reading method on a millimeter-division ruler, recording 12.3, 12.4, 12.4, 12.9, 12.5, and 12.4 cm — plotted in the figure. The student recalls that on the fourth reading the eye was well off to one side of the rod's end. Produce the complete measurement result.

![A number line of lengths in centimeters running from twelve to thirteen, with labeled marks every two tenths and small unlabeled steps at every tenth. Six dots sit above the line: several gather close together left of the middle, stacking where readings repeat, while one dot sits alone farther to the right.](../figures/04_repeated_measurements_and_uncertainty/repeat-dot-plot.svg)

S: **IDENTIFY:** A repeated-measurement summary: screen the readings for mistakes, condense the kept ones into a best value with the mean, size the scatter with half the range, and report best value \(\pm\) uncertainty at a consistent fineness.

**PLAN:** Set aside the reading with the identified slip; average the rest; subtract smallest from largest kept reading and halve it; then write the mean \(\pm\) that half-range, with both numbers ending at the same decimal place.

**EXECUTE:** The result is \((12.4 \pm 0.1)\text{ cm}\). The 12.9 cm reading is excluded — its off-to-one-side sighting is an identified parallax slip. The kept readings 12.3, 12.4, 12.4, 12.5, 12.4 sum to 62.0, giving mean \(62.0 \div 5 = 12.4\) cm; their range is \(12.5 - 12.3 = 0.2\) cm, so the uncertainty is half of that, 0.1 cm.

**EVALUATE:** The mean sits centrally in the plotted cluster, and the interval 12.3–12.5 cm covers every kept reading — as a summary of them should. The excluded value was removed for its identified cause, not for being far away. And the 0.1 cm uncertainty, one ruler division, does not claim fineness below the millimeter divisions — the report is consistent with the instrument.

<!-- card-id: a3c57d91-2e84-4f68-b5d9-06c31e8a94f7 -->
P: A container's scale has 2 mL divisions. Four careful repeated readings of the same volume of liquid, each taken with the eye square to the level, give 62, 64, 64, and 66 mL. No slip is suspected in any reading. Report the measurement result.

S: **IDENTIFY:** A repeated-measurement summary with nothing to exclude: mean, half-range, consistent report.

**PLAN:** Average the four readings; halve the range; write mean \(\pm\) half-range.

**EXECUTE:** The result is \((64 \pm 2)\text{ mL}\): the sum \(62 + 64 + 64 + 66 = 256\) gives mean \(256 \div 4 = 64\) mL, and the range \(66 - 62 = 4\) mL gives half-range 2 mL.

**EVALUATE:** The interval 62–66 mL covers all four readings, the best value's last place (whole milliliters) matches the uncertainty's, and 2 mL equals one scale division — the doubt claimed is exactly as fine as the instrument and scatter support.

<!-- card-id: 0e9a4c86-5b72-4d31-a6f8-93d25c07e1b4 -->
P: Two students measure the mass of the *same* stone on two different balances, each from careful repeats. Student A reports \((78.4 \pm 0.2)\text{ g}\); student B reports \((79.1 \pm 0.3)\text{ g}\). Decide whether the results agree, and state what the outcome tells the students to do.

S: **IDENTIFY:** An agreement check between two reported results for one shared measurand: compare their uncertainty intervals for overlap.

**PLAN:** Turn each report into its interval, look for shared values, and interpret the outcome knowing both results describe one stone.

**EXECUTE:** The results **disagree**: A's interval is 78.2–78.6 g and B's is 78.8–79.4 g, leaving a 0.2 g gap with no value common to both. Since the measurand is one stone, its true mass cannot genuinely differ between them, so the gap signals a hidden problem — most plausibly a systematic error in one procedure (such as a zero error in a balance) or an understated uncertainty.

**EVALUATE:** The gap (0.2 g) remains after both stated uncertainty intervals are included, so the reports are incompatible under their own uncertainty claims. A practical check is to weigh the same object whose mass is already well established on both balances; a constant offset between their readings would expose a systematic shift that no averaging of repeats could remove.

<!-- card-id: 74f1d8a6-3c95-4e27-8b64-d509a2f7c8e3 -->
P: A student measures a board's length five times with a measuring tape whose end piece is bent, each time pressing the bent end against one edge of the board as if it were zero. The readings are 180.3, 180.5, 180.6, 180.5, and 180.9 cm. The student drops the 180.9 cm reading "because it was clearly off," reports \((180.475 \pm 0.15)\text{ cm}\), and adds: "any effect of the bent end averaged out over the five repeats." Identify every error in this treatment, and state how to fix each.

S: **IDENTIFY:** An audit of a repeated-measurement analysis: the exclusion decision, the reported fineness, and the claim about what averaging removed must each be checked against its rule.

**PLAN:** Follow the analysis in order — which readings were kept, how the report was written, what repetition was credited with — and match each fault to its fix.

**EXECUTE:** There are **three errors**. First, an unjustified exclusion: no slip was identified for the 180.9 cm reading, and "clearly off" is not a cause — the reading must be kept (or the measurement retaken); with all five kept, the mean is \(902.8 \div 5 \approx 180.6\) cm and half the range is \((180.9 - 180.3) \div 2 = 0.3\) cm. Second, false precision: 180.475 carries thousandths of a centimeter while the uncertainty spans tenths — the best value must be rounded to the uncertainty's place. Third, a systematic error wished away: the bent end shifts every reading by the same amount, so it cannot average out; the fix is procedural — use the two-reading method from a clear mid-scale mark, then re-form the result, which would otherwise be written \((180.6 \pm 0.3)\text{ cm}\) but remains shifted until the zero error is removed.

**EVALUATE:** Each fix ties to its rule: exclusion demands an identified cause, the report's last places must agree in fineness, and averaging cancels only effects that change direction between repeats. The revised half-range estimate (0.3 cm) is larger than the student's (0.15 cm) — honest doubt grew when the inconvenient reading returned, which is exactly why convenience is not a reason to drop data. The common zero shift is still present until the procedure is corrected.
