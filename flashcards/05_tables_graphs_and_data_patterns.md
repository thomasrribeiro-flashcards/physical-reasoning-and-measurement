+++
order = 5
subject = "physics"
authoring_model = "claude-fable-5"
authoring_reasoning_effort = "high"
tags = ["physical-reasoning", "data-tables", "graphs", "trends", "interpolation"]
prerequisites = ["chapter:04_repeated_measurements_and_uncertainty"]
provides = [
  "data-table",
  "independent-quantity",
  "dependent-quantity",
  "graph-axes",
  "data-point",
  "axis-scale",
  "graph-trend",
  "trend-line",
  "anomalous-point",
  "interpolation",
  "extrapolation",
  "graphical-artifact",
  "display-choice",
]
+++

# Tables, graphs, and data patterns

## Recording data so others can use it

<!-- card-id: a1b4c7d2-3e58-4f91-8c26-d05b9e3a71f4 -->
Q: An investigation often produces several related readings that must be recorded so that anyone can inspect them later. A **data table** arranges recorded values in rows and columns: each column holds one physical quantity, and each row holds the values that belong together from one trial. The column header names the quantity and states its unit once — for example, "Total mass in g" — so the entries below it are written as bare numbers. In such a column, one entry reads "45.3". What complete quantity value does that entry stand for, and why is it acceptable that the entry itself carries no unit?
A: The entry stands for **45.3 g** — the number in the body paired with the unit named once in the header. A quantity value always needs both a number and a unit; the table simply factors the shared unit out of the column so it is written once instead of on every line. The pairing is preserved, not dropped: under a header that named no unit, the bare numbers would be incomplete records that no reader could turn back into quantity values.

<!-- card-id: 5e928c3b-7a41-4d67-b3f8-291c6d84e0a5 -->
Q: Many experiments share one shape: the experimenter deliberately sets one quantity to chosen values, then measures how another quantity responds. The set-by-choice quantity is called the **independent quantity**; the measured response is the **dependent quantity**, because its value depends on what the independent quantity was set to. A student places 2, then 4, then 6 identical coins on a digital balance and records the balance reading each time. Which quantity here is independent and which is dependent, and what test decides it?
A: The number of coins is the **independent** quantity and the balance reading — the total mass — is the **dependent** one. The test is who fixes the value: the student chose 2, 4, and 6 before any measuring happened, while the mass value was delivered by the measurement in response to that choice. Chosen by the experimenter means independent; produced by the measurement means dependent.

<!-- card-id: c39d51e8-2f76-4b04-9ae1-6b8f24c7d093 -->
Q: A table can be inspected for a pattern before any picture is drawn. A student recorded the total mass of different numbers of identical coins:

| Number of coins | Total mass in g |
|---:|---:|
| 2 | 11 |
| 4 | 21 |
| 6 | 32 |
| 8 | 41 |
| 10 | 52 |

One useful check is to subtract each mass entry from the next one down, to see how much the mass grows per step of 2 coins. Compute these successive differences. What pattern do they reveal, and why do they vary slightly even though the coins are identical?
A: The differences are **10, 11, 9, and 11 g** — close to 10 g for every 2 added coins, so the pattern is a steady growth of about 5 g per coin: equal steps in the set quantity produce roughly equal steps in the measured one. The slight wobble is the repeat variation of the mass readings carried into the table — each entry is an honest reading with its own small scatter — not evidence that some coins differ from others.

## Turning rows into positions

<!-- card-id: 8d64f2a9-1c35-4e78-a5d2-4e907b1f68c3 -->
Q: A table records values; a **graph** turns them into positions so a pattern can be seen at a glance. A graph is built on two number lines called **axes**, one horizontal and one vertical: by convention the horizontal axis carries the independent quantity and the vertical axis carries the dependent quantity, and each axis is labeled with its quantity and unit, like a table header. Each row of the table becomes one **data point** — the single position that lines up with the row's value on each of the two axes. For the coin experiment (coin counts set by the student, mass measured in response), state which quantity belongs on which axis, and describe the point that represents the row "6 coins, 32 g".
A: Number of coins goes on the **horizontal** axis, because the student set it, and total mass in g goes on the **vertical** axis, because it is the measured response. The row becomes the one point standing directly above 6 on the coin axis and exactly level with 32 on the mass axis — a single position that carries both of the row's values at once.

<!-- card-id: 2f7e94b1-6d08-4a53-8e97-b3c51a26f4d8 -->
Q: The figure shows the coin data as a graph. One data point is circled, and muted dashed guide lines run from it to each axis. Using the scale divisions of each axis, read the two values the circled point represents.

![A graph whose horizontal axis is labeled number of coins, marked from zero to ten with labels every two, and whose vertical axis is labeled total mass in grams, with labels every ten and small unlabeled divisions between them. Five filled dots rise from lower left to upper right. One dot is circled, with dashed guide lines running from the circle down to the horizontal axis and across to the vertical axis.](../figures/05_tables_graphs_and_data_patterns/coin-mass-graph.svg)

A: The circled point represents **6 coins with a total mass of 32 g**. Its vertical guide meets the coin axis at the labeled mark 6; its horizontal guide meets the mass axis one small division above the labeled 30, and since five small divisions span each 10 g, one division is 2 g — the same count-the-divisions reading used on any instrument scale, applied to an axis.

<!-- card-id: e85a3d76-4b92-4c18-af64-19d7e0c352b6 -->
Q: An axis is a number line, so its markings must behave like one. A student draws a vertical axis whose equally spaced labels read, from the bottom up: 0, 5, 10, 20, 40. What is wrong with this axis, and what would the flaw do to the visible shape of any data plotted against it?
A: Equal distances along it carry unequal value steps — the first spaces hold 5 apiece, the next 10, the last 20 — while on a true scale equal distance means equal value everywhere. Such an axis squeezes larger values together: a rise of 5 spans a whole space near the bottom but a fraction of one near the top, so a quantity climbing by equal amounts appears to flatten as it grows. The plotted shape then reports the scale's distortion, not the data's pattern.

## Seeing the pattern through the scatter

<!-- card-id: 7c218e5f-9a63-4d84-b1e9-56a0d38f92c7 -->
Q: Plotted together, data points can show what no single row reveals. The **trend** of a graph is the overall way the dependent quantity changes as the independent quantity increases — rising, falling, or staying level, and steadily or with changing steepness. The figure shows the coin-mass graph. State its trend, and explain why the points can establish a real trend even though they do not lie perfectly on one line.

![A graph whose horizontal axis is labeled number of coins, marked from zero to ten with labels every two, and whose vertical axis is labeled total mass in grams, with labels every ten and small unlabeled divisions between them. Five filled dots rise from lower left to upper right. One dot is circled, with dashed guide lines running from the circle down to the horizontal axis and across to the vertical axis.](../figures/05_tables_graphs_and_data_patterns/coin-mass-graph.svg)

A: The trend is a **steady rise**: total mass grows by roughly equal amounts — about 10 g — for each equal step of 2 coins. Each plotted reading carries repeat variation, so honest points sit *near* the pattern rather than exactly on it; the trend is the collective behavior that survives the scatter, judged from all the points together rather than from any single one.

<!-- card-id: 4a9c6e21-8f57-4b39-92d6-c7e13b508a4f -->
Q: Once points are plotted, a line is usually drawn to show the pattern. A **trend line** is a single straight or smoothly bending line drawn through the middle of the scatter, leaving the points roughly balanced on either side. The figure shows the same five plotted points treated two ways: in P, each neighboring pair of points is joined by its own straight segment; in Q, one straight line runs through the middle of the scatter. Which treatment better represents the measured pattern, and what mistaken claim does the other treatment make?

![Two small graphs side by side labeled P and Q, each showing the same five dots rising from lower left to upper right with small vertical wobbles. In P the dots are joined point to point by straight segments that bend at every dot. In Q a single straight line passes through the middle of the dots, some sitting slightly above it and some slightly below.](../figures/05_tables_graphs_and_data_patterns/line-treatments.svg)

A: Treatment **Q**. The points wobble around the pattern only because each reading carries repeat variation, so the underlying behavior is best shown by one line through the middle, where the ups and downs partly cancel — the same reason a mean beats any single reading. Treatment P claims that every wobble is real: that the measured quantity genuinely rose faster, then slower, turning exactly at each measured point. It promotes measurement scatter into physical behavior.

<!-- card-id: b62d8f34-5c19-4e72-a840-3f9e6c25d1b7 -->
Q: Just as one reading far outside a cluster of repeats points to a possible mistake, a graph can contain an **anomalous point**: a data point lying far from the trend that all the other points share. A student's graph climbs steadily except for one point sitting far above the pattern. What should the student do about the anomalous point, and what should the trend line do in the meantime?
A: Treat it as a **suspected mistake**: look for an identifiable cause — a misread scale, a miscopied digit — and re-measure that row if possible. It may be set aside only with an identified cause, never merely for being inconvenient. Meanwhile, the trend line is drawn through the middle of the *other* points and must not bend toward the anomaly: one suspect row is not allowed to reshape the pattern that the rest of the data establishes.

## Reading between and beyond the data

<!-- card-id: 09e5b7c8-2d64-4a91-b53e-8c1f70d46a92 -->
Q: A trustworthy trend lets a graph answer questions the table never measured. **Interpolation** is reading a value *between* measured points by assuming the trend continues smoothly across the gap. A coin graph has points at 2 coins (11 g) and 4 coins (21 g), on a steadily rising trend. Use interpolation to predict the total mass of 3 coins, and state why the prediction deserves an "about".
A: About **16 g**: 3 coins sits midway between the measured 2 and 4, and on a steady rise the value midway across the gap lies near the middle of 11 and 21 g. The "about" is honest for two reasons — the surrounding readings each carry repeat variation, and the smooth continuation of the trend inside the gap is an assumption, not a measurement. Interpolation yields a well-supported estimate, never a measured value.

<!-- card-id: d41f6a83-7e25-4c96-8b17-f0a3c5e928d6 -->
Q: **Extrapolation** extends a trend *beyond* the last measured point. A student measures a young plant's height each morning for five days; the points rise steadily by about 2 cm per day. Compare the trust deserved by (a) an interpolated height read between day 2 and day 3, and (b) an extrapolated prediction of the height at day 40 — and explain what makes the difference.
A: The interpolated value deserves fair trust; the day-40 prediction deserves very little. Inside the measured range, the trend is anchored by tested points on both sides of the gap. Beyond the last point nothing was measured, so the data cannot check the pattern there — the prediction rests entirely on assuming the trend continues unchanged for 35 unmeasured days, and no real plant adds 2 cm forever. Data supports a pattern only over the range where it was tested; extrapolation may still be useful nearby, but it must be reported as an assumption, and its support weakens the farther it reaches.

<!-- card-id: 6e83c9d5-0b47-4f12-9a68-25d8b4e07c31 -->
Q: The figure shows the *same* four height readings of one plant displayed twice. In display P the vertical axis runs from 0 to 50 cm and the points look level; in display Q it runs only from 40.0 to 40.5 cm and the points climb steeply. A **graphical artifact** is a visual impression produced by the display choices rather than by the data. What did the plant's height actually do over the four days, and which visual impression is an artifact?

![Two small graphs side by side labeled display P and display Q, each plotting four dots against days one through four. In display P the vertical axis is labeled from zero to fifty centimeters and the four dots sit at nearly the same height. In display Q the vertical axis is labeled from forty point zero to forty point five centimeters and the same four dots step visibly upward from left to right.](../figures/05_tables_graphs_and_data_patterns/axis-start-comparison.svg)

A: The height rose by a small but real **0.3 cm**, from 40.1 to 40.4 cm — both displays plot identical data. Each impression is shaped by an axis choice: Q stretches a 0.5 cm span across the whole axis, so a 0.3 cm rise fills most of it and *looks* dramatic, while P compresses the same rise into a sliver of a 50 cm axis and makes it look like nothing. The steepness of a picture is an artifact of the scale; the *size* of a change must be read from the axis numbers. A zoomed-in axis like Q's is legitimate for showing fine detail — provided its scale, not its slope, is what gets believed.

<!-- card-id: 3b57e0a2-9c84-4d16-8f39-71e6a4d2c580 -->
Q: The same measurements can be presented as a table, as a graph, or as both. Name one question the table answers better and one question the graph answers better, with the reason for each.
A: The table best answers "exactly what value was recorded?" — it preserves each reading to its full written fineness, whereas a plotted position can only be read back to about the nearest axis division, adding reading doubt on top of the original. The graph best answers "what is the data doing overall?" — trend, steadiness, and any anomalous point become visible at a glance once values become positions, a pattern that stays buried in columns of digits. A careful report often includes both: the table as the record, the graph as the pattern.

## Problems

<!-- card-id: f9264b8e-1d73-4a05-b6c8-e3958d17f2a4 -->
P: A student pours water into a straight-sided container in measured additions and records the depth after each addition. No reading is suspect.

| Total volume added in mL | Depth in cm |
|---:|---:|
| 100 | 2.1 |
| 200 | 3.9 |
| 300 | 6.1 |
| 400 | 8.0 |

Working from the table alone, state the trend of depth against volume added, and predict the depth when the total volume added is 250 mL.

S: **IDENTIFY:** A data-pattern task on a recorded table: check the successive differences for steadiness, state the trend, then interpolate between measured rows for a value that was never measured.

**PLAN:** Subtract each depth entry from the next to get the change per 100 mL; if the steps are roughly equal, the trend is a steady rise. Since 250 mL lies midway between the 200 and 300 rows, predict its depth as the middle of those two depth entries.

**EXECUTE:** The trend is a **steady rise of about 2 cm per 100 mL added**, and the predicted depth at 250 mL is **about 5.0 cm**. The successive differences are \(3.9 - 2.1 = 1.8\), \(6.1 - 3.9 = 2.2\), and \(8.0 - 6.1 = 1.9\) cm — roughly equal steps. Midway between the neighboring entries: \((3.9 + 6.1) \div 2 = 5.0\) cm.

**EVALUATE:** The prediction is an interpolation — 250 mL sits inside the measured range with tested rows on both sides — so the trend is being used where the data supports it. The differences wobble by about 0.2 cm, ordinary repeat variation, so "about 5 cm" claims no fineness the wobble cannot support; and 5.0 does lie between 3.9 and 6.1, as a between-rows value must.

<!-- card-id: 81c5d3f6-4e29-4b87-a1d4-09b67e8c53f2 -->
P: The graph shows the recorded total mass for even numbers of identical coins from 2 to 10. From the graph, predict the total mass of 7 coins, with an honest statement of how fine the prediction can be.

![A graph whose horizontal axis is labeled number of coins, marked from zero to ten with labels every two, and whose vertical axis is labeled total mass in grams, with labels every ten and small unlabeled divisions between them. Five filled dots rise from lower left to upper right. One dot is circled, with dashed guide lines running from the circle down to the horizontal axis and across to the vertical axis.](../figures/05_tables_graphs_and_data_patterns/coin-mass-graph.svg)

S: **IDENTIFY:** An interpolation between plotted points on a steadily rising trend.

**PLAN:** Locate 7 midway between the measured 6 and 8 on the coin axis; read the surrounding points and take the value midway across the gap.

**EXECUTE:** The prediction is **about 36 or 37 g**. The points at 6 and 8 coins read 32 and 41 g; midway between them gives roughly 36.5 g, and a value read between plotted points cannot honestly claim a finer place than the readings and axis divisions themselves.

**EVALUATE:** A per-coin check agrees: the trend climbs about 5 g per coin, and seven coins at about 5 g each also lands near 35–36 g. The prediction stays inside the measured range, so it leans on the trend only where the data has tested it.

<!-- card-id: 57a8e2c4-6f91-4d38-b7a2-c40d19f6e835 -->
P: The figure shows a classmate's graph of stack height against the number of identical books, with the line the classmate drew through the data. Alongside it, the classmate concludes: "The pattern is exact, so 40 books would stand 160 cm tall." Audit the graph and the conclusion: identify every flaw and state what should be done about each.

![A graph whose horizontal axis is labeled number of books, marked one through five, and whose vertical axis is labeled stack height in centimeters, with the labels zero, five, ten, twenty, and forty at equal spacing. Five dots are joined point to point by straight segments. The dots step upward from left to right, except that the dot at three books sits far above its neighbors, and the segments bend sharply up to it and back down.](../figures/05_tables_graphs_and_data_patterns/flawed-graph.svg)

S: **IDENTIFY:** A display audit: the axis scale, the line treatment, the handling of a far-off point, and the reach of the stated claim must each be checked against its rule.

**PLAN:** Check each axis as a number line; compare the drawn line with trend-line practice; ask whether the far-off point was investigated; compare the claim's range with the measured range.

**EXECUTE:** There are **four flaws**. First, the vertical axis is not a true scale: its equally spaced labels 0, 5, 10, 20, 40 carry unequal value steps, distorting every plotted shape — redraw it with equal value per equal distance. Second, the line is drawn point to point, promoting repeat scatter into real turns — a single trend line through the middle of the scatter belongs there instead. Third, the point at 3 books lies far above the pattern of the others: an anomalous point to investigate for a cause or re-measure, yet the drawn line chases it as if it were part of the trend. Fourth, the conclusion extrapolates to 40 books — eight times beyond the measured range of 1 to 5 — and calls the pattern "exact": with the anomaly set aside pending re-measurement, the remaining points do show about 4 cm per book, so 40 books at about 160 cm is a *stated-assumption* estimate at best, never an exact certainty.

**EVALUATE:** Each flaw maps to its rule: an axis must behave as a number line; a trend line balances scatter rather than joining dots; setting data aside needs an identified cause; and a trend earns trust only over the range where it was tested. Note what was *not* wrong: the arithmetic of 40 books × 4 cm is fine — the flaw is the certainty claimed for it, not the number.
