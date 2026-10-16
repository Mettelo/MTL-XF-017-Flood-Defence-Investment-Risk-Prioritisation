# MTL-XF-017 — Flood Defence Asset, Investment & Risk Prioritisation Intelligence

**Mettelo Project Studio**  
**Project ID:** MTL-XF-017  
**Project Type:** Cross-Functional Environmental & Capital Investment Analytics · Team project · Production-style portfolio project  
**Client:** Confidential Regional Flood & Climate Resilience Authority  
**Sector:** Environment / Flood Risk / Capital Investment  
**Engagement Type:** Simulated confidential-client engagement  
**Status:** Pre-launch  
**Recommended Team Size:** 6–8  
**Delivery Window:** 8 weeks  
**Master Repository:** Mettelo-controlled

> **Confidentiality Notice**  
> The client identity is intentionally withheld. This is a simulated Mettelo Project Studio engagement built around official public/open data. Participants must not represent the simulated client as a real external Mettelo customer.

## Challenge

A regional authority has more flood-defence maintenance and resilience needs than available capital. Programme and funding data exists, but leaders need a transparent way to understand the portfolio, identify schemes that warrant deeper review and distinguish evidence gaps from genuine investment signals.

Your team will work as a multidisciplinary delivery team rather than as a group of people independently producing charts.

The engagement combines business analysis, data governance, data engineering, analytics, BI/decision support, assurance and specialist roles relevant to the project.

## Commissioned Decision

> **Which flood-defence schemes or asset interventions should receive the earliest investment attention, and where is the current evidence insufficient to justify prioritisation?**

A successful submission must help structure or support this decision. A dashboard without governed definitions, reproducible data, analytical evidence and a defensible decision framework is not sufficient.

## Official Data Source

**Environment Agency Flood and Coastal Erosion Risk Management investment programme open data**

Official publisher/source:

https://environment.data.gov.uk/asset-management/doc/about

The project uses a frozen Mettelo cohort copy/reference of the approved source wherever licensing and file-size rules permit. Teams should not depend on a live website or API remaining unchanged.

See:
- [Data workspace](data/README.md)
- [Source register](data/SOURCE_REGISTER.md)
- [Raw data folder](data/raw/)

## Core Objective

Build a reproducible cross-functional solution that:

1. build a governed scheme and investment analytical model;
2. standardise scheme, status, funding and geography fields;
3. reconcile the selected programme scope and total funding;
4. analyse funding concentration, delivery timing and regional patterns;
5. identify evidence gaps that prevent robust prioritisation;
6. develop transparent scenario-based scheme review logic;
7. build capital-programme BI;
8. complete assurance, UAT and technical handover;

## Key Business Questions

- Which schemes account for the largest funding commitments?
- Where are programme delivery and funding pressures concentrated?
- Which schemes warrant deeper review based on transparent portfolio factors?
- How sensitive are priorities to different weighting assumptions?
- What engineering or benefit-cost evidence is still missing?

## Required Delivery Flow

```text
Discovery & stakeholder understanding
        ↓
Business requirements & acceptance criteria
        ↓
Data governance & source control
        ↓
Data ingestion & analytical modelling
        ↓
Data quality, reconciliation & exceptions
        ↓
KPI definition
        ↓
Core analysis
        ↓
Decision / prioritisation framework
        ↓
BI / decision-support product
        ↓
Assurance & UAT
        ↓
Executive recommendation
        ↓
Technical & operational handover
```

## Cross-Functional Team Model

The exact allocation can vary by team, but the project should demonstrate meaningful contribution across:

- Business Analysis;
- Data Governance;
- Data Engineering;
- Data Analysis / Domain Analysis;
- BI Development;
- Risk, Assurance or QA;
- specialist roles defined in the project brief;
- Data Science / AI or Model Governance where applicable.

One person may cover more than one function in a smaller team, but ownership and evidence must remain explicit.

## Minimum Delivery Standard

The final repository must demonstrate:

- traceable stakeholder requirements;
- governed metric and field definitions;
- frozen source/version documentation;
- reproducible data preparation;
- row/value reconciliation;
- explicit data-quality exceptions;
- project-specific analysis;
- transparent decision/prioritisation logic;
- governed BI measures;
- user acceptance testing;
- technical handover;
- visible GitHub collaboration;
- clear individual contribution evidence.

## Important Interpretation Rules

- Funding allocation is not a direct measure of flood-risk reduction.
- Do not present the prioritisation as an official Environment Agency ranking.
- Do not infer community vulnerability from geography alone.
- Flag schemes with insufficient critical fields instead of silently scoring them.
- Separate portfolio evidence from engineering judgement.

## Agreed Success Standard

The engagement is considered successful only when:

- the approved frozen source can be identified and obtained;
- curated outputs can be regenerated from code/instructions;
- material exclusions and data-quality issues are quantified;
- headline KPIs reconcile to the curated analytical model;
- analytical conclusions answer the commissioned business questions;
- decision rules and thresholds are visible and challengeable;
- at least five headline dashboard measures reconcile to underlying data;
- UAT and assurance evidence is present;
- each member's contribution can be evidenced;
- a reviewer can reproduce the team's core outputs without undocumented manual changes.

Detailed sign-off tests are defined in:

- [Acceptance Criteria](project/ACCEPTANCE_CRITERIA.md)
- [Deliverables](project/DELIVERABLES.md)

## Repository Purpose

This master repository is the official Mettelo source of truth for:

- project scope and challenge;
- business context;
- approved data/source information;
- governance requirements;
- deliverables;
- acceptance criteria;
- team repository standards;
- final submission instructions.

Teams use this repository as the specification. Their delivery work is completed in their own team repository under the Mettelo GitHub organisation.

## Repository Structure

```text
.
├── README.md
├── project/
│   ├── README.md
│   ├── PROJECT_BRIEF.md
│   ├── BUSINESS_CONTEXT.md
│   ├── DELIVERABLES.md
│   ├── ACCEPTANCE_CRITERIA.md
│   └── GOVERNANCE.md
├── data/
│   ├── README.md
│   ├── SOURCE_REGISTER.md
│   ├── raw/
│   ├── reference/
│   └── metadata/
└── submission/
    ├── README.md
    ├── TEAM_REPOSITORY_STANDARD.md
    ├── SUBMISSION_GUIDE.md
    └── FINAL_SUBMISSION_TEMPLATE.md
```

## Start Here

### 1. Understand the engagement
- [Project Brief](project/PROJECT_BRIEF.md)
- [Business Context](project/BUSINESS_CONTEXT.md)

### 2. Understand what must be delivered
- [Deliverables](project/DELIVERABLES.md)
- [Acceptance Criteria](project/ACCEPTANCE_CRITERIA.md)

### 3. Understand governance and data
- [Governance](project/GOVERNANCE.md)
- [Data Workspace](data/README.md)
- [Source Register](data/SOURCE_REGISTER.md)

### 4. Create the team delivery repository
- [Team Repository Standard](submission/TEAM_REPOSITORY_STANDARD.md)
- [Submission Guide](submission/SUBMISSION_GUIDE.md)
- [Final Submission Template](submission/FINAL_SUBMISSION_TEMPLATE.md)

## Team Submission Model

Each project team creates its delivery repository **under the Mettelo GitHub organisation**.

Recommended naming:

`MTL-XF-017-<team-name>`

The Team Lead adds every team member using their individual GitHub account.

Teams should use issues, branches, meaningful commits, pull requests and reviews where practical as evidence of collaborative delivery.

The team repository is the official delivery artefact. The master Mettelo repository remains the source of truth for the challenge specification.

## Final Review

The team presents to a Mettelo review panel acting as the simulated senior stakeholder group.

The panel may challenge:

- problem framing;
- requirements;
- data provenance;
- quality rules;
- metric definitions;
- analytical logic;
- thresholds;
- modelling assumptions;
- decision framework;
- dashboard usability;
- recommendations;
- limitations;
- reproducibility;
- contribution evidence.

A polished presentation does not compensate for weak evidence, unreproducible analysis or unclear ownership.

---
**Mettelo — Built for What’s Next**
