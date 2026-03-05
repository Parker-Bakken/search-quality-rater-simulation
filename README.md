# Search Quality Rater Simulation

Simulates professional Search Quality Rater workflows:
- intent interpretation
- result usefulness
- trust / authority signals
- YMYL sensitivity
- freshness needs
- clear justifications with consistent rubric application

## Quick start (review order)
1) `rating-framework/` — rubric + rating scale
2) `templates/` — evaluation template
3) `examples/` — rated SERP-style examples + rationales
4) `dataset/` — labeled dataset + QA scorecard
5) `analysis/` — summary notes + consistency checks
6) `gold/` — adjudicated edge cases (added)
7) `reports/scorecard.md` — quick metrics + findings (added)

## Additions that set this apart
- QA log: `qa/qa_log.csv`
- Gold set: `gold/gold_set.csv`
- Calibration notes: `calibration.md`
