# Measurement System Analysis (MSA) (DMAIC · Measure)

**Question:** can we trust the data before we use it as a baseline?

## Measurement under review
| Field | Details |
|---|---|
| KPI / measure | |
| Operational definition | |
| How it is recorded | Manual entry / System timestamp / Calculated |
| Source system | |

## Attribute agreement test (for pass/fail or category data)
Pick 20–30 real records. Ask 2–3 people to classify each one on their own, twice, without seeing earlier answers.

| Record | Expected (expert) | Appraiser A – trial 1 | A – trial 2 | Appraiser B – trial 1 | B – trial 2 |
|---|---|---|---|---|---|
| 1 | | | | | |

| Result | Formula | Value | Target |
|---|---|---|---|
| Repeatability (within appraiser) | same answer both trials / records | | ≥ 90% |
| Reproducibility (between appraisers) | all appraisers agree / records | | ≥ 90% |
| Accuracy (vs expert) | matches expected / records | | ≥ 90% |

## Data quality checks (for system data)
| Check | Result | Action |
|---|---|---|
| Missing values (% of records) | | |
| Duplicates | | |
| Default / placeholder values (e.g., 01-01-1900, "N/A") | | |
| Timestamps consistent (time zone, entry date vs. event date) | | |
| Same definition used by every team / site | | |
| Source-to-report reconciliation (N records traced) | | |

## Decision
- [ ] Measurement system acceptable: take the baseline
- [ ] Not acceptable: fix definitions / training / system, then re-test
