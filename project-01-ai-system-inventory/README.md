# Project 1 — AI System Inventory & Classification Engine

## Scenario
NorthStar Financial Services — a mid-sized fintech operating across retail banking, lending, and insurance verticals in the EU. Approximately 
1,400 employees. Regulated in the EU.

## Problem
The Chief Risk Officer initiated an AI governance programme following the EU AI Act entering application. AI systems had been deployed across 
multiple business units without central oversight or classification. No single authoritative inventory existed.

## What I Built
Three professional governance documents:
- Complete AI system inventory of 7 systems (CSV)
- EU AI Act risk classification with full legal rationale for each system
- NIST AI RMF maturity mapping and gap analysis

## Key Findings
- 3 of 7 systems classified as High Risk under EU AI Act
- TalentMatch AI operating since November 2023 with zero conformity assessment — every hiring decision it made could be legally challenged
- CreditScore Pro uses postcode as input — proxy bias risk identified — postcode encodes ethnicity and socioeconomic background
- Vendor contracts missing EU AI Act compliance clauses — legal liability under Article 28
- Two High Risk systems in production with insufficient governance controls — material regulatory exposure for NorthStar

## Risk Tier Summary
| System | Risk Tier | Priority |
|--------|-----------|----------|
| NS-AI-001 CreditScore Pro | High Risk | Critical |
| NS-AI-002 FraudGuard 360 | Limited Risk | Medium |
| NS-AI-003 TalentMatch AI | High Risk | Critical |
| NS-AI-004 SupportBot Aria | Limited Risk | Low |
| NS-AI-005 MarketSense | Minimal Risk | Monitor |
| NS-AI-006 DocIntel Underwriting | High Risk | High |
| NS-AI-007 RegulatoryRadar | Minimal Risk | Monitor |

## NIST RMF Maturity Summary
| System | Overall Maturity |
|--------|-----------------|
| CreditScore Pro | 1.75 — Developing |
| FraudGuard 360 | 3.0 — Defined |
| TalentMatch AI | 1.0 — Initial |
| SupportBot Aria | 3.0 — Defined |
| MarketSense | 3.0 — Defined |
| DocIntel Underwriting | 1.0 — Initial |
| RegulatoryRadar | 3.0 — Defined |

## Frameworks Applied
- EU AI Act — Articles 5, 6, 10, 11, 12, 13, 14, 15, 28, 43, 52, 71 and Annex III Categories 4(a) and 5(b)
- NIST AI RMF 1.0 — Govern, Map, Measure, Manage

## Documents
- ai-system-inventory.csv
- eu-ai-act-classification.pdf
- nist-rmf-mapping.pdf
