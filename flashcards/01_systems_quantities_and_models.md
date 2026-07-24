+++
order = 1
subject = "physics"
authoring_model = "claude-fable-5"
authoring_reasoning_effort = "high"
tags = ["physical-reasoning", "systems", "quantities", "measurement", "models"]
prerequisites = [
  "concept:mathematics/quantitative-reasoning-and-arithmetic#measurement-unit",
  "concept:mathematics/quantitative-reasoning-and-arithmetic#unit-conversion",
]
provides = [
  "system",
  "system-boundary",
  "surroundings",
  "physical-quantity",
  "quantity-value",
  "measurement",
  "measurand",
  "physical-model",
  "model-assumption",
  "model-prediction",
  "model-test",
]
+++

# Systems, quantities, and models

## Choosing a system

<!-- card-id: ed58aef2-6bfd-4839-833b-d601b58b4d03 -->
Q: To answer a question about the world, physics first picks out which part of the world to study. The chosen object or collection of objects is called the **system**. The imagined dividing line that separates the chosen part from everything else is the **system boundary**, and everything outside the boundary is the **surroundings**. For the question "Will this box fit on the closet shelf?", a sensible system is the box together with the shelf opening. Using these three words, what are the closet walls, the floor, and the other stored objects in this situation?
A: They are the surroundings. They lie outside the chosen system boundary: only the box and the shelf opening were picked as the system for this question, and everything not chosen is, by definition, the surroundings.

<!-- card-id: 7b7f1595-7fe8-47ab-b313-fa02686fe787 -->
Q: A system boundary is drawn by the person asking the question. It is imagined, not built: it does not need to follow any wall or container, it may cut through open air, and it may enclose objects that sit far apart. For the question "How many of the loose books on this desk will fit into that empty box across the room?", explain whether one system may contain both the books and the faraway box.
A: It may. The system is whatever collection the question needs, so the books and the box can be enclosed by one imagined boundary even though nothing physically surrounds them together. The boundary is a decision made for the question, not a physical object.

<!-- card-id: 1aa00cc9-be83-48b4-ac3a-fb03a5bf78e3 -->
Q: In the figure, each dashed loop is a *candidate* system boundary, and the letter beside each loop names that candidate. A book stands on a table, and to the right two shelf boards form an open gap.

![A book stands on a table; to the right, two horizontal shelf boards form an open gap. Dashed loop A encloses only the book. Dashed loop B encloses both the book and the shelf gap.](../figures/01_systems_quantities_and_models/system-boundary-options.svg)

The question to answer is: "Will the book fit upright into the gap between the shelf boards?" Which candidate boundary suits this question, and why?
A: Boundary B. The question compares the book with the shelf gap, so both must be inside the system. Candidate A leaves the gap in the surroundings, and a question cannot be answered from a system that excludes something the comparison needs.

<!-- card-id: 192d8b16-c489-432a-b225-0abe7dfb22c9 -->
Q: Two questions are asked about the same book: (1) "Will it fit upright into the shelf gap?" and (2) "Will it lie flat inside the drawer?" The book is identical in both. Explain why the two questions still lead to two different systems.
A: Each question compares the book with a different second object: the shelf gap for (1), the drawer for (2). A system must contain whatever the question's comparison needs, so changing the question changes which objects are chosen — there is no single "correct" system for an object by itself.

## Properties, quantities, and values

<!-- card-id: a3849f0e-637b-4898-9ed3-84faa42daa27 -->
Q: An object has many **properties** — features such as its color, its shape, its material, and its height. A property that can be compared by size or amount, and reported as a number together with a unit, is called a **physical quantity**. A wooden crate is dark brown and is \(40\text{ cm}\) tall. Which of these two properties is a physical quantity, and why is the other, as stated, not one?
A: The height. It is reported as a number with a unit (\(40\text{ cm}\)) and can be compared by size with other heights. "Dark brown" is a property but, as stated, not a physical quantity: it describes the crate without any number-and-unit report that would let one crate be browner than another by a stated amount.

<!-- card-id: 2655ebe3-a6e0-4bf8-84a6-52d0d49fd695 -->
Q: A physical quantity and the report used to express it are different things. The crate's height is the quantity — a feature of the crate itself. The **quantity value** \(40\text{ cm}\) is the report of that quantity: a number (\(40\)) together with a unit (the centimeter). If nobody ever measured the crate or wrote anything down, would the crate still have its height?
A: Yes. The height belongs to the crate whether or not anyone reports it. The quantity value \(40\text{ cm}\) is only an expression of that height — writing it, erasing it, or getting it wrong changes the report, not the crate.

<!-- card-id: 41b502e9-29b2-4edd-8392-6c46428a83dd -->
Q: The same crate height can be reported as \(40\text{ cm}\) or as \(0.40\text{ m}\), using the exact identity \(1\text{ m}=100\text{ cm}\). Between these two reports, what changed and what stayed the same?
A: Only the expression changed: a different unit paired with a matching different number. The physical quantity — the crate's actual height — stayed the same. \(40\text{ cm}\) and \(0.40\text{ m}\) are two quantity values for one and the same length.

## Measurement and the measurand

<!-- card-id: 479582d1-cb88-444c-bbda-e1e431e334ec -->
Q: A **measurement** is an experimental process: an instrument — a tool built to carry the unit's markings, such as a ruler — is brought to the object, the comparison with the unit is actually carried out, and the result is a quantity value. Sara glances at the crate and says "roughly \(40\text{ cm}\)". Tomas stands a ruler beside the crate and reads \(41\text{ cm}\). Which report is a measurement result, and what makes it one?
A: Tomas's \(41\text{ cm}\). He experimentally compared the crate's height against the centimeter markings of an instrument, so his value comes from a carried-out comparison. Sara's "roughly \(40\text{ cm}\)" is an estimate — often useful, but produced by judgment rather than by performing the comparison.

<!-- card-id: 10dd8e1b-b2c6-410b-b66c-9cc757ba5fba -->
Q: The **measurand** is the particular quantity a measurement is intended to determine, stated precisely enough that everyone would measure the same thing: which object, which property, and under which relevant conditions. A helper is told only "measure the height". The room contains a crate whose lid is standing open. Name one way this instruction fails to specify a measurand.
A: Any one of these: it does not name the object (the height of *what*?), or the condition (lid open or closed? — with the lid open, the "height" could include the raised lid). A measurand statement such as "the height of the crate, lid closed, from the floor to the top edge" removes those choices.

<!-- card-id: c56da2b9-5428-4a3a-8cae-3a2f3c73d2f7 -->
Q: An **observation** is any record of something noticed about a system; it may be purely descriptive. A measurement is the special kind of observation that produces a quantity value. A notebook holds two entries about the same crate: "taller than the stool beside it" and "height \(41\text{ cm}\), read from a ruler held upright beside it". Both are observations. What does the second entry provide that the first does not?
A: A quantity value — a number with a unit, obtained by comparison with an instrument's unit markings. The descriptive entry only orders two particular objects; the measured value can be compared with any other height report, rechecked, and used in calculation.

## Models and assumptions

<!-- card-id: b4b274e7-4c73-40bc-9614-0c34a316c0d2 -->
Q: To reason about a system, physics replaces it with a **physical model**: a deliberately simplified stand-in that keeps only the features the question needs and ignores the rest. To decide whether the crate fits under a workbench, you draw the crate as a plain rectangle with only its height written beside it — no color, no texture, no contents. What makes this drawing a model rather than a picture meant to look like the crate?
A: It is built for a purpose. It keeps exactly the feature the fit question needs — the height, as one labeled length — and deliberately leaves everything else out. A picture tries to show how the crate looks; a model tries to make the question easy to answer correctly.

<!-- card-id: 3eadac7a-555b-4b88-b4ff-fd90a1e43a01 -->
Q: A learner studies whether a crate fits under a workbench, using a rectangle drawing labeled "height \(41\text{ cm}\)". In this situation, which thing is the system and which is the model?
A: The system is the real crate together with the space under the workbench — the chosen part of the world. The model is the labeled rectangle drawing — the simplified stand-in used for reasoning. The drawing can be mistaken, redrawn, or thrown away; the crate itself does not change.

<!-- card-id: 71da68d5-89e2-4c83-8ff4-97b0a7f68780 -->
Q: A model rests on **assumptions**: conditions accepted as true while the model is used, without being rechecked each time. The crate-fit model treats the crate as **rigid** — keeping its shape, neither bending nor squashing. Suppose the "crate" is actually a soft fabric storage cube. Which assumption of the fit model does this threaten?
A: The rigidity assumption. A soft cube can squash or bulge, so its measured unloaded height may not be the height it has while being pushed into place — and then comparing that one fixed value with the opening no longer settles the fit. A model's answer is only trustworthy while its assumptions hold.

<!-- card-id: 8399d662-a65a-44dc-b6f0-74aae19e6038 -->
Q: Whether a detail belongs in a model depends on the question, not on how eye-catching the detail is. A crate has bright warning stickers, and a handle that sticks out \(3\text{ cm}\) from one side. For the question "Will the crate fit sideways through the doorway?", which of these two details must the model keep, and why that one?
A: The protruding handle. It makes the crate effectively \(3\text{ cm}\) wider on that side, and how wide the crate is at its widest is exactly what the doorway comparison uses. The stickers change only appearance, so this model can ignore them — though for a different question, such as whether a warning will be noticed, the relevant detail would reverse.

## Predictions and tests

<!-- card-id: dc9e1660-2b5e-4a3d-a60a-86c572935ce9 -->
Q: A **model prediction** is a definite statement, worked out from the model and its assumptions, of what should be observed or measured in the real system. A shelf model says: the shelf has \(3\) rows of \(4\) jar slots each, every slot holds exactly one jar, and every slot is usable. What does this model predict a careful count will find when the shelf is completely full?
A: \(12\) jars, because \(3\times4=12\). If the model and its assumptions describe the shelf correctly, a count of the completely filled shelf should find exactly this number.

<!-- card-id: 20595df8-cf88-4211-846e-9a28216fb4cd -->
Q: A **model test** compares a prediction with what is actually observed or measured in the system — and the comparison only counts as a test if it could come out either way. You completely fill the real shelf and count the jars. Why is comparing this count with the predicted \(12\) a genuine test of the shelf model?
A: Because the count comes from the real shelf, independently of the model, and nothing forces it to equal \(12\): a blocked slot or an extra-wide jar would make it differ. Agreement supports the model; disagreement counts against it. A comparison that could never disagree would test nothing.

<!-- card-id: 4247702d-7977-41f4-95e0-4f24ad018b25 -->
Q: The shelf model predicted \(12\) jars; a careful count of the completely filled shelf finds \(10\). What is the strongest conclusion this mismatch supports on its own?
A: Only that something in the modeling of this shelf is wrong: at least one assumption fails (perhaps not every slot is usable, or one jar per slot is wrong), or the count itself went wrong. The mismatch by itself does not say *which* part failed — identifying the cause needs further checking, such as recounting or inspecting the slots.

## From situation to schematic

<!-- card-id: 61281564-a563-4778-b20b-81ffee4f1813 -->
Q: A model is often drawn as a **schematic**: a simplified technical drawing that shows only the needed shapes and their measured values. Two conventions: a double-headed arrow marks the distance between its two ends, labeled with a measured quantity value; and the note "not to scale" warns that drawn sizes may not match real proportions, so trust the labels, not the picture. The measured values below are heights of the rigid box (lid closed) and of the open shelf gap.

![Schematic labeled not to scale: a rectangular box with a vertical double-headed arrow labeled twenty-nine centimeters stands beside two shelf boards whose gap carries a vertical double-headed arrow labeled thirty-one centimeters. In the drawing the box appears slightly taller than the gap.](../figures/01_systems_quantities_and_models/upright-fit-model.svg)

The model's rule: a rigid box standing upright fits into the gap if the box height is less than the gap height. What does the model predict here, and which information in the figure must you *not* use?
A: The box fits: \(29\text{ cm}<31\text{ cm}\), so the model predicts the upright box passes into the gap. You must not use the drawn sizes — the schematic is not to scale, and the box is deliberately drawn looking taller than the gap; only the labeled values carry measured information.

<!-- card-id: 67e1b5bd-7263-45c4-9a93-70af57714139 -->
P: A rigid wooden board, measured upright with height \(62\text{ cm}\), is to be slid upright into a cabinet opening whose measured height is \(60\text{ cm}\). Use the upright-fit model — a rigid object standing upright fits into an opening if the object's height is less than the opening's height — to state the model's prediction, and check the reasoning.
S: **IDENTIFY:** The system is the board plus the cabinet opening. The measurands are two heights, both already measured: board \(62\text{ cm}\), opening \(60\text{ cm}\). The model is the upright-fit rule with its rigidity and upright-position assumptions.

**PLAN:** Compare the two quantity values, which share the same unit, using the less-than test.

**EXECUTE:** Is \(62\text{ cm}<60\text{ cm}\)? No — \(62>60\). The model predicts the board does *not* fit upright in the opening.

**EVALUATE:** Both values are in centimeters, so the comparison is valid without conversion, and the board exceeds the opening by \(2\text{ cm}\) — a clear margin, not a borderline case. The prediction holds only within the model's assumptions: a rigid board kept upright. Tilting or bending the board lies outside this model, so the model says nothing about those options.
