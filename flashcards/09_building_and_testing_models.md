+++
order = 9
subject = "physics"
authoring_model = "claude-fable-5"
authoring_reasoning_effort = "high"
tags = ["physical-reasoning", "models", "model-testing", "model-comparison", "model-regime"]
prerequisites = ["chapter:08_estimation_and_order_of_magnitude"]
provides = [
  "quantitative-model",
  "model-parameter-meaning",
  "model-table-test",
  "model-graph-match",
  "representation-consistency",
  "parameter-from-data",
  "model-data-agreement",
  "model-mismatch-diagnosis",
  "model-comparison",
  "prediction-difference-pattern",
  "model-revision",
  "model-regime",
  "impossible-prediction-check",
  "model-purpose-fit",
  "discriminating-test",
]
+++

# Building and testing models

## From verbal rule to quantitative model

<!-- card-id: 3a05b5b4-aa1c-4a09-ab1b-dd29b86140c9 -->
Q: A physical model is a purposeful simplified stand-in for a system, and a genuine test is a comparison the model could lose. A friend offers this model of a burning candle: "While it burns, the candle gets steadily shorter." As stated, this **verbal model** cannot yet produce a single number for a measurement to contradict. What two ingredients must be added to turn it into a **quantitative model** — one that makes numerical predictions?
A: Named **measurable quantities with units** — the candle's remaining length in cm, its burning time in hours — and a **specific relationship between them**, such as "about 2 cm of length is lost each hour." With those two ingredients the model outputs numbers that a measurement can contradict; without them nothing could ever disagree with it, so there is nothing to test.

<!-- card-id: af54c449-ccc4-44bc-a66f-f644107a5844 -->
Q: A 20 cm candle shortens steadily while it burns. Its quantitative model is written as an equation: \(L = 20 - 2t\), with \(L\) the remaining length in cm and \(t\) the burning time in hours. Each number in the equation carries a physical meaning and a hidden unit of its own. State what the constant term 20 and the coefficient 2 each say about the candle, and which unit each must carry.
A: The constant term **20 is the starting length, in cm** — it is what \(L\) equals when \(t = 0\). The coefficient **2 is the shortening rate, in cm/h** — the length lost per hour, subtracted once for every hour that passes. The units are forced: \(2\ \tfrac{\text{cm}}{\text{h}} \times t\ \text{h}\) cancels to cm, and only a cm value can be subtracted from the 20 cm start, since adding or subtracting requires the same dimension.

## One model, several representations

<!-- card-id: badf3659-917a-4d8b-99ac-759d2bd85828 -->
Q: If the steady-shortening model \(L = 20 - 2t\) (\(L\) in cm, \(t\) in h) is right, it leaves a fingerprint in a data table of hourly length measurements. Two candles, both starting at 20.0 cm, were measured:

| \(t\) (h) | Candle X length (cm) | Candle Y length (cm) |
|---:|---:|---:|
| 0 | 20.0 | 20.0 |
| 1 | 18.0 | 18.0 |
| 2 | 16.1 | 16.5 |
| 3 | 13.9 | 15.5 |

What table pattern would support the model, and which candle's data count against it?

A: The fingerprint is **near-equal successive differences — about 2 cm lost every hour**. Candle X supports the model: its hourly drops are 2.0, 1.9, 2.2 cm, wobbling around 2 the way repeated measurements normally do. Candle Y counts against it: drops of 2.0, 1.5, 1.0 cm shrink steadily — a drift, not a wobble — so the "steady rate" assumption itself is failing for Y.

<!-- card-id: 71c60dad-fca2-498a-9277-567402697750 -->
Q: The figure shows three graphs of candle length \(L\) against burning time \(t\), drawn on identical axes. Which panel shows what the model \(L = 20 - 2t\) (\(L\) in cm, \(t\) in h) predicts, and what is wrong with each of the other two?

![Three small graphs of length L in centimeters against time t in hours, labeled panel one, panel two, and panel three. Panel one shows a straight line rising from the origin. Panel two shows a straight line starting at twenty centimeters and falling to zero at ten hours. Panel three shows a curve starting at twenty centimeters that falls steeply at first and then levels off.](../figures/09_building_and_testing_models/equation-graph-panels.svg)

A: Panel **2**: the line starts at 20 cm when \(t = 0\) (the constant term) and falls by the same amount every hour — a straight falling line reaching 0 cm at \(t = 10\) h. Panel 1 rises from the origin, a candle *growing* from nothing. Panel 3 starts right but levels off — its loss per hour keeps shrinking, contradicting the constant 2 cm/h rate.

<!-- card-id: 1a087b72-fe9d-43bb-a77d-8695ab115168 -->
Q: A classmate records a burning candle's length every hour. Their data table shows near-equal drops each hour, but the graph they drew from the *same readings* curves — steep at first, then flattening. What must be true of two faithful representations of the same measurements, and what should be checked first on this graph?
A: They must **tell the same story** — a table with equal steps and an honest graph of those readings must both show a steady trend, so at least one of these two representations is misdrawn. Check the **axis scales first**: an axis whose labels do not advance in equal steps is a broken number line, and it bends genuinely steady data into a fake curve — the familiar graphical artifact. If the scales are true, check the plotted points against the table row by row.

## Fitting and testing against data

<!-- card-id: 34f87020-3193-4a14-a495-58f11e9ae0ca -->
Q: **Fitting** a model means reading its numbers from measured data instead of guessing them. A new, longer candle is measured while burning:

| \(t\) (h) | 0 | 1 | 2 | 3 |
|---|---:|---:|---:|---:|
| \(L\) (cm) | 24.0 | 21.1 | 18.0 | 15.0 |

Assuming the steady-shortening form \(L = \text{start} - \text{rate} \times t\), fit the two numbers, and state which part of the finished model was *assumed* rather than measured.

A: The fitted model is \(\mathbf{L = 24 - 3t}\): the start is the \(t = 0\) reading, 24.0 cm, and the rate comes from the hourly drops 2.9, 3.1, 3.0 — a mean of about 3.0 cm/h. What was assumed is the model's **form** — that the candle shortens at a steady rate at all. The data fitted the numbers, but the steady-rate shape was chosen before fitting, and it remains an assumption the next measurement could still defeat.

<!-- card-id: f8032131-dfd3-45f7-8ddd-eed41593a646 -->
Q: The candle model \(L = 20 - 2t\) (\(L\) in cm, \(t\) in h) is put on trial. Derive its prediction for \(t = 2.5\) h; the measurement at that moment gives \(15.4 \pm 0.5\) cm. Does the model survive, and exactly how is that decided?
A: Prediction: \(L = 20 - 2 \times 2.5 = \mathbf{15.0\ \text{cm}}\). The measured interval runs 14.9–15.9 cm, and 15.0 lies **inside** it, so prediction and measurement agree and **the model survives**. The decision rule: a prediction is compared with the measured *uncertainty interval*, never with the bare central value. And surviving means consistent, not proven — one passed test leaves the model standing, exactly as a passed unit check leaves an equation merely unrejected.

<!-- card-id: 1d7ef124-ca59-4aec-aaea-212284ec8b44 -->
Q: A model's prediction lands far outside the measured uncertainty interval — no overlap at all. Name the three different places this fault can hide, and explain which checks come first and why.
A: The mismatch only localizes the fault to somewhere in the chain: the **derivation** (an arithmetic slip in computing the prediction), the **measurement** (a mistake or a systematic error such as a zero error), or the **model itself** (a failing assumption). Recompute first, then repeat the measurement while checking its procedure, zero or reference, and—when possible—using an independent instrument or method. A systematic fault can survive an unchanged repetition. A mismatch that persists after those checks is evidence against the model or its assumptions; blaming the model immediately risks revising a good model to fit a bad number.

## Competing models and revision

<!-- card-id: 1e16e83d-cfdd-4325-9a33-7150044c09dd -->
Q: Identical cups nest into a stack. Measured stack heights: 2 cups → 11.0 cm, 4 cups → 13.0 cm, 6 cups → 15.0 cm, each good to about ±0.2 cm. The figure shows these points with two candidate model lines: model A, \(H = 2.5n\), proportional through the origin; model B, \(H = 9 + 1.0n\). Which model do the measurements support, and what feature of the data settles the choice?

![Axes with number of cups across and stack height in centimeters up. Three measured points sit at two cups eleven centimeters, four cups thirteen centimeters, and six cups fifteen centimeters. A dashed line labeled model A rises from the origin. A solid line labeled model B starts near nine centimeters on the height axis and rises gently.](../figures/09_building_and_testing_models/competing-model-lines.svg)

A: **Model B.** Its line passes within the ±0.2 cm uncertainty of every point, while A misses the small stacks by several centimeters — many times the uncertainty. The settling feature: doubling the cups does **not** double the height (2 → 4 cups gives 11.0 → 13.0 cm, nowhere near 22 cm), so the data show a steady rise with a nonzero start, not a proportion. Physically, the first cup contributes its full height and each added cup shows only its rim.

<!-- card-id: def2af1a-3b67-4c79-8eca-a27a095cc7c4 -->
Q: A jug fills from a slowly running tap. A classmate models it as \(V = 30t\) (\(V\) in mL, \(t\) in min), assuming the jug starts empty and the flow is steady. Measurements: \(t = 2\) → 110 mL, \(t = 4\) → 171 mL, \(t = 6\) → 229 mL; the model predicts 60, 120, and 180 mL. Compute the measurement-minus-prediction differences, read their pattern, and state which single assumption the pattern says to revise — and to what.
A: The differences are **+50, +51, +49 mL — a constant offset**, so revise the "starts empty" assumption: the jug already held about 50 mL, giving \(V = 50 + 30t\). A constant gap means the measured values run parallel to the predictions, exactly what a wrong start produces, while the steady-flow assumption survives — a wrong *rate* would make the differences grow or shrink steadily instead of staying flat. Revision repairs the one failing assumption; it does not throw the whole model away.

## Regime, purpose, and deciding between models

<!-- card-id: 3575c64b-71b1-4252-a588-ab3ae9384afd -->
Q: A model's **regime of usefulness** is the range of conditions over which its predictions actually match measurement. A sunflower seedling was measured weekly, and \(H = 2 + 3w\) (\(H\) in cm, \(w\) in weeks) was fitted to the early weeks; the figure shows all the measurements with the model line. State this model's regime, and what the model is worth outside it.

![Graph of height in centimeters against age in weeks. Measured points sit at week one five centimeters, week two eight, week three eleven, week four fourteen, week five seventeen, week six about nineteen and a half, week seven about twenty and a half, and week eight twenty-one. A straight model line labeled H equals two plus three w passes upward across the full width of the graph.](../figures/09_building_and_testing_models/plant-regime.svg)

A: The regime is roughly **weeks 1 through 5**: there the points sit on the line, while from week 6 on the measurements flatten and fall ever farther below it. Outside the regime the model's predictions are unsupported — using them is the familiar extrapolation gamble. But the model is not "wrong everywhere": it remains a good model *of the early growth*, and a bounded model plus its stated regime is a perfectly honest result.

<!-- card-id: f5b4089e-6dfb-4a53-b756-ada55584208c -->
Q: Even with no late measurements at all, the candle model \(L = 20 - 2t\) (\(L\) in cm, \(t\) in h) exposes its own limit. Compute its prediction for \(t = 15\) h, and state what that prediction establishes about the model's regime — and what it cannot establish.
A: It predicts \(L = 20 - 30 = \mathbf{-10\ \text{cm}}\) — **a negative length, which is physically impossible**, so the model must fail somewhere at or before \(t = 10\) h, where \(L\) reaches 0. An impossible prediction is a free regime check: no measurement is needed to know the model cannot be trusted out there. What it cannot establish is the reverse — it does not certify the model all the way to 10 h, since the real candle may stop following the steady rate well before burning out. Like a unit check, this test only rejects.

<!-- card-id: 2477b1b5-462f-42ab-8aac-0b43f515ea3a -->
Q: The candle model \(L = 20 - 2t\) is known to be rough: the true rate wobbles by about ±0.2 cm/h. Two proposed uses — Use 1: decide whether one fresh 20 cm candle lasts a 4-hour dinner. Use 2: predict the length at \(t = 9\) h to within 0.2 cm. For each, is the rough model good enough, and what is the general rule?
A: Use 1: **good enough** — 4 h burns about 8 cm, and even at the high rate 2.2 cm/h only 8.8 cm goes; both bounds leave half the candle, so the decision is already settled. Use 2: **not good enough** — over 9 h the ±0.2 cm/h wobble alone moves the answer by about ±1.8 cm, nine times the demanded precision. The rule: a model is adequate when its roughness is small compared with what the *purpose* requires — the same judgment already used for measurement uncertainty, now applied to models. More detail than the purpose needs is unearned cost.

<!-- card-id: ad20181b-c61f-4f88-a9dc-f8a619992c1d -->
Q: Two classmates model the same slowly filling water barrel. Model A: \(V = 50t\); model B: \(V = 100 + 30t\) (\(V\) in mL, \(t\) in min). The only measurements so far: \(t = 4\) → \(210 \pm 20\) mL and \(t = 5\) → \(245 \pm 20\) mL. Show that these data cannot decide between the models, and design the measurement that would decide.
A: Both models survive both tests: at \(t = 4\), A predicts 200 and B predicts 220, both inside 190–230; at \(t = 5\), both predict 250, inside 225–265 — the two lines cross right around there. Data taken where the candidates *agree to within the uncertainty* can never separate them. So **measure where the predictions differ by much more than ±20 mL** — best of all at \(t = 0\): A says 0 mL, B says 100 mL, a 100 mL gap that no ±20 blur can hide. A deciding test is designed from the models' disagreement, not from convenience.

## Problems

<!-- card-id: 28d0d38c-cf48-4adb-b776-9cde64c4d270 -->
P: Salt pours in a thin steady stream from a dispenser into a container standing on a kitchen balance. The balance readings:

| \(t\) (s) | 0 | 10 | 20 | 30 |
|---|---:|---:|---:|---:|
| reading \(R\) (g) | 40 | 91 | 139 | 190 |

Build a model of the reading \(R\) as an equation in \(t\), state the physical meaning of each fitted number, and predict when the reading will reach 240 g.

S: **IDENTIFY:** A model-construction task. The readings rise by near-equal steps, so the candidate form is a start value plus a steady rate, \(R = \text{start} + \text{rate} \times t\) — the same two-part shape as a steady trend with a nonzero start. Both numbers must be fitted from the table, then the finished model makes the prediction.

**PLAN:** Read the start from the \(t = 0\) row. Fit the rate from the successive differences, averaging their wobble. Attach units and meanings to both numbers, check the equation against a middle row, then find when \(R\) reaches 240 g by asking how much more mass is needed at that rate.

**EXECUTE:** The model is \(\mathbf{R = 40 + 5t}\) (\(R\) in g, \(t\) in s), and it reaches **240 g at about \(t = 40\) s**. Start: the \(t = 0\) reading is 40 g — physically the empty container's mass, on the balance before any salt lands. Rate: the 10 s differences are 51, 48, 51 g — about 50 g per 10 s, so 5 g/s of salt flow. Check at \(t = 20\): \(40 + 5 \times 20 = 140\) g against the measured 139 g — inside the wobble. Prediction: reaching 240 g needs \(240 - 40 = 200\) g of salt, and \(200 \div 5 = 40\) s.

**EVALUATE:** Units close properly: \(\tfrac{\text{g}}{\text{s}} \times \text{s} = \text{g}\), and both added terms carry grams, as same-dimension addition demands. A bracket agrees: the observed rates 4.8–5.1 g/s give \(200 \div 5.1 \approx 39\) s to \(200 \div 4.8 \approx 42\) s, so 40 s is solid to a couple of seconds. One caution: 40 s lies just past the tested 0–30 s — a short reach beyond the data, safe only if the stream stays steady that little bit longer.

<!-- card-id: de34771e-84dd-47c8-a872-298ea0e33d4f -->
P: A candle following the fitted model \(L = 20 - 2t\) (\(L\) in cm, \(t\) in h) has burned for 4.0 h. A careful measurement then gives \(12.3 \pm 0.4\) cm. Does the model survive this test?

S: **IDENTIFY:** A model test: one derived prediction against one measured uncertainty interval.

**PLAN:** Substitute \(t = 4.0\) h, compare the prediction with the interval, and conclude only what agreement licenses.

**EXECUTE:** **The model survives: the prediction 12.0 cm lies inside the measured interval.** Substituting, \(L = 20 - 2 \times 4.0 = 12.0\) cm; the measurement allows 11.9 to 12.7 cm, which contains 12.0.

**EVALUATE:** The margin is thin — 12.0 sits just 0.1 cm above the interval's lower edge — so the agreement is real but not roomy; a finer instrument or a later test time would probe the model more sharply. And as always, surviving one test leaves the model useful, not proven.

<!-- card-id: fa67e13b-2b46-482c-adce-bf3ce60e7160 -->
P: A water tank fills identical bottles. Volume drawn from the tank: 4 bottles → 2.0 L, 8 bottles → 4.0 L, 12 bottles → 6.1 L. Two candidate models: A: \(V = 0.5n\); B: \(V = 0.8 + 0.4n\) (\(V\) in L, \(n\) the number of bottles). Choose the supported model, justify the choice with a test of the data, and predict the volume for 10 bottles.

S: **IDENTIFY:** A model choice between a proportional candidate and a start-plus-rate candidate, settled by testing each against the table; then one prediction, kept inside the tested range.

**PLAN:** Apply the constant-ratio test to A; compute B's predictions row by row; keep the survivor and substitute \(n = 10\).

**EXECUTE:** **Model A is supported, and it predicts \(V = 5.0\) L for 10 bottles.** Ratios: \(2.0 \div 4 = 0.50\), \(4.0 \div 8 = 0.50\), \(6.1 \div 12 \approx 0.51\) L per bottle — constant within a small wobble, the proportional signature. Model B predicts 2.4, 4.0, and 5.6 L: it misses the first and last rows by 0.4–0.5 L, far beyond that wobble. Prediction: \(0.5 \times 10 = 5.0\) L.

**EVALUATE:** Sense check: zero bottles should draw zero water — A says exactly that, while B's 0.8 L start would be water leaving with no bottle to hold it. The prediction sits at \(n = 10\), between the tested 4 and 12 — an interpolation, comfortably inside the regime the data support. The fitted 0.5 carries its proper unit, liters per bottle.

<!-- card-id: bbd9cfcd-c1c0-4f8d-a883-d790d70eec33 -->
P: The stacked-cup model \(H = 9.0 + 1.0n\) (\(H\) in cm, \(n\) cups) was fitted to small stacks of 2 to 6 cups and worked well there. A warehouse check on tall stacks finds: \(n = 10\) → 18.0 cm, \(n = 15\) → 21.5 cm, \(n = 20\) → 24.0 cm. Audit the model: compute the differences, read their pattern, state which revisions the pattern rules out and which it demands, and give the model's revised regime.

S: **IDENTIFY:** A mismatch-driven revision. Predictions and tall-stack measurements must be compared, with the *pattern* of the differences deciding among the candidate faults: the start value, the per-cup rate, or a measurement problem.

**PLAN:** Predict \(H\) at \(n\) = 10, 15, 20; form measurement-minus-prediction differences; a constant offset would implicate the start (or a fixed zero-style shift in the measuring), while a steadily growing gap would implicate the per-cup rate. Then bound the regime of the original model and refit the rate for tall stacks.

**EXECUTE:** **The per-cup rate fails for tall stacks: keep \(H = 9.0 + 1.0n\) only in its tested small-stack regime, about 2 to 6 cups, and refit tall stacks at about 0.6 cm per cup.** Predictions: 19.0, 24.0, 29.0 cm; measurements: 18.0, 21.5, 24.0 cm; differences: −1.0, −2.5, −5.0 cm — a gap that grows with every step. Growth rules out a start-value fix and a fixed zero error, since both would produce a flat offset. What remains is the rate: each added cup contributes less than 1.0 cm as the stack grows — the cups settle deeper into one another under the stack above. Tall-stack refit from \(n = 10\) to 20: \((24.0 - 18.0) \div 10 = 0.6\) cm per cup.

**EVALUATE:** The refit checks against the middle point: \(18.0 + 0.6 \times 5 = 21.0\) cm versus 21.5 measured — agreement at this roughness. The audit's logic ran one way: the pattern *rejected* two candidate faults and left one standing, but confirming the settling story needs its own discriminating test — for instance, measuring the added height of one cup directly at several stack sizes and watching whether it really shrinks.
