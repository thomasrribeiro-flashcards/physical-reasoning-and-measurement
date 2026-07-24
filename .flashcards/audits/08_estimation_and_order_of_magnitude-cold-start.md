# Cold-start audit — Chapter 8: Estimation and order of magnitude

Learner contract (frozen from the CLI-resolved closure): scheduled cards of
local chapters 01–07 (07 in full; 01–06 as validator-resolved capability
summaries) and the staged external closures of
`mathematics/elementary-algebra-and-functions` and
`mathematics/quantitative-reasoning-and-arithmetic` (arithmetic chapter 10 in
full, earlier chapters as capabilities). Assumed tools: none. No inbound edge
was added during authoring; the chapter frontmatter declares only
`chapter:07_dimensions_and_derived_quantities`, matching the resolution.

Frontier decisions fixed before drafting: scientific notation and negative
exponents are not inbound (reserved to this chapter by the Chapter 2 ledger,
taught here only for values ≥ 1 with whole-number exponents); square roots are
not inbound, so the order-of-magnitude boundary is bridged as 3 × 3 ≈ 10;
everyday size anchors come only from the arithmetic chapter 10 benchmarks.

## Front-by-front dependency ledger

| Concept, symbol, or representation | Required on which front? | Allowed inbound source or earlier establishment | First supported retrieval | Later application | Status |
|---|---|---|---|---|---|
| estimate; reference value | 08-01 | defined on the 08-01 front itself | 08-01 | 08-02 onward, all problems | ok |
| door ≈ 2 m anchor | 08-01 | supplied and justified on the front (door-handle ~1 m benchmark makes it plausible; value restated wherever used) | 08-01 | 08-02, 08-08 | ok |
| corridor, tape measure | 08-01, 08-09 | measurement procedures capability (ch3) plus everyday scene | — | 08-09, 08-12 | ok |
| reading countable structure + scale from a drawing | 08-02 (figure) | scale-factor capability (ch6); figure shows only shapes, no numbers | 08-02 | 08-15–08-17 (anchor selection) | ok |
| decomposition into anchorable factors | 08-03 | defined on the 08-03 front | 08-03 | 08-04, 08-10, 08-15–08-18 |ok |
| sheets/cm slash unit; unit cancellation | 08-03 | slash notation and cancellation established in ch7 (07-01, 07-02); sheets/cm is a new instance of the established grammar | 08-03 | 08-15–08-17 | ok |
| 100 cm = 1 m; 1000 mL = 1 L; 1000 g = 1 kg | 08-03, 08-15 | arithmetic conversion capabilities (ch10 and earlier) | — | 08-11, 08-15 | ok |
| sample bulk volume including gaps | 08-04 | measurement and division capabilities are inbound; the front distinguishes bulk volume from water displacement | — | — | ok |
| whole-number powers, 10³ = 1000 | 08-05 | arithmetic `whole-number-power` capability; expanded on the front | 08-05 | 08-06 onward | ok |
| leading digit; power-of-ten form | 08-05 | defined on the 08-05 front | 08-05 | 08-06, 08-10, 08-12, 08-16–08-18 | ok |
| order of magnitude; factor-scale rounding at ~3 | 08-06 | defined on the front; boundary bridged as 3 × 3 = 9 ≈ 10 (no square roots) | 08-06 | 08-07, 08-14, 08-18 | ok |
| scale ladder; equal step = ×10 | 08-07 (figure) | bridged on the front ("equal spacing is honest because each step means the same factor"); log-axis honesty owed by the ch2 ledger is settled here | 08-07 | 08-14, 08-18 | ok |
| fingernail ≈ 1 cm; city block ≈ 100 m; bathtub ≈ 200 L | 08-07, 08-14, 08-15, 08-17 | arithmetic ch10 benchmark cards (fingernail, ten-blocks ~1 km, bathtub) | — | same fronts | ok |
| lower bound, upper bound, bracket | 08-08 | defined on the 08-08 front | 08-08 | 08-09–08-11, 08-15–08-17 | ok |
| contrast with measured uncertainty interval | 08-08 (answer) | mean-and-uncertainty capability (ch4), named only to fence it off | — | — | ok |
| number-line interval reading | 08-09 (figure) | arithmetic number-line and ch5 graph-reading capabilities | — | — | ok |
| bound propagation through a product | 08-10 | monotonic product rule stated and justified on the front | 08-10 | 08-11, 08-15–08-17 | ok |
| ±10–20% uncertainty phrasing | 08-10 (answer) | `percent` capability (arithmetic ch9, in the staged closure) | — | — | ok |
| decision line; both-bounds-same-side rule | 08-11 | defined on the 08-11 front | 08-11 | 08-17 EVALUATE | ok |
| false precision; digits beyond input quality | 08-12 | resolution/reported-digits capability (ch3, ch4); rule restated for estimates | 08-12 | 08-16 (trim to 2 × 10⁴) | ok |
| cm², m², 1 m² = 10 000 cm² | 08-12 | ch7 (07-05, 07-09) | — | — | ok |
| assumptions reported with the result; estimate as model | 08-13 | `physical-model`, `model-assumption` capabilities (ch1) | 08-13 | 08-15 EVALUATE | ok |
| order-of-magnitude audit; reject-never-confirm | 08-14 | defined on the front; parallels ch7 unit-check limit (07-14) | 08-14 | 08-18 | ok |
| density of water 1.0 g/mL; mass = volume × density | 08-15 | ch7 (07-04, 07-15) | — | — | ok |
| 60 min/h; 24 h/day; rate × time | 08-16 | arithmetic time-unit capabilities; ch7 rate × time (07-02); 24 h/day everyday calendar knowledge | — | — | ok |
| bare count carries no unit | 08-17 | ch7 (07-03), restated in EXECUTE | — | — | ok |
| defensibility test between rival estimates | 08-18 | assembled from 08-01 (checkable comparison) and 08-14 (audit) | 08-18 | — | ok |

## First-use scan

Every technical term on a Chapter 8 front is inbound, established by an
earlier Chapter 8 card, or defined at its own first use on the same front;
figures carry no numeric labels that would pre-answer their cards
(building-floors shows proportions only; scale-ladder's rung labels are the
given data, not the counted answer; bracket-comparison shows the supplied
intervals and reading). New chapter vocabulary follows the
explain → supported retrieval → application micro-sequence: estimate/reference
value (08-01 → 08-02 → problems), decomposition (08-03 → 08-04 → problems),
power-of-ten form (08-05 → 08-06 → 08-18), order of magnitude
(08-06 → 08-07 → 08-14/08-18), bounds (08-08 → 08-09/08-10 → problems),
honest reporting and audit (08-12/08-13/08-14 → problems). No front borrows
later-chapter material; no blocked rows remain.

cold_start_status: pass
unresolved_dependencies: 0
