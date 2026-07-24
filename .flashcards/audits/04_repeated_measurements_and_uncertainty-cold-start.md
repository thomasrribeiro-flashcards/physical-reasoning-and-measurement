# Chapter 4 cold-start audit — repeated measurements and uncertainty

Isolated chapter build, 2026-07-24. Learner contract: Chapter 3 scheduled
cards in full; Chapter 1–2 validator capability summaries; scheduled external
closure of `mathematics/elementary-algebra-and-functions` (variables,
substitution, evaluation) and `mathematics/quantitative-reasoning-and-arithmetic`
(arithmetic, decimals, fractions/halving, signed quantities, number lines,
ratios, percents, measurement chapter: units, conversion, scale reading,
precision claims, rounded-value intervals, reasonableness, IPEE headings).
No tools assumed. Everything else is treated as unseen.

## Chapter dependency ledger

| Concept, symbol, or representation | Required on front | Inbound source or establishment | First supported retrieval | Later application | Status |
|---|---|---|---|---|---|
| Procedure, ruler, mm divisions, two-reading method, eye square to scale | 04-01 onward | Chapter 3 scheduled cards | inbound | 04-11, 04-16, 04-19 | confirmed inbound |
| Measurand, measurement, quantity value | 04-03 onward | Chapter 1 capability summary | inbound | throughout | confirmed inbound |
| cm, mm, mL, g units and notation | 04-01 onward | Chapter 2 summary + external measurement chapter | inbound | throughout | confirmed inbound |
| Number line with labeled/unlabeled marks | 04-02 | external arithmetic closure (number lines, scales) | inbound | 04-06, 04-13 | confirmed inbound |
| Decimals, addition, division, halving | 04-04, 04-05 | external arithmetic closure | inbound | problems | confirmed inbound |
| Rounded reading stands for a band of true values | 04-07, 04-09 | external `rounded-value-interval` card | inbound | 04-09 | confirmed inbound |
| Precision claim of the last written place; false precision | 04-10 | external precision card + ch3 false-precision cards | inbound | 04-19 | confirmed inbound |
| Parallax mechanism | 04-03, 04-12 | Chapter 3 parallax card | inbound | 04-16 | confirmed inbound |
| Zero error / broken tip / bent end | 04-11 | Chapter 3 zero-error card | inbound | 04-18, 04-19 | confirmed inbound |
| Resolution; digital balance; container mL scale | 04-06, 04-09, 04-17 | Chapter 3 cards | inbound | problems | confirmed inbound |
| IPEE headings | 04-16 back onward | scheduled arithmetic problem cards; ch3 problems | inbound | 04-16 through 04-19 | confirmed inbound |
| Repeat variation | 04-01 onward | 04-01 front defines it in ordinary language | 04-01 | 04-03, 04-05, 04-06 | established |
| Dot plot (dots above a number line; stacking) | 04-02 onward | 04-02 front supplies the grammar before the reading | 04-02 | 04-06, 04-16 | established |
| Cluster / stray reading | 04-02 onward | 04-02 front and answer | 04-02 | 04-03, 04-16 | established |
| Mistake; exclusion-needs-a-cause rule | 04-03 onward | 04-03 front defines mistake; answer states the rule | 04-03 | 04-16, 04-19 | established |
| Best value; mean | 04-04 onward | 04-04 front defines mean from inbound add/divide | 04-04 | 04-10, 04-11, problems | established |
| Range of readings; half-range; contrast with instrument range | 04-05 onward | 04-05 front defines and disambiguates | 04-05 | 04-09, problems | established |
| Measurement uncertainty; uncertainty interval; ± sign | 04-07 onward | 04-07 front defines all three | 04-07 (interval claim), 04-08 (notation) | 04-09 through 04-19 | established |
| Resolution floor on uncertainty | 04-09 | 04-09 joins inbound resolution band to 04-07 uncertainty | 04-09 | 04-16 EVALUATE | established |
| Consistent rounding rule | 04-10 | 04-10 answer states the rule from inbound false precision | 04-10 | 04-16, 04-19 | established |
| Averaging tames scatter, not constant shifts | 04-11 | 04-11 front poses it; answer explains cancellation | 04-11 | 04-12, 04-18, 04-19 | established |
| Random error; systematic error | 04-12 onward | 04-12 front defines both names for behaviors seen in 04-01/04-11 | 04-12 | 04-18, 04-19 | established |
| Agreement as interval overlap | 04-13 onward | 04-13 front states the rule; figure carries the decision | 04-13 | 04-14, 04-18 | established |
| Consistency versus equality; gap as decisive outcome | 04-14 | builds only on 04-13 | 04-14 | 04-18 | established |
| Uncertainty judged for a purpose | 04-15 | 04-15 front frames the fit decision with established intervals | 04-15 | future chapters | established |

Blocked dependencies: none. Rejected framings: stopwatch/timing examples
(instrument never established), standard deviation and "average of many
trials converges" claims (formal statistics excluded from this deck),
axis-based scatter graphs (Chapter 5 grammar), and a "true value known by
authority" example (would contradict the deck's treatment of true values as
unknown).

## Front-by-front scan

Fronts were read in order and each dependency recorded before the answer was
inspected.

- **04-01** — needs procedure/ruler/two-reading/eye-square vocabulary (ch3
  inbound) and decimals (external). Defines repeat variation on the front. No
  unexplained term.
- **04-02** — needs number line (external) and 04-01's readings context; dot
  plot grammar bridged on the front; the figure's alt text describes layout
  without leaking the cluster bounds. Pass.
- **04-03** — needs cluster (04-02), parallax mechanism (ch3), measurand
  (ch1 summary); defines mistake on the front. Pass.
- **04-04** — defines mean from inbound addition/division; readings supplied.
  Pass.
- **04-05** — defines range of readings and explicitly disambiguates from
  ch3's instrument range (interference pair handled at first use). Pass.
- **04-06** — needs digital balance and g (ch3/external), dot plot (04-02),
  spread language (04-01, 04-05). Figure read is the task. Pass.
- **04-07** — needs rounded-band idea (external rounded-value interval, in
  established ordinary words), half-range (04-05), mean/best value (04-04);
  defines uncertainty, interval, and ± on the front. Pass.
- **04-08** — cloze; visible text uses only 04-07 vocabulary; single
  deletion "uncertainty" is uniquely determined and not revealed elsewhere in
  the block. Pass.
- **04-09** — needs mm divisions and nearest-division reading (ch3), range
  (04-05), uncertainty (04-07). Pass.
- **04-10** — needs mean (04-04), half-range (04-05), false precision (ch3).
  Pass.
- **04-11** — needs broken-tip zero error and two-reading method (ch3), mean
  (04-04). Pass.
- **04-12** — needs liquid-level scale reading and parallax (ch3),
  scatter/mean behavior (04-01, 04-11); defines the two standard names on the
  front. Pass.
- **04-13** — needs uncertainty intervals (04-07); agreement rule stated on
  the front; figure labels give the ± values as setup, and the alt text leaves
  the overlap judgment to the learner. Pass.
- **04-14** — needs agreement/overlap (04-13). Pass.
- **04-15** — needs interval reasoning (04-07); slot treated as exact is
  stated on the front as a bounded idealization. Pass.
- **04-16** (P) — needs 04-02 through 04-05, 04-07, 04-10; the slip cause is
  supplied on the front, matching the 04-03 rule. Full IPEE; direct result
  first in EXECUTE. Pass.
- **04-17** (P) — needs mL container scale (ch3) and the 04-16 method; faded
  support with all four headings. Pass.
- **04-18** (P) — needs agreement (04-13, 04-14), systematic error (04-11,
  04-12), balances (ch3). Pass.
- **04-19** (P) — needs exclusion rule (04-03), rounding rule (04-10),
  systematic-shift rule (04-11), tape and bent end (ch3). Pass.

## Notes for the maintainer

- The validator reports three prerequisite-resolution errors that predate and
  are unrelated to this chapter: the isolated sandbox cannot resolve the real
  filesystem path of `mathematics/elementary-algebra-and-functions`, so
  Chapter 1's two external concept edges fail to resolve *inside the sandbox
  only*. The machine-resolved graph supplied to this run lists both edges as
  valid. No metadata was changed; rerun validation in the real workspace.
- Chapter-4 files validate with 0 parser, KaTeX, image, identity, markup,
  cloze, and frontmatter issues; `git diff --check` is clean; all three
  figures compile from TikZ with title/desc metadata and compact centered
  coordinates.

cold_start_status: pass
unresolved_dependencies: 0
