+++
order = 6
subject = "physics"
authoring_model = "claude-fable-5"
authoring_reasoning_effort = "high"
tags = ["physical-reasoning", "proportionality", "scale-factors", "inverse-proportion", "scaling"]
prerequisites = ["chapter:05_tables_graphs_and_data_patterns"]
provides = [
  "direct-proportion",
  "proportionality-constant",
  "proportion-equation",
  "proportional-graph",
  "nonproportional-steady-trend",
  "scale-factor",
  "scaled-drawing",
  "ratio-invariance",
  "inverse-proportion",
  "constant-product-test",
  "scaling-data-test",
]
+++

# Proportional reasoning and scaling

## From a steady trend to an exact rule

<!-- card-id: 14089667-0d8a-4178-8d47-a6bbff8e8aae -->
Q: The coin data showed a steady rise: roughly equal extra mass for each extra coin, on a trend line heading toward zero mass at zero coins. A pattern with both features has a stronger name. Two quantities are **directly proportional** when multiplying one by any factor multiplies the other by the *same* factor — double the coins and the mass doubles — which also forces the two to reach zero together. The measured table gave 21 g for 4 coins. Working from that single row, what total mass does direct proportionality predict for 8 coins, and does the measured value of 41 g bear the prediction out?
A: About **42 g**: eight coins is four coins multiplied by 2, so proportionality multiplies the 21 g by the same 2. The measured 41 g sits within ordinary repeat variation of that prediction, so the data bear it out. The zero-together feature is equally physical here — no coins contribute no mass — which is why a proportionality claim was plausible for this pair of quantities in the first place.

<!-- card-id: c7389bc4-38cc-4705-9c10-3e0509a12237 -->
Q: The doubling test compares rows two at a time; there is also a row-by-row test. In a direct proportion, dividing the dependent value by the independent value gives — apart from measurement wobble — the **same result in every row**, and that shared value is called the **constant of proportionality**. It keeps a per-unit meaning. For the coin table, the row "2 coins, 11 g" gives \(11 \div 2 = 5.5\) g per coin. Compute the same ratio for the row "10 coins, 52 g", and state what physical thing this roughly shared value tells you.
A: The ratio is **5.2 g per coin** \((52 \div 10)\) — close to the 5.5 from the other row, as a direct proportion demands. Physically, the constant of proportionality is the mass of one coin: each coin adds about 5.2 g, so any row's total is just that per-coin mass counted up. One number summarizes how the two quantities are tied together.

<!-- card-id: ab9517da-e79c-47fd-8664-54287eaf0ffa -->
Q: Let \(n\) stand for the number of coins and \(m\) for the total mass in grams, with the constant of proportionality about 5.2 g per coin. Translate the statement "the total mass is the constant times the count" into an equation, and use substitution to predict the total mass of 5 coins.
A: The equation is **\(m = 5.2\,n\)**, and substituting \(n = 5\) gives \(m = 5.2 \times 5 = 26\) g. That one short equation is a compact model of the whole relationship: it stores every table row and yields a prediction for counts nobody measured. The 5-coin prediction sits inside the measured range of 2 to 10 coins, so it leans on the rule only where the data have tested it.

<!-- card-id: 853376ff-35ca-45cb-8d57-66e25dc3ea92 -->
C: Direct proportion in symbols: for a dependent quantity \(y\), an independent quantity \(x\), and a constant of proportionality \(k\), the rule computing the dependent from the independent reads [\(y = k\,x\)] — one fixed multiplier, and nothing added on.

<!-- card-id: e5e86993-3acf-4c95-bff8-f52cdd7db41e -->
Q: A direct proportion also has a graphical signature. The corner where a graph's two axes meet — the point where both quantities read zero — is called the **origin**. The figure shows three graphs, each with a rising trend line. Which panel alone could show a direct proportion, and what feature disqualifies each of the other two?

![Three small graphs labeled A, B, and C, each with a horizontal and a vertical axis meeting at a corner marked zero. In A a straight line rises from the corner itself. In B a straight line rises but begins partway up the vertical axis, above the corner. In C a line leaves the corner and curves upward ever more steeply.](../figures/06_proportional_reasoning_and_scaling/rising-graph-shapes.svg)

A: **Panel A** — a straight trend line passing through the origin. Panel B is straight but starts above the origin: its dependent quantity is not zero when the independent one is, so doubling the independent value does not double the dependent one. Panel C passes through the origin but bends: its rise per step keeps growing, so the row ratio drifts instead of staying constant. The signature needs both marks at once — straight, *and* through the origin.

<!-- card-id: 40330c7d-808d-4186-804f-0dbb0ffb818a -->
Q: An empty jar of mass 50 g stands on a balance, and identical coins are added one at a time. The readings: 1 coin, 55 g; 2 coins, 60 g; 4 coins, 70 g. A classmate argues: "The reading climbs by equal steps, so the reading is directly proportional to the number of coins." Apply a proportionality test to the readings, give the verdict, and name the feature of the situation that ruins proportionality.
A: **Not proportional.** Doubling the coins from 2 to 4 takes the reading from 60 g to only 70 g, nowhere near double; equivalently, the row ratios drift: 55, then 30, then 17.5 g per coin. The culprit is the jar: its 50 g is present even at zero coins, an added starting amount that no shared multiplier can produce. A steady, equal-step rise is a genuine trend — but it is a **steady trend with a nonzero start**, and proportionality additionally demands a constant ratio and zero-with-zero.

## Scale factors and scaled drawings

<!-- card-id: 1d884762-7158-405d-9f15-dfdae9156003 -->
Q: Doubling is only the factor 2; a direct proportion obeys every **scale factor**: multiply one quantity by any factor \(f\) — 2.5, or one half — and the other quantity is multiplied by the same \(f\). In a container with constant cross-sectional area, the water depth is directly proportional to the volume of water added, and one measured row reads "200 mL added, depth 3.9 cm". Use a single scale factor to predict the depth when the total volume added is 250 mL.
A: About **4.9 cm**: 250 mL is 200 mL scaled by \(f = 1.25\), so the depth is \(3.9 \times 1.25 \approx 4.9\) cm. One factor carries the prediction in a single jump — no need to build up in steps. Reading midway between this container's measured 200 and 300 mL rows gave "about 5 cm" before, and the two routes agree within the data's ordinary wobble.

<!-- card-id: 4fe17466-3930-4759-a6b0-fbc6553501c4 -->
Q: A drawing is **to scale** when every length on the object is multiplied by one shared scale factor to give the corresponding length on the drawing. The figure shows a door and its scale drawing, with dimension arrows: the real door is 200 cm tall and 80 cm wide, and the drawing is 10 cm tall with its width left as a question mark. Find the drawing's scale factor and the missing width.

![A tall rectangle representing a door, with a small circle for its handle, marked by dimension arrows as two hundred centimeters tall and eighty centimeters wide. Beside it stands a much smaller rectangle of the same shape labeled scale drawing, marked as ten centimeters tall, with its width marked by a question mark. A note says the artwork itself is not drawn to scale.](../figures/06_proportional_reasoning_and_scaling/scaled-door-drawing.svg)

A: The missing width is **4 cm**, from a scale factor of **\(\frac{1}{20}\)**. The matched pair of heights fixes the factor: \(10 \div 200 = \frac{1}{20}\), so every drawn length is one-twentieth of the real one. Applying it to the width gives \(80 \times \frac{1}{20} = 4\) cm. That is the general method: read the factor off one matched pair, then apply it to every other length.

<!-- card-id: 6e3575bb-d8c3-469a-af37-75a46a2876b8 -->
Q: The door drawing used one factor for all lengths. Suppose a student instead doubles only the widths of a drawing and leaves the heights alone. The result is "bigger" in one direction — yet it no longer looks like the door. Using ratios, explain what one-factor scaling preserves that unequal factors destroy.
A: One shared factor leaves every ratio of lengths *within* the object unchanged: the real door's height-to-width ratio is \(200 : 80 = 2.5\), and the drawing's is \(10 : 4 = 2.5\) — equivalent ratios, so the proportions of the shape survive and the drawing looks right. Doubling only the width changes that internal ratio (a 10 cm tall, 8 cm wide door drawing has ratio 1.25), which is a different shape. Distortion *is* a change in internal ratios; faithful scaling is their invariance.

## Trading off: inverse proportion

<!-- card-id: 0debd8e0-ad3e-48a3-a7a9-6084a129070d -->
Q: Some pairs of quantities trade off instead of growing together. A 120 cm ribbon is cut into equal pieces with nothing left over: 4 cm pieces give 30 of them; 8 cm pieces give 15. Two quantities are **inversely proportional** when multiplying one by a factor *divides* the other by that same factor — equivalently, when their product stays fixed. What is the fixed product here, and how many 6 cm pieces would the ribbon give?
A: The ribbon gives **20 pieces** of 6 cm, because piece length times piece count is pinned at the ribbon's total: \(4 \times 30 = 8 \times 15 = 120\) cm, so \(120 \div 6 = 20\). The factor rule shows the same trade: doubling the piece length from 4 to 8 cm halved the count from 30 to 15. The fixed product is the physical whole being shared out — the 120 cm of ribbon.

<!-- card-id: f5b5153a-0d5a-4ae8-8bf8-b67341114e11 -->
Q: A 600 mL container is filled by pouring at a steady rate. Trials with different rates record: 20 mL per second takes 30 s; 30 mL per second takes 20 s; 60 mL per second takes 10 s. Test whether the filling time is inversely proportional to the pouring rate, and state what the fixed product means physically.
A: It is **inversely proportional**: every row's product is the same, \(20 \times 30 = 30 \times 20 = 60 \times 10 = 600\), and tripling the rate from 20 to 60 mL per second cuts the time to a third, from 30 s to 10 s. The fixed product is the container's 600 mL capacity — rate times time is the amount of water delivered, and the container fixes that amount no matter how the pouring is split between "how fast" and "how long".

<!-- card-id: adde7d74-bbec-4984-a056-cb0ea8392f0c -->
Q: Both panels of the figure show a dependent quantity falling as the independent quantity grows, with the plotted values labeled at the marked points. "One goes down while the other goes up" fits both. Which panel alone could show an inverse proportion? Give the test that decides it and the feature that disqualifies the other panel.

![Two small graphs labeled A and B, each with a horizontal axis marked one through four and dots that sit lower as the horizontal value grows. In A three dots on a straight falling line are labeled sixty at one, forty-five at two, and fifteen at four. In B three dots on a curve that falls steeply and then flattens are labeled sixty at one, thirty at two, and fifteen at four.](../figures/06_proportional_reasoning_and_scaling/falling-graph-shapes.svg)

A: **Panel B.** Doubling the independent value halves the dependent one — 60 to 30 from 1 to 2, and 30 to 15 from 2 to 4 — so every labeled product is the fixed 60. Panel A instead loses an equal *amount* each step (15 per unit), a subtraction pattern: its products run 60, 90, 60, not a constant. Panel A's line would also reach zero just past 4, but an inverse proportion never touches zero — a fixed product forbids either quantity from vanishing. Falling alone proves nothing; the constant product is the test.

## Testing a scaling claim against data

<!-- card-id: 5617edff-21b1-4511-a7d0-39d4cb0ac3e8 -->
Q: A real ratio test must cope with measurement wobble, so "the ratios are not exactly equal" can never be the whole verdict. Two students each test the claim "total mass is directly proportional to the number of coins" on their own coin sets, computing grams per coin for five rows. Student 1's ratios: 5.5, 5.1, 5.3, 5.2, 5.2. Student 2's ratios: 4.1, 4.6, 5.0, 5.5, 5.9. Neither list is perfectly constant. Whose data support the claim, and what distinguishes harmless wobble from disqualifying variation?
A: **Student 1's.** Those ratios scatter irregularly around 5.2 with no direction — the fingerprint of repeat variation in honest readings of a genuinely constant ratio. Student 2's ratios climb steadily from 4.1 to 5.9: that is a trend in the ratios, not scatter, so the ratio itself changes as the count grows and proportionality fails — even though every single value looks plausible alone. Judge constancy the way a trend is judged: look for direction in the deviations, not for perfection.

## Problems

<!-- card-id: 0ffa8a4f-164d-4432-9986-43b6dc31d725 -->
P: A student measures the total thickness of stacks of identical paper sheets:

| Number of sheets | Stack thickness in mm |
|---:|---:|
| 50 | 5.2 |
| 100 | 10.1 |
| 150 | 15.3 |
| 200 | 20.2 |

Decide whether the stack thickness is directly proportional to the number of sheets, and — if the data support it — predict the thickness of 120 sheets.

S: **IDENTIFY:** A proportionality test on measured data, followed by a prediction that uses the constant of proportionality. The decision test is ratio constancy judged against ordinary measurement wobble.

**PLAN:** Divide each thickness by its sheet count to get mm per sheet; if the ratios wobble without direction, take their rough shared value as the constant \(k\) and predict \(120 \times k\). Check the prediction against the measured range.

**EXECUTE:** The data support direct proportionality, and 120 sheets should stack to **about 12 mm**. The row ratios are \(5.2 \div 50 = 0.104\), \(10.1 \div 100 = 0.101\), \(15.3 \div 150 = 0.102\), and \(20.2 \div 200 = 0.101\) mm per sheet — irregular wobble around 0.10 with no direction, so \(k \approx 0.10\) mm per sheet, one sheet's thickness. Then \(120 \times 0.102 \approx 12.2\), about 12 mm.

**EVALUATE:** A scale-factor route agrees: 120 sheets is 200 scaled by 0.6, and \(0.6 \times 20.2 = 12.1\) mm. The prediction lies inside the measured range of 50 to 200 sheets, where the rule has been tested; zero sheets giving zero thickness is physically right for a pure stack; and "about 12 mm" claims no fineness the ratio wobble cannot support.

<!-- card-id: 2956337c-34f8-46e6-ac66-c0fc6d7a5467 -->
P: A photo 10 cm wide and 15 cm tall is enlarged to scale. The print is 25 cm wide. How tall is the print?

S: **IDENTIFY:** A scaled-drawing task: one shared scale factor links every photo length to its print length.

**PLAN:** Fix the factor from the matched pair of widths, then apply it to the height.

**EXECUTE:** The print is **37.5 cm** tall: the factor is \(25 \div 10 = 2.5\), and \(15 \times 2.5 = 37.5\).

**EVALUATE:** The internal ratio survives, as to-scale demands: \(15 : 10 = 1.5\) and \(37.5 : 25 = 1.5\).

<!-- card-id: b0e2a7d3-3173-4f39-8659-3545ac971fda -->
P: Three data sets, each relating an independent quantity to a measured dependent one:

Set (i) — rice measured out with a scoop: 2 scoops, 90 g; 4 scoops, 180 g; 5 scoops, 225 g.

Set (ii) — a storage box as identical books are added: 1 book, 2.7 kg total; 2 books, 4.9 kg; 4 books, 9.3 kg.

Set (iii) — 240 identical stickers shared equally among albums: 2 albums, 120 stickers each; 4 albums, 60 each; 8 albums, 30 each.

A classmate claims set (ii) is directly proportional "because every extra book adds the same amount." Classify each set as directly proportional, inversely proportional, or a steady trend with a nonzero start — justifying each with the appropriate test — and repair the classmate's claim.

S: **IDENTIFY:** A classification of three candidate scaling rules, each needing its matching test: ratio constancy for direct proportion, product constancy for inverse proportion, and the zero-with-zero check to separate proportionality from a mere steady trend.

**PLAN:** Compute per-row ratios for sets (i) and (ii) and apply a doubling check; compute per-row products for set (iii); then compare the classmate's equal-steps argument with the full definition.

**EXECUTE:** Set (i) is **directly proportional**, set (ii) is a **steady trend with a nonzero start** — not proportional — and set (iii) is **inversely proportional**. For (i), every ratio is 45 g per scoop \((90 \div 2 = 180 \div 4 = 225 \div 5)\), and doubling 2 scoops to 4 doubles 90 g to 180 g. For (ii), the ratios drift — 2.7, then 2.45, then about 2.3 kg per book — and doubling 2 books to 4 takes 4.9 kg to 9.3 kg, not 9.8: the box's own roughly 0.5 kg is present at zero books. For (iii), every product is the fixed 240 stickers \((2 \times 120 = 4 \times 60 = 8 \times 30)\), and doubling the albums halves each album's share. The claim's repair: equal steps establish only a steady trend; direct proportionality further requires a constant ratio — equivalently, zero-with-zero — which the box breaks.

**EVALUATE:** Each verdict passes a second, independent test: (i) zero scoops of rice would weigh zero; (ii) the drifting ratios and the failed doubling agree with each other; (iii) the factor rule matches the product rule at every step. And the repaired claim explains the classmate's error instead of merely contradicting it — the steady steps are real, but they are the books' 2.2 kg apiece stacked on a nonzero start.
