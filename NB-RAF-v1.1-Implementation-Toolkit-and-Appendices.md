NB‑RAF v1.1 — Implementation Toolkit & Appendices
Operational Tools · Practitioner Templates · Governance Checklists  
Aligned with the New Brunswick Responsible AI Framework (NB‑RAF v1.1)

Table of Contents
Purpose of This Toolkit

How to Use This Document

Appendix A — Model Card Template

Appendix B — AI System Summary

Appendix C — AI Procurement Checklist

Appendix D — OCAP®‑Aligned Indigenous Data Governance Workflow

Appendix E — CyberSecure NB AI Security Checklist

Appendix F — Bias Audit Checklist

Appendix G — RAG Validation Checklist

Appendix H — Annual AI Portfolio Review Template

Links to Modular Templates Folder

Versioning & Contribution Guidance

1. Purpose of This Toolkit
The NB‑RAF Implementation Toolkit & Appendices provides the operational layer of the New Brunswick Responsible AI Framework (NB‑RAF v1.1).
While the main PDF defines principles, governance, and risk tiers, this document provides:

Practitioner templates

Checklists

Governance workflows

Operational tools

Implementation guidance

This toolkit is designed for:

Public sector teams

First Nations governance bodies

SMEs and startups

CyberSecure NB partners

Consultants and analysts

Educators and researchers

It is open, editable, and community‑maintained.

2. How to Use This Document
This document is structured to support real‑world implementation.

Tier 1 (High‑Risk) systems must complete all appendices.

Tier 2 (Limited‑Risk) systems must complete Model Card, System Summary, Procurement Checklist, and CyberSecure NB Checklist.

Tier 3 (Minimal‑Risk) systems should complete the Model Card and System Summary.

Tier 0 (Prohibited) systems cannot be deployed.

Each appendix is also available as a standalone file in the /templates folder for modular editing.

Appendix A — Model Card Template (NB‑RAF Standard)
A Model Card is required for all Tier 1 and Tier 2 systems.

MODEL CARD — NB‑RAF v1.1
1. System Overview
Model Name:

Version:

Release Date:

Risk Tier (NB‑RAF):

Intended Use:

Out‑of‑Scope Use:

2. Data & Training
Training Data Sources:

Geographic Relevance:

Language Coverage (EN/FR/Acadian):

First Nations Data (Yes/No):

If yes → attach OCAP® documentation

Data Limitations:

3. Performance
Accuracy Metrics:

F1 Scores (EN/FR/Acadian):

Known Weaknesses:

Edge Case Behavior:

4. Fairness & Bias
Bias Testing Conducted:

Protected Grounds Evaluated:

Disparate Impact Findings:

Mitigation Techniques Applied:

5. Security
Threat Modelling Completed:

Adversarial Testing:

Data Residency:

Access Controls:

6. Explainability
XAI Methods Used:

Explanation Availability:

7. Human Oversight
Human‑in‑the‑Loop Requirements:

Escalation Path:

8. Monitoring & Maintenance
Drift Monitoring:

Versioning Policy:

Incident Reporting Process:

Appendix B — AI System Summary (SME Handover Package)
Required for all CyberSecure NB–funded AI projects.

AI SYSTEM SUMMARY — NB‑RAF v1.1
1. System Description
What the AI does:

What decisions it influences:

Risk Tier:

2. Data Processed
Inputs:

Outputs:

Storage Location (must be Canadian for public/health/First Nations data):

Retention Period:

3. Human Responsibilities
Who reviews outputs:

What cannot be automated:

When human override is mandatory:

4. Operational Obligations
Monthly review tasks:

Bias monitoring:

Security monitoring:

Vendor contact information:

5. Failure Modes
Known risks:

What to watch for:

Emergency shutdown procedure:

Appendix C — AI Procurement Checklist
Required for all public‑sector procurement.

PROCUREMENT CHECKLIST — NB‑RAF v1.1
Vendor Requirements
Provides Model Card

Provides System Card

Provides security attestations

Provides bias testing results

Provides Canadian data residency confirmation

Provides exit strategy and data deletion plan

Contract Requirements
System purpose defined

Prohibited uses defined

Liability and indemnification clauses

Incident reporting timelines

Human oversight requirements

OCAP® compliance if First Nations data involved

Technical Requirements
Threat modelling completed

Logging enabled

Version control documented

Explainability available

Bilingual output validated

Appendix D — OCAP®‑Aligned Indigenous Data Governance Workflow
Required for any AI system involving First Nations data.

OCAP® WORKFLOW — NB‑RAF v1.1
1. Determine if First Nations data is involved
Data relates to Wolastoqiyik or Mi’kmaq individuals or communities

Data includes Indigenous language content

Data includes cultural expressions or knowledge

2. Engage the appropriate Nation(s)
Identify the governance body

Initiate Nation‑to‑Nation consultation before procurement

Provide full documentation package

3. Apply OCAP® Principles
Ownership — Community owns the data collectively

Control — Community controls how data is used

Access — Community has access to all data and outputs

Possession — Data stored in infrastructure approved by the Nation

4. Obtain Free, Prior, and Informed Consent (FPIC)
Consent granted

Conditions documented

Renewal schedule defined

5. Co‑Development
Indigenous language experts involved

Cultural safety review completed

Bias testing includes First Nations evaluators

6. Ongoing Governance
Annual review with the Nation

Incident reporting shared

Model updates approved

Appendix E — CyberSecure NB AI Security Checklist
Required for all CyberSecure NB–funded AI deployments.

CYBERSECURE NB CHECKLIST — NB‑RAF v1.1
1. Threat Modelling
Prompt injection

Data poisoning

Model inversion

Adversarial inputs

RAG retrieval manipulation

2. Access Controls
Zero‑trust applied

API keys rotated

Role‑based access enforced

3. Monitoring
Drift detection

Anomalous output detection

Abuse monitoring

4. Logging
Input → Model → Output chain logged

Human overrides logged

Logs retained (5 years Tier 1, 2 years Tier 2)

5. Data Residency
All data stored in Canada

First Nations data stored per OCAP® requirements

6. Incident Response
AI incident categories defined

Escalation path documented

Public disclosure thresholds defined

Appendix F — Bias Audit Checklist
Required for Tier 1 and Tier 2 systems.

BIAS AUDIT CHECKLIST — NB‑RAF v1.1
1. Protected Grounds Tested
Race

National origin

Language (EN/FR/Acadian)

First Nations identity

Age

Disability

Sex & gender identity

2. Bias Types (Suresh & Guttag)
Historical

Representation

Measurement

Aggregation

Evaluation

Deployment

3. Mitigation Applied
Pre‑processing

In‑processing

Post‑processing

4. Documentation
Bias Incident Register updated

Remediation timelines defined

Appendix G — RAG Validation Checklist
Required for all public‑facing chatbots.

RAG VALIDATION CHECKLIST — NB‑RAF v1.1
1. Retrieval
Sources are authoritative

Document freshness enforced

No unverified external sources

2. Generation
Output filtering applied

Bilingual accuracy validated

No raw AI output used for legal/administrative text

3. Security
Prompt injection defenses

Rate limiting

Abuse monitoring

Appendix H — Annual AI Portfolio Review Template
Required for all public‑sector bodies.

ANNUAL PORTFOLIO REVIEW — NB‑RAF v1.1
1. Inventory
List of all AI systems

Risk tiers

Owners

2. Changes
Scope creep

Model updates

New risks

3. Retirements
Systems to decommission

Data deletion plans

4. Governance
Review Board minutes

Incident reports

Bias register

Links to Modular Templates Folder
Each appendix also exists as a standalone file for modular editing:

Model Card

AI System Summary

Procurement Checklist

OCAP Governance

CyberSecure NB Checklist

Bias Audit Checklist

RAG Validation Checklist

Versioning & Contribution Guidance
This toolkit is:

Open‑source

Community‑maintained

Licensed under CC BY 4.0

Designed for public consultation

Contributors may:

Propose new templates

Improve checklists

Add sector‑specific guidance

Localize content (EN/FR/Acadian)

Add First Nations governance workflows

To contribute:

Open an Issue

Submit a Pull Request

Join discussions
