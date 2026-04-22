# Project 2 — AI Risk Assessment & Governance Review Pack

## Scenario
NorthStar Financial Services — a mid-sized EU fintech operating across retail banking, lending, and insurance. Approximately 1,400 employees. 
Regulated under the EU AI Act.

## Problem
Following the AI System Inventory in Project 1, NorthStar's Chief Risk Officer commissioned a full risk assessment across three High Risk AI 
systems — CreditScore Pro, TalentMatch AI, and DocIntel Underwriting.

No formal risk register existed. No controls had been mapped to EU AI Act articles. The board had no visibility into AI risk exposure.

## What I Built
- AI Risk Register — 9 risks scored across 3 High Risk systems
- Risk Heat Map — 5x5 visual matrix
- Governance Control Framework — 12 controls mapped to EU AI Act articles
- Executive Risk Summary — board-level briefing

## Key Findings
- 8 of 9 risks rated Critical (score 15-25/25)
- TalentMatch AI scored 25/25 — discriminating against female candidates in live hiring
- DocIntel operating with zero human oversight — direct Article 14 breach
- CreditScore Pro cannot explain any rejection — Article 13 and GDPR Article 22 breach
- Total fine exposure: up to 30M euros under Article 71

## Risk Register Summary
| Risk ID | System | Category | Score | Priority |
|---------|--------|----------|-------|----------|
| NS-RISK-001 | CreditScore Pro | Bias & Fairness | 20 | Critical |
| NS-RISK-002 | CreditScore Pro | Explainability | 16 | Critical |
| NS-RISK-003 | TalentMatch AI | Bias & Fairness | 25 | Critical |
| NS-RISK-004 | TalentMatch AI | Data Quality | 20 | Critical |
| NS-RISK-005 | DocIntel Underwriting | Compliance | 25 | Critical |
| NS-RISK-006 | DocIntel Underwriting | Security | 15 | Critical |
| NS-RISK-007 | CreditScore Pro | Model Drift | 16 | Critical |
| NS-RISK-008 | TalentMatch AI | Explainability | 16 | Critical |
| NS-RISK-009 | DocIntel Underwriting | Data Quality | 12 | Medium |

## Immediate Actions Recommended
1. SUSPEND TalentMatch AI from senior role shortlisting — bias audit required
2. ENFORCE human review gate for all DocIntel decisions — Article 14 breach
3. INTEGRATE SHAP explainability into CreditScore Pro — Article 13 breach

## EU AI Act Articles Applied
Articles 9, 10, 12, 13, 14, 15, 43, 71 Annex III Categories 4(a) and 5(b)

## Documents
- ai-risk-register.xlsx
- governance-control-framework.docx
- executive-risk-summary.docx
