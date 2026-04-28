# Project 5 — High Risk AI Documentation # & Conformity Pack

## Scenario
NorthStar Financial Services — EU fintech. System: NS-AI-001 CreditScore Pro.
Classification: High Risk — Annex III 
Category 5(b) — creditworthiness assessment.
2,400 loan applications per month. Germany and Netherlands.
In production since March 2022. Never undergone a conformity assessment.

## Problem
A conformity assessment is not a document. It is a formal process that proves — with documented evidence — that a High Risk AI 
system meets every EU AI Act requirement before it continues operating.

Three critical gaps were identified in the Q1 2026 governance review:

1. Postcode feature functioning as proxy for ethnicity — bias audit never conducted
2. SHAP explainability not deployed to Article 13 customer-facing standard
3. Loan officer override rate falling from 1.2% to 0.7% over 5 quarters — automation bias confirmed and documented for the first time

## What I Built
### Document 1 — Technical Documentation File Reference: NS-TDF-AI-001 Regulatory basis: Article 11 + Annex IV
Complete technical file for CreditScore Pro. System identity and architecture — XGBoost gradient boosting on 847,432 historical 
applications January 2016 to December 2021. All 7 input features documented with governance notes — postcode flagged as 
critical proxy bias risk. Production performance metrics — AUROC 0.821, Precision 0.748, Recall 0.703. Demographic parity gap — NOT MEASURED. 
Flagged as critical gap. SHAP explainability — technically implemented, not deployed to Article 13 standard. Human oversight — override rate data across 
5 quarters showing declining trend. 8 compliance gaps documented with deadlines.

### Document 2 — Risk Management System Reference: NS-RMS-AI-001 Regulatory basis: Article 9
5 risks identified and formally scored:
NS-RISK-001 Proxy Bias — Score 20/25 Critical
NS-RISK-002 Explainability Gap — Score 16/25
NS-RISK-007 Model Drift — Score 12/25
NS-RISK-010 Automation Bias — Score 12/25
NS-RISK-011 Thin File Applicants — Score 9/25

Residual risk assessed post-controls. Honest: controls for NS-RISK-001 are rated LOW effectiveness — they do not address the root cause. Bias audit required.
Monitoring cadence — daily, weekly, monthly, quarterly, annual.

### Document 3 — Bias and Fairness Assessment Reference: NS-BFA-AI-001Regulatory basis: Article 10
This document does not clear CreditScore Pro of bias concerns. It documents what is known, what has been done, and what gaps remain.

Proxy bias sources identified:
- Postcode — encodes ethnicity and socioeconomic status in DE and NL markets
- Historical lending data — 2016-2021 decisions reflect human prejudice
- Age — thin-file risk for young applicants

Four fairness metrics defined: 
Demographic Parity — NOT MEASURED
Equal Opportunity — NOT MEASURED
Calibration — PARTIALLY MEASURED
Individual Fairness — NOT FORMALLY MEASURED

Independent bias audit commissioned.
This document is an honest governance record — not a bias clearance.

### Document 4 — Declaration of Conformity Reference: NS-DOC-AI-001 Regulatory basis: Article 47
Status: DRAFT — pending bias audit

Cannot be finalised until:
- Bias audit complete and findings addressed
- SHAP customer explanation deployed
- Loan officer training delivered
- Demographic parity measurement implemented
- AI Risk Committee unanimous approval
- EU database registration completed

All 9 articles assessed with status — compliant, in progress, gap, or critical gap. Target signature date: 30 May 2026.

### Document 5 — Conformity Assessment Checklist Reference: NS-CAC-AI-001 Regulatory basis: Articles 9-17

Excel workbook — 2 sheets. 19 requirements tracked across Articles 9-17. RAG status per requirement.
Current evidence documented. Owner and deadline for every gap.

Summary Dashboard:
5 Compliant — logging, data provenance, data processing, override mechanism, aggregate accuracy
4 In Progress — risk management system, technical documentation, Art.13 info, 
Art.14 oversight 4 Gap — customer explanation, oversight training, automation bias, demographic parity
2 Critical Gap — bias audit (Art.10), instructions for use (Art.13)
3 Pending — CE marking, EU registration, Declaration of Conformity

Key blocking issue: bias audit must complete before Declaration of Conformity can be issued.

## Most Important Finding
The Declaration of Conformity is a DRAFT because the bias audit is not done.

That is not a failure. That is honesty.

A real conformity assessment does not produce a clean pass for a system that has never had a bias audit. It produces an honest gap analysis with a clear path to compliance.

That is what this project demonstrates.

## Frameworks Applied
EU AI Act Articles 9, 10, 11, 12, 13, 14, 15, 47, 71 and Annex III, Annex IV, Annex V NIST AI RMF — MEASURE and MANAGE functions

## Documents
- NorthStar-Technical-Documentation-CreditScore-Pro-v1.0.docx
- NorthStar-Risk-Management-System-v1.0.docx
- NorthStar-Bias-Fairness-Assessment-v1.0.docx
- NorthStar-Declaration-of-Conformity-DRAFT-v1.0.docx
- NorthStar-Conformity-Assessment-Checklist-v1.0.xlsx
