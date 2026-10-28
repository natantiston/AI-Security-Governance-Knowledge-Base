# Chapter 20 --- AI Security Governance Tools and Templates

## Overview

Chapter 20 turns the concepts, frameworks, and practices covered in the
AI Security Governance Knowledge Base into a practical toolkit for
governance, risk, compliance, security, privacy, and assurance work.

It provides reusable templates and worksheets to help organizations
assess AI systems, identify and manage risks, assign accountability,
document controls, evaluate third-party providers, support audits, and
track governance improvements throughout the AI lifecycle.

The tools in this chapter are intended to be adapted to the
organization's size, risk profile, operating model, technology
environment, and applicable legal, regulatory, contractual, and
framework requirements. They are starting points for structured
work---not automatic proof of compliance, security, or AI system
trustworthiness.

## Objectives

This chapter is designed to help practitioners:

-   Translate AI governance policies and principles into operational
    processes.
-   Establish consistent documentation for AI systems and use cases.
-   Identify, assess, treat, and monitor AI-related risks.
-   Evaluate AI impacts, security architecture, models, large language
    models, and AI agents.
-   Assess AI vendors and other third-party dependencies.
-   Define governance responsibilities, decision rights, and escalation
    paths.
-   Record incidents, exceptions, risk acceptance, and audit findings.
-   Map internal controls to relevant standards, frameworks, and
    applicable obligations.
-   Build an evidence-based AI control matrix and security governance
    dashboard.
-   Improve the repeatability, traceability, and auditability of AI
    governance activities.

## Chapter Contents

  -----------------------------------------------------------------------------------------------------------------------
  Lesson                                                                  Title                   Primary Purpose
  ----------------------------------------------------------------------- ----------------------- -----------------------
  [20.01](#2001--ai-governance-policy-template)                           AI Governance Policy    Establish the
                                                                          Template                organization's
                                                                                                  overarching AI
                                                                                                  governance principles,
                                                                                                  responsibilities, and
                                                                                                  policy expectations.

  [20.02](#2002--ai-security-policy-template)                             AI Security Policy      Define security
                                                                          Template                requirements for AI
                                                                                                  systems, data, models,
                                                                                                  applications,
                                                                                                  infrastructure, and
                                                                                                  operations.

  [20.03](#2003--ai-acceptable-use-policy)                                AI Acceptable Use       Set expectations and
                                                                          Policy                  boundaries for
                                                                                                  employees and other
                                                                                                  authorized users of AI
                                                                                                  tools.

  [20.04](#2004--ai-risk-management-policy)                               AI Risk Management      Define how AI risks are
                                                                          Policy                  identified, assessed,
                                                                                                  treated, accepted,
                                                                                                  monitored, and
                                                                                                  reported.

  [20.05](#2005--ai-system-inventory-template)                            AI System Inventory     Maintain visibility of
                                                                          Template                AI systems, use cases,
                                                                                                  owners, providers,
                                                                                                  lifecycle stages, and
                                                                                                  dependencies.

  [20.06](#2006--ai-risk-register-template)                               AI Risk Register        Record AI risk
                                                                          Template                scenarios, assessments,
                                                                                                  treatments, owners, and
                                                                                                  residual-risk
                                                                                                  decisions.

  [20.07](#2007--ai-impact-assessment-template)                           AI Impact Assessment    Structure the
                                                                          Template                evaluation of potential
                                                                                                  impacts on individuals,
                                                                                                  groups, organizations,
                                                                                                  and other affected
                                                                                                  stakeholders.

  [20.08](#2008--ai-security-assessment-template)                         AI Security Assessment  Assess AI system
                                                                          Template                security requirements,
                                                                                                  threats, safeguards,
                                                                                                  evidence, and
                                                                                                  outstanding gaps.

  [20.09](#2009--ai-vendor-assessment-template)                           AI Vendor Assessment    Evaluate third-party AI
                                                                          Template                providers, services,
                                                                                                  dependencies,
                                                                                                  contractual safeguards,
                                                                                                  and ongoing risks.

  [20.10](#2010--ai-use-case-assessment-template)                         AI Use-Case Assessment  Evaluate an AI use
                                                                          Template                case's purpose,
                                                                                                  context, intended
                                                                                                  users, data, risks, and
                                                                                                  approval requirements.

  [20.11](#2011--ai-security-questionnaire)                               AI Security             Provide structured
                                                                          Questionnaire           questions for
                                                                                                  collecting information
                                                                                                  about an AI system's
                                                                                                  security and governance
                                                                                                  arrangements.

  [20.12](#2012--ai-governance-raci-and-governance-charter)               AI Governance RACI and  Define governance
                                                                          Governance Charter      bodies, roles,
                                                                                                  accountability,
                                                                                                  decision rights, and
                                                                                                  escalation paths.

  [20.13](#2013--ai-security-architecture-review-template)                AI Security             Review AI architecture,
                                                                          Architecture Review     trust boundaries, data
                                                                          Template                flows, integrations,
                                                                                                  identity, and security
                                                                                                  controls.

  [20.14](#2014--ai-model-risk-assessment)                                AI Model Risk           Assess model-related
                                                                          Assessment              risks, limitations,
                                                                                                  validation,
                                                                                                  performance,
                                                                                                  robustness, and
                                                                                                  lifecycle changes.

  [20.15](#2015--llm-security-assessment)                                 LLM Security Assessment Assess risks specific
                                                                                                  to large language
                                                                                                  models, including
                                                                                                  prompt injection,
                                                                                                  information disclosure,
                                                                                                  and output handling.

  [20.16](#2016--ai-agent-security-assessment)                            AI Agent Security       Evaluate agent
                                                                          Assessment              autonomy, tool access,
                                                                                                  permissions, execution
                                                                                                  boundaries, approvals,
                                                                                                  and monitoring.

  [20.17](#2017--ai-incident-report-and-security-exception-templates)     AI Incident Report and  Document AI-related
                                                                          Security Exception      incidents and manage
                                                                          Templates               approved or requested
                                                                                                  deviations from
                                                                                                  requirements.

  [20.18](#2018--ai-risk-acceptance-and-audit-checklists)                 AI Risk Acceptance and  Support documented risk
                                                                          Audit Checklists        decisions and
                                                                                                  structured governance
                                                                                                  or control reviews.

  [20.19](#2019--isoiec-42001-soa-nist-ai-rmf-and-eu-ai-act-worksheets)   ISO/IEC 42001 SoA, NIST Organize framework
                                                                          AI RMF and EU AI Act    mappings, applicability
                                                                          Worksheets              analysis, control
                                                                                                  traceability, and
                                                                                                  obligation tracking.

  [20.20](#2020--ai-control-matrix-and-security-governance-dashboard)     AI Control Matrix and   Connect controls,
                                                                          Security Governance     risks, owners,
                                                                          Dashboard               evidence, assessment
                                                                                                  results, remediation,
                                                                                                  metrics, and management
                                                                                                  reporting.
  -----------------------------------------------------------------------------------------------------------------------

## How to Use This Chapter

Use the templates according to the AI system's context, risk, lifecycle
stage, and governance requirements. Not every template will apply to
every system or organization.

A practical sequence is:

1.  **Establish governance.** Review the governance policy, security
    policy, acceptable-use policy, risk-management policy, and
    governance charter.
2.  **Identify the AI system or use case.** Record its purpose, owner,
    provider, data, integrations, users, dependencies, and lifecycle
    stage.
3.  **Determine applicability and assess impact.** Evaluate relevant
    risks, potential impacts, and applicable legal, regulatory,
    contractual, and organizational requirements.
4.  **Assess security and technical design.** Review architecture,
    models, LLM-specific risks, agent capabilities, data flows,
    identity, and safeguards as relevant.
5.  **Assess suppliers and dependencies.** Evaluate third-party
    services, provider assurances, contractual terms, and material
    dependencies.
6.  **Define and map controls.** Link risks and applicable requirements
    to controls, owners, implementation methods, and assessment
    criteria.
7.  **Collect and validate evidence.** Record evidence references,
    ownership, freshness, and assessment results.
8.  **Manage findings and decisions.** Track incidents, exceptions, risk
    acceptance, remediation actions, and approvals.
9.  **Report and improve.** Use the control matrix and dashboard to
    monitor coverage, effectiveness, material risks, overdue actions,
    and governance decisions.
10. **Review when circumstances change.** Reassess when intended use,
    data, model, provider, system capabilities, threat conditions, or
    applicable requirements change materially.

This sequence is a suggested workflow, not a mandatory order for every
engagement. Activities may need to run in parallel or be repeated as the
system evolves.

## How the Templates Fit Together

The templates are most effective when their records are connected
through stable identifiers and clear ownership.

``` text
AI GOVERNANCE POLICIES AND CHARTER
                 |
                 v
AI SYSTEM INVENTORY AND USE-CASE ASSESSMENT
                 |
                 v
RISK AND IMPACT ASSESSMENTS
                 |
                 v
SECURITY, MODEL, LLM, AGENT, AND VENDOR ASSESSMENTS
                 |
                 v
CONTROL MATRIX AND FRAMEWORK / OBLIGATION MAPPINGS
                 |
                 v
EVIDENCE, TEST RESULTS, AND AUDIT RECORDS
                 |
                 v
INCIDENTS, EXCEPTIONS, RISK ACCEPTANCE, AND REMEDIATION
                 |
                 v
GOVERNANCE DASHBOARD AND MANAGEMENT REVIEW
                 |
                 v
CONTINUOUS IMPROVEMENT
```

Recommended shared identifiers include:

-   **AI System ID** --- uniquely identifies an AI system.
-   **AI Use-Case ID** --- identifies a specific business use case.
-   **Risk ID** --- identifies a risk scenario.
-   **Control ID** --- identifies a control.
-   **Assessment ID** --- identifies an assessment or review.
-   **Evidence ID** --- identifies a supporting evidence record.
-   **Vendor ID** --- identifies a provider or supplier.
-   **Incident ID** --- identifies an incident.
-   **Exception ID** --- identifies an exception request or approved
    deviation.
-   **Remediation Action ID** --- identifies a corrective action.
-   **Obligation Mapping ID** --- identifies a mapping between a source
    requirement and internal controls.

The organization should define how these identifiers are created,
maintained, linked, and retired. A shared identifier model improves
traceability and reduces duplicate or inconsistent records.

## Important Governance Principles

### 1. Tailor to Context and Risk

Do not apply every template mechanically. Determine what is relevant to
the AI system, its intended purpose, users, data, autonomy, potential
impact, and operating environment.

### 2. Distinguish Framework Mapping from Compliance

Mapping an internal control to a standard, framework, or legal provision
does not by itself demonstrate conformity or legal compliance. Validate
applicability, coverage, implementation, and evidence separately.

### 3. Separate Implementation from Effectiveness

A control marked as implemented has not necessarily been tested or shown
to operate effectively. Record design, implementation, operating
effectiveness, evidence sufficiency, and residual risk as distinct
assessment dimensions.

### 4. Preserve Evidence and Traceability

Assessment conclusions should be supported by appropriate, current, and
traceable evidence. Missing or outdated evidence should be visible and
should not be treated as proof that a control is effective.

### 5. Assign Clear Accountability

Every material system, risk, control, finding, and remediation action
should have an accountable owner. Approval and risk acceptance must
follow the organization's delegated authority model.

### 6. Integrate with Existing Enterprise Governance

Reuse established enterprise processes and controls when they adequately
address the relevant AI risk. Add AI-specific controls where existing
safeguards do not cover AI-related threats or requirements.

### 7. Maintain Lifecycle Oversight

Governance does not end at approval or deployment. Review controls and
assessments when there are material changes to system purpose, models,
data, providers, integrations, autonomy, or operating context.

### 8. Treat Templates as Living Records

Templates should be version-controlled, reviewed periodically, and
updated when the organization's risk profile, operating model,
technology, or applicable requirements change.

## Suggested Implementation Approach

For an organization starting from a limited baseline, a proportionate
rollout may follow these stages:

  -----------------------------------------------------------------------
  Stage                   Focus                   Main Outcome
  ----------------------- ----------------------- -----------------------
  1\. Establish           Governance policies,    Initial accountability
                          roles, scope, and AI    and visibility
                          inventory               

  2\. Assess              Use cases, risks,       Documented risk
                          impacts, security, and  understanding
                          suppliers               

  3\. Control             Control catalogue,      Traceable control
                          ownership, mapping, and framework
                          evidence                

  4\. Operate             Testing, findings,      Repeatable governance
                          exceptions, and         processes
                          remediation             

  5\. Report              KPIs, dashboards, and   Risk-informed decision
                          management reviews      support

  6\. Improve             Reassessment, lessons   Sustainable governance
                          learned, and control    capability
                          updates                 
  -----------------------------------------------------------------------

Prioritize implementation based on risk and applicable obligations
rather than the number of templates completed.

## Limitations and Use

The materials in this chapter are practical governance aids. They do not
replace professional judgment, legal advice, formal risk decisions,
independent assurance, or a system-specific technical assessment.

Before using a template operationally:

-   Confirm that it fits the organization's governance model and scope.
-   Validate applicable requirements with the appropriate legal,
    compliance, privacy, security, and technical specialists.
-   Define the approval authority and record-retention requirements.
-   Protect confidential, personal, and security-sensitive information.
-   Establish clear owners, assessment criteria, and review triggers.
-   Record assumptions, limitations, unresolved questions, and
    decisions.
-   Validate evidence before reporting a control or compliance
    conclusion.

## Chapter Completion Outcome

After applying Chapter 20, practitioners should be able to assemble a
practical AI security governance toolkit that connects policies,
inventories, assessments, risk records, supplier reviews, control
mappings, evidence, incidents, exceptions, remediation, and dashboard
reporting.

The intended outcome is a repeatable and auditable governance
process---not simply a collection of completed documents.

------------------------------------------------------------------------

**Core Principle:** Effective AI security governance depends on
connecting requirements and risks to accountable controls, validated
evidence, defensible decisions, and continuous improvement throughout
the AI lifecycle.
