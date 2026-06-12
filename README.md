# 🔐 AI-Powered IAM Risk Assessment

> A GRC portfolio project demonstrating a structured risk assessment of AI-driven Identity and Access Management systems in a Canadian financial services organisation — covering agentic AI, predictive AI, and customer authentication AI across workforce and customer-facing environments.

---

Project Overview

This risk assessment evaluates three AI systems deployed for Identity and Access Management (IAM) at a fictional Canadian bank — NorthBridge Financial Corp — against four industry frameworks and Canadian financial services regulatory requirements.

It was developed to demonstrate practical competency in:


AI risk identification and quantitative scoring methodology
Second line of defense (2LOD) AI risk oversight concepts
Framework mapping across NIST AI RMF, OWASP LLM Top 10, ISO 27001:2022, and NIST SP 800-53
Canadian financial services regulatory awareness — OSFI B-13 and PIPEDA
AI-specific risk categories including prompt injection, agentic AI risks, privilege escalation, and algorithmic bias
Remediation roadmap development with realistic ownership and timelines



Contents

SheetDescriptionCover PageOrganisation profile, assessment scope, frameworks applied, regulatory contextExecutive SummaryAuto-calculated risk portfolio overview and 9 key findings with severity ratingsAI IAM ArchitectureThree AI systems documented — functions, AI types, data sources, and primary risk areasRisk Register25 risks scored by Likelihood x Impact with severity ratings, controls, and framework referencesControl MappingEvery risk mapped to specific controls across all four frameworksRemediation Roadmap25 prioritised actions across 4 phases with owners, timelines, and severity ratings


Fictional Organisation Profile

FieldDetailOrganisationNorthBridge Financial CorpIndustryFinancial Services / BankingHeadquartersToronto, Ontario, CanadaSize 2,000 employees, 3 regional offices Customers 180,000 retail banking customersAI IAM SystemsWorkforce IAM Agent, Customer Authentication AI, Predictive Access AnalyticsAssessment TypeAI Risk Assessment — Second Line of Defense (2LOD)Assessment DateJune 2026


AI Systems Assessed

1. Workforce IAM Agent

AI Type: AI Agent (Agentic AI)

Autonomously provisions, de-provisions, and reviews access for 2,000 employees and contractors. Makes real-time access grant/deny decisions without human approval for standard roles.

Primary risk: Autonomous decisions without explainability — no audit trail for why access was granted or denied, creating direct compliance exposure under OSFI B-13.


2. Customer Authentication AI

AI Type: Predictive AI and AI Agent

Handles biometric and behavioural authentication for 180,000 retail banking customers. Detects account takeover attempts and triggers step-up authentication.

Primary risk: Processes biometric PII without a PIPEDA DPIA; vulnerable to prompt injection via natural language banking interface; false positives lock legitimate customers out of accounts.


3. Predictive Access Analytics

AI Type: Predictive AI

Analyses historical access patterns to recommend role assignments, flag anomalous access behaviour, and predict Segregation of Duties violations before they occur.

Primary risk: Training data containing historically over-provisioned access normalises privilege creep at scale; model recommendations accepted without human review.


Critical Risks Summary

Risk IDRiskLikelihoodImpactScoreR-01AI Agent makes autonomous access decisions with no explainability or audit trail4520R-02Prompt injection via natural language interface manipulates Customer Auth AI4520R-03AI trained on privilege creep baselines normalises over-provisioned access at scale4520R-04No AI-specific incident response procedure — undefined escalation when AI agent fails5525


Risk Portfolio Summary

SeverityCountPrimary DomainCritical4Explainability, Prompt Injection, Training Data, Incident ResponseHigh8Privilege Escalation, Bias, Vendor Risk, Privacy, SIEM IntegrationMedium9Session Management, Model Drift, Data Quality, BCP, SoDLow4API Security, Documentation, TrainingTotal25


Frameworks Applied

FrameworkApplication in This AssessmentNIST AI RMFPrimary AI governance framework — GOVERN, MAP, MEASURE, MANAGE, and RESPOND functionsOWASP LLM Top 10AI-specific attack vectors — prompt injection (LLM01), excessive agency (LLM08), supply chain (LLM05)ISO 27001:2022Information security controls — A.8 Technical Controls, A.5 Organisational ControlsNIST SP 800-53Security and privacy controls — AC (Access Control), AU (Audit), IR (Incident Response), SI (System Integrity)


Canadian Regulatory Context

RegulationRelevanceOSFI B-13Technology and cyber risk guideline for federally regulated financial institutions — requires AI risk governance, model risk management, and third-party AI oversightPIPEDAPersonal Information Protection and Electronic Documents Act — governs processing of biometric and behavioural PII in Customer Authentication AIFINTRACFinancial Transactions and Reports Analysis Centre — AML/ATF obligations relevant to AI-assisted access controls for financial transactions


Remediation Roadmap Overview

PhaseTimelineFocusPhase 1Month 1Critical — AI IR Playbook, Governance Policy, Audit Logging, Prompt Injection Defence, Fallback SystemPhase 2Month 2-3High — PIPEDA DPIA, Vendor Audit, SIEM Integration, Least Privilege, Training Data CleanupPhase 3Month 4-6Medium — Bias Monitoring, Drift Detection, Session Management, BCP Update, SoD ControlsPhase 4OngoingLow-Medium — API Monitoring, Security Training, Vendor Reviews, Encryption Audit


Skills Demonstrated


AI risk identification and quantitative scoring methodology
Agentic AI risk concepts — autonomous decision-making, privilege escalation, and excessive agency
Prompt injection risk assessment and controls
NIST AI RMF application across all five functions
OWASP LLM Top 10 mapping to real-world IAM attack scenarios
ISO 27001:2022 technical and organisational control application
Canadian financial services regulatory knowledge — OSFI B-13 and PIPEDA
Second line of defense (2LOD) risk oversight concepts
Remediation roadmap development with realistic ownership and timelines
Microsoft Excel — multi-sheet workbook design, conditional formatting, formula-driven risk scoring



Relationship to Other Portfolio Projects

ProjectFrameworksWhat It ShowsISO 27001:2022 Gap AnalysisISO 27001:2022Audit methodology and compliance assessmentAI-Powered IAM Risk Assessment (this project)NIST AI RMF, OWASP LLM Top 10, ISO 27001, NIST 800-53AI risk identification and 2LOD oversightAI GRC Risk Register (coming soon)NIST AI RMF, ISO 27001, EU AI ActEnterprise AI risk managementAI Vendor Risk Assessment (coming soon)NIST AI RMF, ISO 42001, EU AI ActThird-party AI risk management

Together these projects demonstrate end-to-end GRC competency — from compliance assessment through AI risk management to third-party oversight.


Files

AI_IAM_Risk_Assessment_NorthBridge.xlsx   — Full risk assessment workbook (6 sheets)
README.md                                  — This file


References


NIST AI Risk Management Framework (AI RMF 1.0): https://www.nist.gov/artificial-intelligence/ai-rmf
OWASP LLM Top 10: https://owasp.org/www-project-top-10-for-large-language-model-applications/
ISO/IEC 27001:2022: https://www.iso.org/standard/27001
NIST SP 800-53 Rev 5: https://csrc.nist.gov/publications/detail/sp/800-53/rev-5/final
OSFI B-13: https://www.osfi-bsif.gc.ca/en/guidance/guidance-library/technology-cyber-risk-management
PIPEDA: https://www.priv.gc.ca/en/privacy-topics/privacy-laws-in-canada/pipeda/



Author

Dhanya Mary Sam
Cybersecurity Professional | GRC and AI Governance Specialist
Greater Toronto Area, Canada

Certifications: CEH v13 | Security+ (In Progress)
Currently pursuing: CompTIA SecAI+ 
LinkedIn: https://www.linkedin.com/in/dhanya-m-sam
GitHub: https://github.com/Dhanya93


This project was created for portfolio and educational purposes. NorthBridge Financial Corp is a fictional organisation. All risks, findings, scores, and remediation actions are illustrative only.
