# Chapter 21 --- AI Governance and Security Case Studies

## Overview

Chapter 21 applies AI governance, cybersecurity, risk management,
privacy, regulatory compliance, and assurance principles to realistic
enterprise scenarios. Each case study connects business purpose and
system architecture to threats, risk decisions, controls, evidence, and
ongoing monitoring.

## Purpose and Learning Objectives

This chapter helps readers: - Assess AI use cases in their business and
technical context. - Map AI components, integrations, data flows, trust
boundaries, and third-party dependencies. - Identify AI-specific and
conventional cybersecurity risks. - Define governance ownership across
business, technology, security, privacy, legal, procurement, risk, and
audit. - Translate applicable obligations into testable controls. -
Evaluate third-party AI services. - Define treatment plans,
residual-risk approvals, KPIs, KRIs, and evidence requirements. -
Communicate risk and remediation priorities to technical teams and
executives.

------------------------------------------------------------------------

## Chapter Structure

  -----------------------------------------------------------------------
  Lesson                  Case study              Primary focus
  ----------------------- ----------------------- -----------------------
  **21.01**               Enterprise ChatGPT      Acceptable use, data
                          Deployment              classification, tenant
                                                  controls, identity,
                                                  retention, and
                                                  awareness

  **21.02**               Microsoft Copilot       Permissions, Microsoft
                          Enterprise Deployment   365 oversharing,
                                                  connectors,
                                                  auditability, and
                                                  change management

  **21.03**               Customer-Service AI     Customer data,
                          Chatbot                 hallucinations,
                                                  disclosure, abuse
                                                  prevention, and human
                                                  escalation

  **21.04**               AI-Powered Contact      Voice and transcript
                          Center                  data, identity
                                                  verification,
                                                  retention, agent
                                                  assist, and resilience

  **21.05**               AI Fraud Detection      False positives and
                          System                  negatives, model drift,
                                                  explainability, data
                                                  quality, and
                                                  investigations

  **21.06**               AI Credit-Scoring       Fairness,
                          System                  explainability, adverse
                                                  decisions, data
                                                  provenance, and model
                                                  validation

  **21.07**               AI Recruitment Platform Candidate privacy,
                                                  discrimination,
                                                  accessibility, human
                                                  oversight, and vendor
                                                  assurance

  **21.08**               AI Healthcare Platform  Sensitive health data,
                                                  clinical safety,
                                                  validation,
                                                  traceability, and
                                                  resilience

  **21.09**               AI-Powered Security     Alert triage, analyst
                          Operations Center       oversight, prompt
                                                  injection in telemetry,
                                                  and response
                                                  authorization

  **21.10**               AI-Powered Network      Availability, automated
                          Operations              remediation, privileged
                                                  access, change control,
                                                  and rollback

  **21.11**               Enterprise RAG          Retrieval permissions,
                          Knowledge System        document
                                                  classification,
                                                  poisoning, source
                                                  traceability, and
                                                  prompt injection

  **21.12**               AI Coding Assistant     Source-code
                                                  confidentiality, secret
                                                  leakage, insecure
                                                  generated code, and
                                                  software supply chain

  **21.13**               AI Financial Advisor    Suitability,
                                                  disclosures, personal
                                                  data, explainability,
                                                  and human escalation

  **21.14**               AI HR Assistant         Employee data, access
                                                  boundaries, policy
                                                  accuracy, retention,
                                                  and human review

  **21.15**               Autonomous AI Agent     Agent identity, least
                          with Tool Access        privilege, tool
                                                  allowlisting, approval
                                                  gates, limits, and
                                                  containment

  **21.16**               AI in Critical          Safety, availability,
                          Infrastructure          OT/IT segmentation,
                                                  change management, and
                                                  resilience

  **21.17**               Enterprise AI Cloud     Shared responsibility,
                          Migration               identity, encryption,
                                                  logging, residency, and
                                                  configuration
                                                  governance

  **21.18**               Third-Party AI SaaS     Vendor due diligence,
                          Deployment              data-use terms,
                                                  subprocessors,
                                                  assurance, exit
                                                  planning, and
                                                  concentration risk

  **21.19**               AI Data Breach, Prompt  Investigation,
                          Injection and Model     containment, evidence
                          Poisoning               preservation,
                                                  notification analysis,
                                                  and recovery

  **21.20**               Deepfake, AI Fraud and  Executive
                          Enterprise AI Crisis    impersonation, payment
                          Case Study              fraud, verification,
                                                  crisis governance,
                                                  forensics, and recovery
  -----------------------------------------------------------------------

------------------------------------------------------------------------

## Standard Case-Study Method

Each lesson follows a consistent assessment sequence. The work may be
iterative; architecture discovery, risk analysis, control design, and
validation often inform one another.

``` text
Business Context and Intended Use
              |
              v
System Architecture, Assets and Data Flows
              |
              v
Stakeholders, Accountability and Trust Boundaries
              |
              v
Threat Scenarios and Risk Assessment
              |
              v
Legal, Regulatory, Contractual and Policy Obligations
              |
              v
Control Design and Risk Treatment
              |
              v
Implementation, Testing and Evidence Collection
              |
              v
Residual-Risk Decision and Formal Approval
              |
              v
Monitoring, Reporting and Continuous Improvement
```

### Required assessment dimensions

1.  **Business context:** objective, users, affected parties, intended
    and prohibited uses, criticality, and success criteria.
2.  **Architecture and data flows:** models, applications, APIs, data
    stores, integrations, trust boundaries, identity, providers, and
    administrative paths.
3.  **Assets and data classification:** personal and confidential data,
    credentials, source code, prompts, outputs, logs, model artifacts,
    and evaluation data.
4.  **Governance and accountability:** business and system owners, AI
    product owner, data owner, security, privacy, legal, procurement,
    operations, and assurance.
5.  **Threat and risk analysis:** threat actors, attack paths, failure
    modes, likelihood, impact, existing controls, residual risk, and
    uncertainty.
6.  **Obligations mapping:** applicable laws, regulations, contracts,
    policies, and standards.
7.  **Control design:** preventive, detective, responsive, and
    corrective controls; human oversight; accountable owners; and test
    methods.
8.  **Risk treatment:** mitigation, avoidance, transfer or sharing where
    appropriate, or acceptance by an authorized risk owner.
9.  **Assurance and evidence:** test results, configuration records,
    approvals, logs, validation, supplier evidence, and audit trails.
10. **Monitoring and improvement:** KPIs, KRIs, drift, incidents,
    exceptions, control failures, and reassessment triggers.

------------------------------------------------------------------------

## Core Governance Model

``` text
Board / Executive Risk Committee
              |
              v
Executive Sponsor and Business Risk Owner
              |
     +--------+---------+
     |                  |
     v                  v
AI Governance       Enterprise Risk / GRC
Committee           Legal / Privacy / Compliance
     |                  |
     +---------+--------+
               |
               v
AI Product / System Owner
               |
     +---------+----------+----------------+
     |                    |                |
     v                    v                v
Engineering / IT     Cybersecurity      Data / Model
Operations           Architecture       Owners
     |                    |                |
     +--------------------+----------------+
                          |
                          v
             Monitoring, Evidence and Audit
```

The exact reporting structure varies by organization. Accountability,
approval authority, escalation routes, and independent challenge must be
explicit.

### Minimum governance records

-   AI system or use-case inventory entry.
-   Business purpose, intended use, and system owner.
-   Data inventory and architecture/data-flow diagram.
-   AI risk assessment and risk-register entries.
-   Applicable-obligations assessment.
-   Security, privacy, safety, and model evaluation results as relevant.
-   Vendor due-diligence records.
-   Control implementation and test evidence.
-   Human-oversight and escalation procedures.
-   Residual-risk decision and approval.
-   Monitoring plan, incident playbook, and reassessment triggers.
-   Retirement, data deletion, and supplier-exit requirements where
    applicable.

------------------------------------------------------------------------

## Framework and Regulatory Mapping

These references may be relevant depending on the use case,
jurisdiction, organizational role, and system characteristics. Their
inclusion does not mean every requirement applies to every case.

  -----------------------------------------------------------------------
  Reference                           Potential use
  ----------------------------------- -----------------------------------
  **NIST AI Risk Management Framework Organize work around Govern, Map,
  (AI RMF)**                          Measure, and Manage

  **ISO/IEC 42001**                   AI management system governance,
                                      risk processes, operational
                                      controls, and performance
                                      evaluation

  **ISO/IEC 23894**                   AI risk-management guidance

  **ISO/IEC 27001**                   Information security management,
                                      risk treatment, and assurance

  **NIST Cybersecurity Framework**    Structure cybersecurity outcomes
                                      and improvement

  **NIST SP 800-53**                  Select and tailor security and
                                      privacy controls where appropriate

  **OWASP guidance for LLM            Examine application risks such as
  applications**                      prompt injection and sensitive
                                      information disclosure

  **EU AI Act**                       Assess obligations based on system,
                                      role, intended purpose, risk
                                      category, and applicable timeline

  **GDPR**                            Assess personal-data processing,
                                      transparency, minimization, rights,
                                      security, and transfers where
                                      relevant

  **DORA / sector-specific            Consider digital operational
  requirements**                      resilience obligations for in-scope
                                      financial entities and services

  **NIS2 and national implementing    Consider cybersecurity and
  measures**                          incident-management duties for
                                      in-scope entities

  **PCI DSS**                         Address payment-account-data
                                      environments when applicable

  **Internal policies and contracts** Translate organizational risk
                                      appetite and commitments into
                                      enforceable requirements
  -----------------------------------------------------------------------

**Applicability rule:** establish the jurisdiction, organization type,
system role, intended purpose, data categories, deployment model, and
contractual context before assigning legal or regulatory obligations.
Seek qualified legal and compliance review where needed.

------------------------------------------------------------------------

## Cross-Cutting Risk Themes

-   **Data exposure:** prompts, retrieved content, outputs, telemetry,
    and logs can reveal sensitive information.
-   **Identity and authorization:** AI services and agents must not
    inherit excessive user or service permissions.
-   **Prompt injection:** untrusted content may influence model behavior
    or tool use when trust boundaries are weak.
-   **Output reliability:** hallucinations and unsupported
    recommendations can create business, safety, or compliance harm.
-   **Model and data integrity:** poisoning, tampering, unauthorized
    changes, and compromised pipelines can undermine results.
-   **Human oversight:** review must be meaningful, timely, and
    supported by information that enables challenge.
-   **Autonomy:** consequential actions require proportionate limits,
    approval gates, and containment.
-   **Third-party dependency:** provider practices, subprocessors, model
    updates, availability, and contracts affect risk.
-   **Fairness and impact:** systems affecting people may require
    assessment of discrimination, accessibility, explainability, and
    adverse impacts.
-   **Monitoring and drift:** changing data, models, prompts, users,
    integrations, or operating conditions can invalidate prior
    assessments.
-   **Incident readiness:** define escalation, evidence preservation,
    containment, recovery, and notification analysis.
-   **Auditability:** material decisions and control operations must
    produce evidence for review.

------------------------------------------------------------------------

## Risk Register and Control Design

For each material risk, capture the following fields:

  -----------------------------------------------------------------------
  Field                               Expected content
  ----------------------------------- -----------------------------------
  Risk ID                             Unique identifier

  Use case / system                   AI application, component, or
                                      process in scope

  Risk statement                      Cause, uncertain event, and
                                      business or stakeholder consequence

  Threat / failure scenario           Credible path from weakness or
                                      trigger to impact

  Affected assets                     Data, model, application, identity,
                                      service, people, or operations

  Inherent risk                       Risk before considering existing
                                      controls

  Existing controls                   Implemented controls and available
                                      evidence

  Control gap                         Missing, ineffective, or unverified
                                      control

  Treatment plan                      Action, owner, due date, and
                                      dependencies

  Residual risk                       Risk remaining after treatment is
                                      implemented and tested

  Risk owner                          Person authorized to own the
                                      business risk

  Approval / exception                Decision, rationale, conditions,
                                      approver, and expiry if applicable

  Monitoring / evidence               Test method, metric, evidence
                                      source, cadence, and reassessment
                                      trigger
  -----------------------------------------------------------------------

Use the organization's approved risk-rating methodology. Do not imply
that a score is objectively precise when likelihood or impact inputs are
uncertain.

------------------------------------------------------------------------

## Recommended Delivery Workflow

1.  Scope the use case, objectives, stakeholders, deployment model, and
    boundaries.
2.  Discover the architecture, integrations, data flows, trust
    boundaries, identities, and external dependencies.
3.  Determine applicable legal, regulatory, contractual, policy, and
    framework requirements.
4.  Assess credible threats and failure modes; record assumptions and
    uncertainty.
5.  Define controls, implementation measures, owners, test methods, and
    evidence requirements.
6.  Prioritize treatment actions and obtain authorized decisions for
    residual risk.
7.  Validate controls, model behavior, access boundaries, human
    oversight, operational readiness, and recovery procedures as
    relevant.
8.  Approve deployment only after required controls and risk decisions
    are documented.
9.  Monitor performance, incidents, changes, exceptions, and control
    effectiveness.
10. Reassess after material changes, incidents, model updates, new
    integrations, regulatory changes, or changes in intended use.

------------------------------------------------------------------------

## Expected Outputs

A completed case study should produce a proportionate evidence package
containing:

-   Executive summary and scope.
-   Architecture and data-flow diagram.
-   Stakeholder and accountability matrix.
-   AI system and data inventory details.
-   Threat scenarios and risk register.
-   Applicable-obligations and control-mapping matrix.
-   Control-gap analysis and prioritized remediation plan.
-   Third-party due-diligence findings where relevant.
-   Security, privacy, model, and operational test plan.
-   Residual-risk decision and approval evidence.
-   KPIs, KRIs, and monitoring plan.
-   Incident-response and recovery considerations.
-   Audit evidence index and reassessment triggers.

## Intended Audience

-   AI Governance and AI Security Governance professionals.
-   Cybersecurity GRC consultants and risk managers.
-   CISOs, security architects, and security engineering teams.
-   AI product owners, system owners, and engineering leaders.
-   Data protection, privacy, legal, and compliance professionals.
-   Enterprise architects and technology risk teams.
-   Procurement and third-party risk management teams.
-   Internal auditors and independent assurance functions.
-   Project and program managers responsible for AI-enabled
    transformation.

------------------------------------------------------------------------

## How to Use This Chapter

Use each lesson as a structured workshop or consulting exercise:

1.  Identify assumptions that require validation.
2.  Draw the architecture and trace sensitive data and privileged
    actions.
3.  Identify accountable owners and affected stakeholders.
4.  Develop threat scenarios before selecting controls.
5.  Map controls to risks and applicable obligations.
6.  Verify whether controls are implemented, tested, and evidenced---not
    merely documented.
7.  Distinguish inherent risk, residual risk, and formally accepted
    risk.
8.  Present prioritized recommendations appropriate to the audience.
9.  Define monitoring and reassessment triggers.

A case study is not a substitute for architecture discovery, threat
modeling, or legal analysis. Adapt its assumptions and controls to the
organization's actual environment, risk appetite, and obligations.

## Definition of Done

A case study is complete when it explains:

-   What the AI system does and why it is used.
-   Which components, data, people, and dependencies are in scope.
-   Which material risks and failure scenarios were identified.
-   Who owns the risks and controls.
-   Which obligations apply and why.
-   How controls reduce risks and how effectiveness is tested.
-   Which risks remain and who is authorized to accept them.
-   What evidence supports the assessment and approval.
-   How the system will be monitored, reassessed, changed, or retired.

------------------------------------------------------------------------

## Conclusion

Chapter 21 turns AI governance and security principles into repeatable,
evidence-based assessments of enterprise AI use cases. The objective is
not simply to list risks. It is to connect business purpose,
architecture, threats, obligations, controls, accountable decisions, and
operational evidence into a coherent governance process.

> **Core principle:** An AI system is not governed effectively because a
> policy exists or a risk assessment has been completed. Effective
> governance requires accountable decisions, proportionate controls,
> tested outcomes, traceable evidence, and continuous reassessment
> throughout the system lifecycle.
