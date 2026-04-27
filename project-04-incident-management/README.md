# Project 4 — AI Incident Management Framework

## Scenario
NorthStar Financial Services — EU fintech. 3 High Risk AI systems in production. No AI-specific incident response capability existed before this project.

## Problem
AI incidents are fundamentally different from IT incidents.

When a server fails — systems go down.
When an AI discriminates — people get hurt, careers are derailed, and regulators must be notified within 72 hours under EU AI Act Article 73.
NorthStar had no framework for any of this.

## What I Built

### Document 1 — AI Incident Response Playbook Reference: NS-IRP-AI-001

P1 to P4 severity classification with NorthStar-specific examples for each level. Five-phase response framework — Detect, Contain, Investigate, Recover, Learn.
Timestamped escalation paths for P1 and P2. System-specific guidance for CreditScore Pro, TalentMatch AI, and DocIntel Underwriting.
Article 73 72-hour notification rule. Contact directory for all system owners. Incident log requirements — 5-year retention.

### Document 2 — AI Incident Scenario Library Reference: NS-ISL-AI-001

Three fully reconstructed incidents:

Scenario A — TalentMatch AI Gender Bias
Severity: P1 Critical 26 months of operation. No conformity assessment. No bias audit. 140 candidates potentially affected.
The first signal: a single email from Meera Pillai — a rejected candidate. Not a monitoring alert. Full 12-step timeline from detection to BaFin notification.

Scenario B — CreditScore Pro Model Drift Severity: P2 High
6 months of unfired monitoring alerts. Priya Mehta's branch complaint as the trigger. Postcode-segment rejection rates 12 points 
above national average. Complete response timeline from alert to model redeployment.

Scenario C — SupportBot Aria Disclosure Failure Severity: P3 Medium
9 months. 287,400 conversations. Zero AI disclosure on mobile channel. Article 52 violation. AFM notified voluntarily despite P3 not requiring mandatory notification.

Cross-scenario comparison table showing all three incidents side by side.

### Document 3 — Regulatory Escalation Framework Reference: NS-REF-AI-001

Article 73 — when notification is required and when it is not. Decision tree format. Competent authorities: BaFin (Germany) and AFM (Netherlands). 
What a notification must contain.
Template 1 — Initial notification letter.
Template 2 — Follow-up supplementary report.
What happens if NorthStar misses the 72-hour window.

### Document 4 — Post-Incident Review Template Reference: NS-PIR-AI-001

Excel workbook — 8 tabs:
Tab 1 — Instructions
Tab 2 — Incident Header
Tab 3 — Root Cause Analysis (5-Why method)
Tab 4 — Impact Assessment
Tab 5 — Control Gap Analysis (all 12 NS-CTRL)
Tab 6 — Remediation Tracker
Tab 7 — Lessons Learned
Tab 8 — Regulatory Log and Sign-Off

## Most Important Finding

The first signal of a P1 bias incident was a candidate complaint — not an internal monitoring alert.
You cannot respond to what you cannot detect. You cannot detect what you are not monitoring.

That single finding justifies this entire project. Governance documents without monitoring are decoration.

## Frameworks Applied
EU AI Act Article 73 — incident reporting
EU AI Act Article 52 — AI disclosure
NIST AI RMF — MANAGE function
NS-POL-AI-001 Section 9 — Incident Management
NS-OM-AI-001 — Escalation Framework

## Documents
- NS-IRP-AI-001-Incident-Response-Playbook.docx
- NS-ISL-AI-001-Incident-Scenario-Library.docx
- NS-REF-AI-001-Regulatory-Escalation-Framework.docx
- NS-PIR-AI-001-Post-Incident-Review-Template.xlsx
