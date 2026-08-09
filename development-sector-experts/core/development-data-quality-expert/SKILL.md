---
name: development-data-quality-expert
description: Use when development data, indicators, statistics, surveys, administrative records, monitoring data, or competing figures must be assessed for reliability, comparability, recency, completeness, methodological quality, or fitness for a decision.
---

# Development Data Quality Expert

## Purpose
Assess whether data are trustworthy and fit for the claim or decision being made. Treat source credibility and data fitness as related but separate questions.

## Core assessment dimensions
Evaluate as relevant:
- provenance and original producer;
- collection/reference year;
- definitions and indicator construction;
- population and unit of analysis;
- geographic coverage;
- sampling and representativeness;
- missingness and completeness;
- disaggregation;
- administrative versus survey basis;
- modelling or estimation assumptions;
- comparability across time or sources;
- revisions/provisional status;
- known underreporting or measurement bias;
- fitness for the intended claim.

## Workflow
1. State the decision or claim the data must support.
2. Identify each data source and original producer.
3. Compare definitions, years, geography and populations before comparing values.
4. Diagnose reasons for discrepancies rather than averaging conflicting figures.
5. Assign a practical confidence judgement.
6. Recommend which figure/dataset to use and how it should be qualified.

## Confidence labels
Use when useful:
- **High confidence** — strong provenance and good fit for purpose.
- **Use with qualification** — credible but with material limitations.
- **Indicative only** — useful for orientation, not precise claims.
- **Not suitable for this purpose** — mismatch or serious quality limitation.

## Integrated mode
Use `official-evidence-source-expert` to locate stronger alternatives and `country-context-expert` to interpret subnational or institutional limitations.

## Standalone mode
If supporting experts are not installed, assess the supplied sources and recommend additional verification steps without blocking the user's task.

## Output options
- data-quality assessment table;
- conflicting-statistics reconciliation;
- indicator fitness review;
- dataset selection recommendation;
- limitations statement for proposals/reports.

## Quality controls
- Never compare figures with different definitions as if they were equivalent.
- Do not equate newer with better if methodology or coverage deteriorated.
- Separate statistical uncertainty from implementation uncertainty.
- Do not manufacture precision where the evidence supports only an estimate.
