# NB-RAF v1.1 — Implementation Toolkit & Appendices

**Operational Tools · Practitioner Templates · Governance Checklists**  
*Aligned with the New Brunswick Responsible AI Framework (NB-RAF v1.1)*

## Table of Contents
1. [Purpose of This Toolkit](#1-purpose-of-this-toolkit)
2. [How to Use This Document](#2-how-to-use-this-document)
3. [Appendix A — Model Card Template](#appendix-a--model-card-template](https://github.com/JoieC-GRC-Analyst/NB-AI-Framework/blob/main/templates/model-card.md))
4. [Appendix B — AI System Summary](#appendix-b--ai-system-summary)
5. [Appendix C — AI Procurement Checklist](#appendix-c--ai-procurement-checklist)
6. [Appendix D — OCAP®-Aligned Indigenous Data Governance Workflow](#appendix-d--ocap-aligned-indigenous-data-governance-workflow)
7. [Appendix E — CyberSecure NB AI Security Checklist](#appendix-e--cybersecure-nb-ai-security-checklist)
8. [Appendix F — Bias Audit Checklist](#appendix-f--bias-audit-checklist)
9. [Appendix G — RAG Validation Checklist](#appendix-g--rag-validation-checklist)
10. [Appendix H — Annual AI Portfolio Review Template](#appendix-h--annual-ai-portfolio-review-template)
11. [Links to Modular Templates Folder](#links-to-modular-templates-folder)
12. [Versioning & Contribution Guidance](#versioning--contribution-guidance)

---

## 1. Purpose of This Toolkit
The NB-RAF Implementation Toolkit & Appendices provides the operational layer of the New Brunswick Responsible AI Framework (NB-RAF v1.1).

While the main PDF defines:
*   Principles
*   Governance
*   Risk tiers

This document provides:
*   Practitioner templates
*   Checklists
*   Governance workflows
*   Operational tools
*   Implementation guidance

**Designed for:**
*   Public sector teams
*   First Nations governance bodies
*   SMEs and startups
*   CyberSecure NB partners
*   Consultants and analysts
*   Educators and researchers

*This toolkit is open, editable, and community-maintained.*

## 2. How to Use This Document
This document supports real-world implementation.

### Risk Tier Requirements
| Tier | Classification | Required Appendices |
| :--- | :--- | :--- |
| 0 | Prohibited | None (system cannot be deployed) |
| 1 | High Risk | All appendices |
| 2 | Limited Risk | Model Card, System Summary, Procurement Checklist, CyberSecure NB Checklist |
| 3 | Minimal Risk | Model Card + System Summary |

*Each appendix is also available as a standalone file in the `/templates` folder.*

---

## Appendix A — Model Card Template
*A Model Card is required for all Tier 1 and Tier 2 systems.*

### MODEL CARD — NB-RAF v1.1
1. **System Overview**: Model Name, Version, Release Date, Risk Tier, Intended Use, Out-of-Scope Use.
2. **Data & Training**: Sources, Geographic Relevance, Language Coverage (EN/FR/Acadian), First Nations Data (Yes/No), Data Limitations.
3. **Performance**: Accuracy Metrics, F1 Scores, Known Weaknesses, Edge Case Behavior.
4. **Fairness & Bias**: Bias Testing, Protected Grounds, Disparate Impact, Mitigation Techniques.
5. **Security**: Threat Modelling, Adversarial Testing, Data Residency, Access Controls.
6. **Explainability**: XAI Methods, Explanation Availability.
7. **Human Oversight**: Human-in-the-Loop Requirements, Escalation Path.
8. **Monitoring & Maintenance**: Drift Monitoring, Versioning Policy, Incident Reporting.

## Appendix B — AI System Summary
*Required for all CyberSecure NB–funded AI projects.*

### AI SYSTEM SUMMARY — NB-RAF v1.1
1. **System Description**: Purpose, Decisions Influenced, Risk Tier.
2. **Data Processed**: Inputs, Outputs, Storage Location, Retention Period.
3. **Human Responsibilities**: Reviewer Roles, Non-Automatable Tasks, Override Conditions.
4. **Operational Obligations**: Monthly Reviews, Bias Monitoring, Security Monitoring, Vendor Contact.
5. **Failure Modes**: Known Risks, Warning Signs, Shutdown Procedure.

## Appendix C — AI Procurement Checklist
*Required for all public-sector procurement.*

### PROCUREMENT CHECKLIST — NB-RAF v1.1
*   **Vendor Requirements**: Model Card, System Card, Security Attestations, Bias Testing, Canadian Data Residency, Exit Strategy.
*   **Contract Requirements**: Purpose, Prohibited Uses, Liability, Incident Reporting, Human Oversight, OCAP® Compliance.
*   **Technical Requirements**: Threat Modelling, Logging, Version Control, Explainability, Bilingual Output.

## Appendix D — OCAP®-Aligned Indigenous Data Governance Workflow
*Required for any system involving First Nations data.*

### OCAP® WORKFLOW — NB-RAF v1.1
1. **Scope**: Wolastoqiyik/Mi’kmaq data, Indigenous language, cultural knowledge.
2. **Engagement**: Governance Body, Consultation, Documentation.
3. **Principles**: Ownership, Control, Access, Possession.
4. **FPIC**: Consent, Conditions, Renewal.
5. **Co-Development**: Language Experts, Cultural Safety, Bias Testing.
6. **Ongoing Governance**: Annual Review, Incident Reporting, Model Updates.

## Appendix E — CyberSecure NB AI Security Checklist
*Required for all CyberSecure NB–funded deployments.*

### CYBERSECURE NB CHECKLIST — NB-RAF v1.1
1. **Threat Modelling**: Prompt Injection, Poisoning, Inversion, Adversarial, RAG Manipulation.
2. **Access Controls**: Zero-Trust, API Key Rotation, RBAC.
3. **Monitoring**: Drift, Anomaly, Abuse.
4. **Logging**: Input/Output flow, Human Overrides, Retention.
5. **Data Residency**: Canadian Storage, OCAP® requirements.
6. **Incident Response**: Categories, Escalation, Disclosure.

## Appendix F — Bias Audit Checklist
*Required for Tier 1 and Tier 2 systems.*

### BIAS AUDIT CHECKLIST — NB-RAF v1.1
1. **Protected Grounds**: Race, Origin, Language, First Nations Identity, Age, Disability, Sex/Gender.
2. **Bias Types**: Historical, Representation, Measurement, Aggregation, Evaluation, Deployment.
3. **Mitigation**: Pre/In/Post-Processing.
4. **Documentation**: Bias Register, Remediation Timelines.

## Appendix G — RAG Validation Checklist
*Required for all public-facing chatbots.*

### RAG VALIDATION CHECKLIST — NB-RAF v1.1
1. **Retrieval**: Authoritative Sources, Freshness, Verification.
2. **Generation**: Filtering, Bilingual Validation, No Raw AI Legal Text.
3. **Security**: Injection Defense, Rate Limiting, Abuse Monitoring.

## Appendix H — Annual AI Portfolio Review Template
### ANNUAL PORTFOLIO REVIEW — NB-RAF v1.1
1. **Inventory**: All Systems, Tiers, Owners.
2. **Changes**: Scope Creep, Updates, New Risks.
3. **Retirements**: Decommissioning, Data Deletion.
4. **Governance**: Review Board Minutes, Incident Reports, Bias Register.

---

## Links to Modular Templates Folder
*   [Model Card Template](/templates/model-card.md)
*   [AI System Summary](/templates/system-summary.md)
*   [Procurement Checklist](/templates/procurement.md)
*   [OCAP® Workflow](/templates/ocap-workflow.md)
*   [CyberSecure NB Checklist](/templates/security-checklist.md)
*   [Bias Audit Checklist](/templates/bias-audit.md)
*   [RAG Validation Checklist](/templates/rag-validation.md)

## Versioning & Contribution Guidance
This toolkit is **open-source**, **community-maintained**, and licensed under **CC BY 4.0**.

**Contributors may:**
*   Propose new templates
*   Improve checklists
*   Add sector-specific guidance
*   Localize content (EN/FR/Acadian)
*   Add First Nations governance workflows

**To contribute:**
1. Open an Issue
2. Submit a Pull Request
3. Join discussions
