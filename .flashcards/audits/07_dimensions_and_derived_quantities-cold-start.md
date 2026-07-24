# Cold-start audit — Chapter 7: Dimensions and derived quantities

Isolated build. Inbound frontier at resolution: Chapter 6 fully scheduled
cards; Chapters 1–5 as capability summaries; external decks
`mathematics/elementary-algebra-and-functions` and
`mathematics/quantitative-reasoning-and-arithmetic` as staged capability
summaries. Only Q:/A:, C:, and P:/S: blocks count as scheduled; no edge was
added beyond the machine-resolved graph.

## Concept-dependency ledger

| Concept used on a front | Status | Source |
|---|---|---|
| Pouring rate in words ("20 mL per second"), 600 mL constant-product data | inbound | ch6 (06-11, filling trials) |
| Constant of proportionality, d = kV water-depth row, m = 5.2 n coin equation | inbound | ch6 (06-02, 06-03, water-depth table 06-07) |
| Direct proportion, doubling test, ratio constancy | inbound | ch6 |
| Variable, equation, substitution | inbound | algebra summary |
| Division, fractions, cancellation of equal factors, whole-number powers | inbound | arithmetic summary |
| Array representation (rows × columns count) | inbound | arithmetic summary |
| Units mL, L, g, s, min, h, mm, cm, m; unit conversion; 1 m = 100 cm | inbound | ch2 + arithmetic ch10 summary |
| Measurand, quantity value | inbound | ch1 summary |
| Resolution, reading wobble | inbound | ch3–ch4 summaries |
| Slash notation mL/s; derived quantity/unit | taught here | 07-01 (reserved for ch7 by the ch6 ledger — resolved) |
| Unit cancellation in arithmetic | taught here | 07-02 |
| Unit of a proportionality constant; counts carry no unit | taught here | 07-03 |
| Density | taught here | 07-04 (in scope; not on the deck exclusion list) |
| Area and cm²; volume-by-cubes and cm³ | taught here | 07-05, 07-06 (geometry deck is NOT an edge; built from array counting + powers) |
| 1 mL = 1 cm³ | taught here | 07-07, drilled 07-08 |
| Squared conversion factor | taught here | 07-09 |
| Dimension (kind of quantity); disambiguation from drawing "dimensions" | taught here | 07-10 |
| Same-dimension addition rule | taught here | 07-11 |
| Same unit ≠ same measurand | taught here | 07-12 |
| Unit check of equations; reject-only limit | taught here | 07-13, 07-14 |

No concept on any front lacks a source; no proposed inbound edge was needed
beyond the resolved graph.

## Front-by-front scan

- **07-01** (a5f4fa18): front teaches slash notation and "derived quantity"
  in place before asking for use. Needs only mL, s, division, and the ch6
  spelled-out rate context. Clean.
- **07-02** (2f43ee87): front states the unit-algebra rule it exercises;
  mL/s from 07-01; fraction cancellation inbound. Clean.
- **07-03** (8f622975): d = kV and the 200 mL / 3.9 cm row are ch6 contexts;
  m = 5.2 n likewise; the counts-have-no-unit boundary is taught in the
  answer, not presupposed. Clean.
- **07-04** (28db4d8d): defines density on the front from direct proportion
  (ch6) before asking for computation; g and mL inbound. Clean.
- **07-05** (7cdaefaa): defines area, unit square, and cm² on the front;
  figure supplies the grid; array counting inbound. Power notation cm²
  anchored to cm × cm explicitly. Clean.
- **07-06** (5fb2cb23): volume familiar from mL (ch2); unit cube and cm³
  defined on the front; layer counting is array counting. Clean.
- **07-07** (2cf3c11c): needs cm³ (07-06), mL (inbound), and the idea of a
  conversion (ch2); states the exact equality on the front. Clean.
- **07-08** (bfafef57): cloze drills the token established by 07-07; single
  deletion, no brackets in math. Clean.
- **07-09** (1a382369): needs 1 m = 100 cm (inbound), cm² (07-05), powers
  (inbound); the flawed claim is quoted on the front, not assumed shared.
  Clean.
- **07-10** (8c1ff613): defines "dimension" on the front and explicitly
  disambiguates the drawing sense used since ch1; needs measurand (ch1),
  m/cm conversion (ch2), m² (07-05/07-09). Clean.
- **07-11** (cb8b46a5): needs unit conversion (ch2), dimension (07-10),
  division-builds-new-quantity (07-01); the 0.25 g/mL aside is computed in
  the front sentence itself. Clean.
- **07-12** (5dcc4c1a): needs resolution (ch3), measurand (ch1), mm (ch2);
  the trap is quoted. Clean.
- **07-13** (ffae85cf): states the same-unit-both-sides rule on the front;
  needs unit algebra (07-02) and fraction-division flip (inbound). Clean.
- **07-14** (d6f8d365): needs the check (07-13) and unitless pure numbers
  (07-03's boundary note, restated in the answer). Clean.
- **07-15** (5f9c20ca, P analyzed): needs density (07-04); the two-reading
  subtraction method is introduced inside IDENTIFY, not presupposed;
  wobble/resolution talk inbound from ch3–ch4. S: begins at IDENTIFY;
  EXECUTE opens with the direct result. Clean.
- **07-16** (f63a4faa, P faded): needs cancellation (07-02) and min/h
  conversion (inbound). Direct result first in EXECUTE. Clean.
- **07-17** (5948b0fd, P independent): needs 07-13/07-14; EVALUATE's 600 mL
  support data is ch6's. Direct result first. Clean.
- **07-18** (348f721e, P mixed): needs 07-13/07-14 plus ch6 doubling test;
  all three claims fully quoted on the front. Direct result first. Clean.

No front uses force, energy, motion vocabulary, or "speed"; no card
references later chapters or unavailable material.

## Chapter-boundary dependency ledger

- **Consumed from ch6 as promised:** slash notation slot (explicitly
  reserved by the ch6 ledger), rate contexts, proportionality constants,
  doubling/constant-product tests.
- **Outbound offers (provides):** derived-quantity, derived-unit,
  per-unit-rate-notation, unit-cancellation, proportionality-constant-unit,
  density, area-unit, volume-unit, milliliter-cubic-centimeter,
  squared-unit-conversion, dimension, same-dimension-addition,
  same-unit-different-quantity, dimensional-consistency,
  dimensional-check-limit — all established by scheduled cards above.
- **Deliberately not established here:** g/cm³ density notation (only g/mL
  used), m³, compound rates beyond volume/time, any named physical law.
  Future chapters must bridge these themselves.

cold_start_status: pass
unresolved_dependencies: 0
