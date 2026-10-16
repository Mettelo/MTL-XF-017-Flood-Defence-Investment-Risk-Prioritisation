# Project Brief

## Engagement Details
| Field | Detail |
|---|---|
| Project ID | MTL-XF-017 |
| Project Title | Flood Defence Asset, Investment & Risk Prioritisation Intelligence |
| Client | Confidential Regional Flood & Climate Resilience Authority |
| Sector | Environment / Flood Risk / Capital Investment |
| Duration | 8 weeks |
| Recommended Team Size | 6–8 |
| Primary Sponsor | Director of Flood & Coastal Risk Management |
| Senior Stakeholders | Capital Programme Lead, Asset Management Lead, Finance Business Partner, Climate Resilience Lead, GIS Lead, Data Governance Lead, Performance & Assurance Lead |
| Primary Dataset | Environment Agency Flood and Coastal Erosion Risk Management investment programme open data |

## 1. Client Situation
The authority has more flood-defence maintenance and resilience needs than available capital. Programme information exists, but leadership cannot consistently compare scheme readiness, funding allocation, regional concentration and evidence limitations within one governed prioritisation process.

## 2. Business Decision
> **Which flood-defence schemes or asset interventions should receive the earliest investment attention, and where is the current evidence insufficient to justify prioritisation?**

## 3. Agreed Objectives
1. Create a governed scheme/investment analytical model from the published programme data.
2. Define consistent scheme, geography, funding, delivery-status and programme fields.
3. Identify portfolio concentrations, delivery pressure and candidate schemes for deeper review.
4. Develop a transparent prioritisation framework that does not pretend open-data fields are a full engineering risk model.
5. Provide a capital-programme decision-support product with visible evidence gaps.

## 4. Key Business Questions
1. Which schemes account for the greatest funding commitments by geography/programme?
2. Where are delivery/funding pressures concentrated?
3. Which schemes appear high priority under transparent portfolio factors and which require more engineering evidence?
4. How sensitive is prioritisation to alternative weighting of funding, delivery timing and geographic factors?
5. What evidence is missing for a defensible risk-reduction or benefit-cost conclusion?
6. Which data-quality issues or status definitions could alter the portfolio view?

## 5. Cross-Functional Roles
| Role | Minimum expected output |
|---|---|
| Business Analyst | Define capital decision process, stakeholder needs, investment questions and acceptance criteria. |
| Data Governance Analyst | Govern scheme identifiers, status, funding, geography, lineage and DQ rules. |
| Data Engineer | Build reproducible programme-data ingestion and curated scheme model. |
| Flood Risk/Data Analyst | Own portfolio, funding, status and scheme-priority analysis. |
| GIS Analyst | Assess regional distribution and map only supported geography. |
| BI Developer | Build capital-programme portfolio and prioritisation views. |
| Investment/Risk Analyst | Challenge materiality, evidence gaps and prioritisation rules. |
| Assurance Analyst | Own reconciliation, scenario checks and UAT. |

## 6. Minimum Delivery Standard
Traceable requirements; governed definitions/lineage; preserved raw data; reproducible transformation; reconciliation; project-specific analysis; transparent decision logic; governed BI; UAT; handover; collaborative evidence.

## 7. Constraints
- Funding allocation does not equal flood-risk reduction or benefit-cost value.
- Open programme data may not include all engineering, asset-condition or community-vulnerability evidence needed for investment decisions.
- Scheme status and geography require consistent definitions.
- No prioritisation score may be presented as an official Environment Agency investment ranking.
- Geographic concentration must not be equated with community vulnerability without supporting data.

## 8. Agreed Success Criteria
- Every scheme in the curated model has a documented source identifier or explicit generated-key rule.
- Total funding in the curated model reconciles to the selected source scope after quantified exclusions.
- The project explicitly separates programme/funding indicators from engineering flood-risk measures.
- Any prioritisation score lists all factors and weights and includes at least three scenario weightings.
- Schemes with insufficient critical fields are flagged rather than silently scored.
- Geographic maps use only source-supported or documented derived locations.

## 9. Out of Scope
Core delivery excludes confidential personal data, paid production infrastructure, automated operational decisions and unsupported causal inference.

## 10. Reproducibility Definition
A reviewer should be able to clone the team repository, obtain the approved source data, execute the workflow and reproduce curated outputs and validation evidence without undocumented manual changes.
