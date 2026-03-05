# Search Quality Evaluation Dashboard

This dashboard summarizes labeled queries and example evaluations in this repository.

---

## Dataset Overview

Total queries: 100

Intent distribution (approx):
- Informational: 35
- Navigational: 12
- Transactional: 18
- Local: 15
- YMYL: 20

---

## Key Evaluation Principles

1) Intent match is the first priority  
2) Trustworthiness is critical for YMYL  
3) Freshness matters for time-sensitive queries (prices, weather, scores)  
4) Local queries should prefer map packs, hours, directions, and proximity  

---

## Sample Quality Signals

High quality results typically include:
- clear match to user goal
- credible source and transparent authorship
- minimal effort required
- updated info when relevant

Low quality results often show:
- clickbait titles
- aggressive ads / popups
- vague or copied content
- unsupported medical/financial claims

---

## Next Expansion Ideas

- Add 20 more evaluations using the same rubric
- Create a "hard cases" folder: mixed intent, ambiguous queries, and borderline trust
- Add a second rater simulation to test inter-rater agreement
