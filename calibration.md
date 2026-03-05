# Calibration & QA (Search Rating)

## Goal
Keep ratings consistent across similar query types and edge cases.

## Workflow
1) Rate using the rubric in `rating-framework/`
2) QA spot-check a subset (10–20%)
3) Log disagreements in `qa/qa_log.csv`
4) Adjudicate final rating + update rubric notes
5) Add edge cases to `gold/gold_set.csv`

## Common disagreement categories
- intent mismatch vs partial satisfaction
- trustworthiness vs usefulness tradeoff
- YMYL severity thresholds
- freshness requirements
