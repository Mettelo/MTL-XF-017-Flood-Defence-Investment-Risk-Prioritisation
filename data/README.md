# Data Guidance

## Approved Core Dataset

Use Environment Agency **Flood and Coastal Erosion Risk Management investment programme** open data.

Official source/documentation:
https://environment.data.gov.uk/asset-management/doc/about

Use the current approved **2026–27 capital/investment programme CSV** for the frozen cohort where available.

## What to Put in `data/raw/`

Store the original programme CSV unchanged:

```text
data/raw/
└── environment-agency-fcerm-capital-projects-2026-2027.csv
```

Record the exact download URL, acquisition date and file size in `SOURCE_REGISTER.md`.

## Core Scope

Use the full 2026–27 programme file for the core project.

Do not combine multiple programme years until:
- the current-year scheme model is working;
- scheme identifiers/status fields are understood;
- comparable fields are confirmed.

## Recommended Analytical Grain

Use:
**one row per scheme/project record** at the source grain.

If the source contains multiple rows per scheme:
- document why;
- define the aggregation rule;
- preserve the raw rows.

## Optional Historical Extension

For trend or programme-change analysis, teams may add one or more earlier programme files only after confirming comparable fields.

Recommended extension:
- current year plus previous 1–2 programme years.

## Optional Asset Enrichment

Environment Agency asset datasets may be added to enrich scheme context, but they are **not mandatory**.

Do not make the project dependent on a very large asset download if the business decision can be answered from the programme data.

## Geographic Guidance

Use the geography included in the programme source where available.

If coordinates or external boundaries are added:
- document the source;
- keep them in `data/reference/` or `data/processed/`;
- do not invent location precision.

## Large File Rule

If any optional Environment Agency asset file is too large for normal GitHub storage:
- keep it outside Git;
- record URL, filename, size, checksum and retrieval steps;
- commit only metadata/reference documentation.

## Assessment Baseline

The project must remain reproducible using the frozen 2026–27 programme file alone.
