# 17 — AI Incident Management and Resilience

## Chapter Overview

**AI Incident Management and Resilience** establishes the governance, security, operational, regulatory, and organizational framework required to identify, classify, contain, investigate, recover from, and learn from AI-related incidents.

AI systems introduce incident scenarios that may not fit traditional cybersecurity incident models. An AI incident may involve model failure, hallucination, data poisoning, prompt injection, model compromise, privacy exposure, deepfake generation, fraud, safety impact, or failure of the supporting infrastructure and supply chain.

Effective AI incident management therefore requires an integrated capability covering:

- AI security incidents
- AI safety incidents
- AI privacy incidents
- AI model failures
- AI hallucinations
- AI data poisoning
- AI prompt injection
- AI model compromise
- AI abuse and misuse
- Deepfake incidents
- AI fraud
- Incident severity and classification
- Incident escalation
- Containment and eradication
- Rollback, shutdown and kill switches
- Disaster recovery
- Business continuity
- Crisis management
- Regulatory notification
- Resilience and continuous assurance

The chapter distinguishes technical incident response from broader AI governance and resilience. It also establishes clear boundaries between internal governance controls and legal or regulatory requirements.

---

## Chapter Objectives

This chapter provides a structured AI Incident Management and Resilience framework that enables organizations to:

1. Establish an AI incident management governance model.
2. Define and classify AI incident types.
3. Detect and respond to AI security incidents.
4. Manage AI safety and privacy incidents.
5. Identify and investigate model failures.
6. Detect and manage hallucination incidents.
7. Detect and contain data poisoning.
8. Respond to prompt injection attacks.
9. Investigate AI model compromise.
10. Manage AI abuse, misuse, deepfake, and fraud incidents.
11. Establish consistent severity and classification mechanisms.
12. Define escalation authorities and decision paths.
13. Implement containment and eradication controls.
14. Establish rollback, shutdown, and kill-switch capabilities.
15. Develop AI disaster recovery capabilities.
16. Establish AI business continuity and crisis-management capabilities.
17. Manage regulatory notification and regulatory resilience.
18. Integrate suppliers and fourth parties into incident and resilience processes.
19. Establish evidence, auditability, and assurance mechanisms.
20. Develop continuous monitoring, testing, automation, and maturity assessment.

---

## Chapter Structure

### 17.01 — AI Incident Management Foundations

Establishes the fundamental concepts, lifecycle, governance, roles, evidence requirements, incident classification, response processes, recovery principles, and resilience foundations for AI incident management.

**Key concepts:**

- AI incident
- AI event
- Incident lifecycle
- Incident detection
- Triage
- Classification
- Severity
- Containment
- Eradication
- Recovery
- Evidence
- Incident governance
- Incident resilience

---

### 17.02 — AI Incident Taxonomy

Defines a structured taxonomy for classifying AI incidents and separating incident categories from causes, attack vectors, triggers, impacts, and root causes.

**Key concepts:**

- Incident category
- Attack vector
- Trigger
- Root cause
- Contributing factor
- Impact
- Scope
- Blast radius
- Security incident
- Safety incident
- Privacy incident
- Operational incident
- Supplier incident
- Regulatory relevance

---

### 17.03 — AI Security Incident Response

Establishes the response framework for AI security incidents involving models, data, infrastructure, agents, tools, credentials, APIs, retrieval systems, and supply-chain components.

**Key concepts:**

- Security incident response
- Model compromise
- Prompt injection
- Data poisoning
- Credential compromise
- Privilege escalation
- Data exfiltration
- Tool abuse
- Agent compromise
- Model extraction
- Supply-chain compromise
- Evidence preservation
- Incident containment

---

### 17.04 — AI Safety Incidents

Addresses incidents in which AI behavior creates or contributes to safety-related consequences.

**Key concepts:**

- AI safety incident
- Unsafe model behavior
- Safety boundary
- Human oversight
- Safety escalation
- Safety containment
- Safety recovery
- Safety assurance
- High-impact AI behavior

---

### 17.05 — AI Privacy Incidents

Addresses incidents involving personal data, privacy exposure, unauthorized processing, model memorization, inference risks, and privacy-related consequences.

**Key concepts:**

- Privacy incident
- Personal data
- Data exposure
- Unauthorized processing
- Privacy breach
- Model memorization
- Inference risk
- Privacy containment
- Privacy recovery
- Privacy assurance

---

### 17.06 — AI Model Failure

Examines failures involving model performance, reliability, behavior, availability, configuration, dependencies, drift, distribution shift, regression, and deployment.

**Key concepts:**

- Model failure
- Model error
- Model drift
- Distribution shift
- Behavioral failure
- Reliability
- Availability
- Regression
- Model rollback
- Fallback
- Recovery validation

---

### 17.07 — Hallucination Incidents

Establishes a governance framework for hallucination-related incidents, including factual errors, unsupported claims, fabricated information, unreliable citations, grounding failures, and downstream decision impact.

**Key concepts:**

- Hallucination
- Factual error
- Unsupported claim
- Fabrication
- Grounding
- Retrieval
- Evidence
- Source reliability
- Verification
- Decision impact

---

### 17.08 — AI Data Poisoning Incidents

Addresses incidents involving malicious or unauthorized manipulation of datasets, training data, validation data, retrieval data, or other AI-relevant information.

**Key concepts:**

- Data poisoning
- Dataset integrity
- Data contamination
- Training-data integrity
- Provenance
- Detection
- Containment
- Eradication
- Recovery
- Data integrity assurance

---

### 17.09 — AI Prompt Injection Incidents

Addresses direct, indirect, persistent, multimodal, retrieval-based, tool-output, and agentic prompt injection scenarios.

**Key concepts:**

- Prompt injection
- Direct injection
- Indirect injection
- Persistent injection
- Context manipulation
- Tool abuse
- Agent compromise
- Memory contamination
- Retrieval compromise
- Data exfiltration
- Authorization boundary

---

### 17.10 — AI Model Compromise

Addresses unauthorized modification, replacement, access, control, corruption, or compromise of AI models and their supporting artifacts.

**Key concepts:**

- Model compromise
- Model artifact
- Model weights
- Model integrity
- Behavioral integrity
- Cryptographic integrity
- Provenance
- Authenticity
- Deployment integrity
- Runtime integrity
- CI/CD integrity
- Supply-chain integrity

---

### 17.11 — AI Abuse and Misuse

Addresses malicious, unauthorized, inappropriate, or unintended use of AI capabilities.

**Key concepts:**

- AI abuse
- AI misuse
- Unauthorized use
- Policy violation
- Capability abuse
- Insider misuse
- External abuse
- Agent misuse
- Automated abuse
- Abuse detection
- Abuse containment

---

### 17.12 — Deepfake Incidents

Addresses incidents involving synthetic or manipulated images, audio, video, identity cloning, impersonation, social engineering, fraud, and reputational impact.

**Key concepts:**

- Deepfake
- Synthetic media
- Impersonation
- Identity cloning
- Face manipulation
- Voice cloning
- Lip synchronization
- Media authenticity
- Media integrity
- Provenance
- Social engineering

---

### 17.13 — AI Fraud Incidents

Addresses AI-enabled and AI-assisted fraud involving impersonation, deepfakes, account takeover, synthetic identities, transaction manipulation, automated fraud, and agentic fraud.

**Key concepts:**

- Fraud event
- Fraud incident
- AI-enabled fraud
- Identity fraud
- Account takeover
- Impersonation
- Transaction manipulation
- Synthetic identity
- Deepfake fraud
- Agentic fraud
- Fraud detection

---

### 17.14 — AI Incident Severity and Classification

Establishes structured mechanisms for evaluating incident severity and classification using multiple impact and risk dimensions.

**Key concepts:**

- Incident classification
- Severity
- Criticality
- Materiality
- Confidentiality
- Integrity
- Availability
- Privacy impact
- Safety impact
- Financial impact
- Operational impact
- Regulatory relevance
- Scope
- Blast radius
- Recoverability

---

### 17.15 — AI Incident Escalation

Defines escalation mechanisms, authority, thresholds, communication paths, and cross-functional coordination.

**Key concepts:**

- Escalation
- Escalation trigger
- Escalation threshold
- Escalation authority
- Functional escalation
- Technical escalation
- Executive escalation
- Regulatory escalation
- Crisis escalation
- Supplier escalation
- Fourth-party escalation

---

### 17.16 — AI Incident Containment and Eradication

Establishes mechanisms for limiting incident propagation, isolating affected components, removing persistence, and validating remediation.

**Key concepts:**

- Containment
- Eradication
- Isolation
- Quarantine
- Model suspension
- Dataset isolation
- Credential revocation
- Privilege restriction
- Root-cause removal
- Residual risk
- Trusted state

---

### 17.17 — AI Incident Rollback, Shutdown and Kill Switches

Addresses emergency mechanisms for reverting, disabling, or terminating AI functionality.

**Key concepts:**

- Rollback
- Shutdown
- Kill switch
- Kill capability
- Emergency shutdown
- Partial shutdown
- Full shutdown
- Functional shutdown
- Model shutdown
- Agent shutdown
- Tool shutdown
- Safe state
- Fail-safe
- Fail-secure
- Graceful degradation
- Fallback

---

### 17.18 — AI Disaster Recovery

Establishes recovery capabilities for restoring AI systems, models, datasets, configurations, infrastructure, identities, and supporting services following major disruption.

**Key concepts:**

- Disaster recovery
- Recovery strategy
- Recovery plan
- Business impact analysis
- RTO
- RPO
- Backup
- Restore
- Failover
- Failback
- Alternate model
- Alternate provider
- Recovery validation
- Trusted recovery state

---

### 17.19 — AI Business Continuity and Crisis Management

Addresses continuity of critical AI-enabled business services and enterprise crisis management during major disruption.

**Key concepts:**

- Business continuity
- Crisis management
- Critical business service
- Business impact analysis
- Maximum tolerable downtime
- RTO
- RPO
- Graceful degradation
- Manual fallback
- Alternative service
- Alternative model
- Alternative provider
- Crisis communication
- Common operating picture
- Crisis authority

---

### 17.20 — AI Regulatory Notification and Resilience Program

Establishes the governance framework for determining regulatory notification applicability, managing regulatory submissions, preserving evidence, maintaining regulatory resilience, and providing continuous assurance.

**Key concepts:**

- Regulatory notification
- Notification trigger
- Notification threshold
- Regulatory applicability
- Competent authority
- Notification ownership
- Notification decision authority
- Legal mapping
- Jurisdiction mapping
- Regulatory inquiry
- Notification deadline
- Regulatory resilience
- Evidence resilience
- Communication resilience
- Regulatory assurance

---

# Cross-Chapter Governance Model

Chapter 17 should be understood as an integrated lifecycle rather than twenty independent subjects.

```text
AI EVENT
   |
   v
DETECTION
   |
   v
INCIDENT IDENTIFICATION
   |
   v
CLASSIFICATION
   |
   v
SEVERITY
   |
   v
ESCALATION
   |
   v
CONTAINMENT
   |
   v
ERADICATION
   |
   v
ROLLBACK / SHUTDOWN
   |
   v
RECOVERY
   |
   v
BUSINESS CONTINUITY
   |
   v
CRISIS MANAGEMENT
   |
   v
REGULATORY ASSESSMENT
   |
   v
REGULATORY NOTIFICATION
   |
   v
ASSURANCE
   |
   v
LESSONS LEARNED
   |
   v
CONTROL IMPROVEMENT
```

This lifecycle should not be interpreted as strictly linear. AI incidents may require repeated movement between classification, escalation, containment, recovery, regulatory assessment, and crisis management.

---

# Core Governance Distinctions

Chapter 17 consistently distinguishes the following concepts.

### Event vs Incident

An event is an observable occurrence. An incident is an event that meets defined organizational criteria for incident management.

### Security Incident vs AI Incident

Not every AI incident is a cybersecurity incident. AI safety, privacy, operational, model-performance, fraud, and regulatory incidents may exist without a confirmed security compromise.

### Failure vs Compromise

A model can fail without being compromised, and a compromised model may continue operating without immediately producing an obvious technical failure.

### Detection vs Response

Detection identifies a condition. Response manages the condition.

### Containment vs Eradication

Containment limits propagation or impact. Eradication removes the underlying malicious or unauthorized condition.

### Eradication vs Recovery

Removing the cause of an incident does not automatically restore a trustworthy operational state.

### Rollback vs Recovery

Rollback returns a system or model to another version or state. Recovery requires restoration and validation of operational capability and trustworthiness.

### Shutdown vs Eradication

Stopping an AI system does not necessarily remove the underlying cause of compromise or failure.

### Kill Capability vs Resilience

A kill switch provides an emergency control. It does not by itself establish resilient operations.

### Backup vs Recoverability

A backup exists as stored data. Recoverability requires demonstrated ability to restore and validate that data.

### Recovery vs Trusted Recovery

Technical restoration does not automatically establish that the restored environment is secure, correct, or trustworthy.

### BCP vs DR

Business continuity focuses on maintaining critical business services. Disaster recovery focuses on restoring technology and supporting capabilities.

### Regulatory Assessment vs Regulatory Notification

Determining whether a regulatory requirement may apply is distinct from actually submitting a notification.

### Regulatory Notification vs Public Disclosure

A regulatory notification is communication to an appropriate authority. It is not automatically equivalent to public disclosure.

### Internal Classification vs Legal Classification

Organizational taxonomies and severity models should not be represented as statutory or regulatory classifications unless an applicable authority establishes them.

### Internal Control vs Legal Requirement

An organizational control designed to support compliance is not automatically a legal requirement.

### Monitoring vs Assurance

Monitoring observes conditions. Assurance provides evidence-based confidence regarding control design, implementation, operation, or effectiveness.

### Documentation vs Capability

A documented process does not demonstrate that the organization can execute the process effectively during a real incident.

### Exercise vs Compliance Proof

An exercise provides evidence about preparedness but does not automatically establish legal or regulatory compliance.

### Automation vs Accountability

Automation may support detection, assessment, routing, evidence collection, and escalation, but accountability remains with appropriately authorized organizational personnel.

---

# Regulatory and Governance Classification

Throughout Chapter 17, controls should be classified according to their source.

| Classification | Meaning |
|---|---|
| **Legal Requirement** | Requirement directly established by applicable legislation or regulation |
| **Regulatory Authority / Power** | Authority, supervisory power, or formal responsibility assigned to a competent authority |
| **Contractual Requirement** | Requirement established through a contract, DPA, SLA, supplier agreement, or similar instrument |
| **Governance Control** | Internal control established by the organization to manage risk or support compliance |
| **Implementation Practice** | Practical mechanism used to implement an obligation or governance requirement |
| **Recommended Practice** | A useful control or practice that is not itself necessarily legally mandated |

This distinction is particularly important for:

- incident severity;
- escalation thresholds;
- kill-switch controls;
- RTO/RPO values;
- regulatory notification workflows;
- supplier controls;
- continuous monitoring;
- maturity models;
- dashboards;
- KRIs and KPIs;
- automated decision support.

---

# Internal Taxonomy

The chapter uses the following primary internal taxonomy:

**`AI-IMR-*` — AI Incident Management and Resilience**

Specialized identifiers may be used for individual domains, for example:

```text
AI-IMR-PRI-*     AI Privacy Incidents
AI-IMR-MCF-*     AI Model Failure
AI-IMR-HAL-*     Hallucination Incidents
AI-IMR-DPI-*     AI Data Poisoning Incidents
AI-IMR-PII-*     AI Prompt Injection Incidents
AI-IMR-MCP-*     AI Model Compromise
AI-IMR-AAM-*     AI Abuse and Misuse
AI-IMR-DFI-*     Deepfake Incidents
AI-IMR-AFR-*     AI Fraud Incidents
AI-IMR-SCL-*     AI Severity and Classification
AI-IMR-ESC-*     AI Incident Escalation
AI-IMR-CON-*     AI Containment and Eradication
AI-IMR-RSK-*     Rollback, Shutdown and Kill Switches
AI-IMR-DR-*      AI Disaster Recovery
AI-IMR-BCM-*     AI Business Continuity and Crisis Management
AI-IMR-RNR-*     Regulatory Notification and Resilience
```

These identifiers are **knowledge-base taxonomy identifiers only**. They do not represent:

- statutory provisions;
- regulatory article numbers;
- official control identifiers;
- certification requirements;
- legal obligations.

---

# Chapter-Wide Control Architecture

The chapter can be represented through seven major control layers:

```text
┌──────────────────────────────────────────────┐
│ 1. GOVERNANCE                                │
│ Policy • Authority • Accountability • Risk   │
├──────────────────────────────────────────────┤
│ 2. IDENTIFICATION                            │
│ Detection • Triage • Classification          │
├──────────────────────────────────────────────┤
│ 3. RESPONSE                                  │
│ Escalation • Containment • Eradication       │
├──────────────────────────────────────────────┤
│ 4. RECOVERY                                  │
│ Rollback • Shutdown • DR • Restoration       │
├──────────────────────────────────────────────┤
│ 5. CONTINUITY                                │
│ BCP • Crisis Management • Fallback           │
├──────────────────────────────────────────────┤
│ 6. REGULATORY RESILIENCE                     │
│ Assessment • Notification • Evidence         │
├──────────────────────────────────────────────┤
│ 7. ASSURANCE                                 │
│ Testing • Monitoring • Metrics • Maturity    │
└──────────────────────────────────────────────┘
```

---

# Chapter Control Objectives

The organization should be able to demonstrate that it can:

- identify AI incidents;
- distinguish incidents from ordinary events;
- classify incidents consistently;
- determine severity using defined criteria;
- escalate incidents appropriately;
- contain affected AI components;
- eradicate underlying causes;
- preserve evidence;
- perform rollback where appropriate;
- shut down unsafe or compromised capabilities;
- activate kill mechanisms when authorized;
- restore AI services;
- validate restored systems;
- maintain critical business services;
- manage enterprise crises;
- assess regulatory obligations;
- submit required notifications where applicable;
- maintain regulatory evidence;
- manage supplier and fourth-party dependencies;
- operate under degraded conditions;
- recover from major disruption;
- test resilience;
- perform independent assurance;
- improve controls following incidents and exercises.

---

# Chapter 17 Key Principles

1. **AI incident management is broader than cybersecurity incident response.**
2. **AI incidents must be classified according to observable facts and defined criteria.**
3. **Security, safety, privacy, operational, fraud, and regulatory dimensions may overlap but should not be conflated.**
4. **Containment is not eradication.**
5. **Eradication is not recovery.**
6. **Recovery is not automatically trusted recovery.**
7. **Rollback is not proof that the underlying problem has been eliminated.**
8. **Shutdown capability is an emergency control, not a complete resilience strategy.**
9. **Business continuity and disaster recovery address different but interconnected objectives.**
10. **Regulatory assessment must be distinguished from regulatory notification.**
11. **Internal governance thresholds must not be represented as statutory thresholds without authoritative support.**
12. **Supplier involvement does not automatically transfer the organization's own responsibilities.**
13. **Documentation does not demonstrate operational capability.**
14. **Exercises provide evidence of preparedness but are not automatically proof of compliance.**
15. **Monitoring is not equivalent to assurance.**
16. **Automation does not eliminate human accountability.**
17. **Evidence must support incident reconstruction, regulatory assessment, and assurance.**
18. **Resilience requires demonstrated capability under disruption, not merely documented plans.**
19. **Continuous improvement should convert incidents, exercises, failures, and assurance findings into control improvements.**
20. **Internal `AI-IMR-*` identifiers are taxonomy identifiers and must not be presented as legal or regulatory provisions.**

---

# Chapter 17 Reference Model

```text
                         AI GOVERNANCE
                              |
                              v
                 ┌───────────────────────┐
                 │ AI INCIDENT MANAGEMENT │
                 └───────────┬───────────┘
                             |
       ┌─────────────────────┼─────────────────────┐
       |                     |                     |
       v                     v                     v
   SECURITY                SAFETY                PRIVACY
       |                     |                     |
       └─────────────────────┼─────────────────────┘
                             |
                             v
                    INCIDENT TAXONOMY
                             |
                             v
                  SEVERITY & CLASSIFICATION
                             |
                             v
                         ESCALATION
                             |
                             v
                  CONTAINMENT / ERADICATION
                             |
                             v
                 ROLLBACK / SHUTDOWN / KILL
                             |
                             v
                    DISASTER RECOVERY
                             |
                             v
                 BUSINESS CONTINUITY
                             |
                             v
                   CRISIS MANAGEMENT
                             |
                             v
                REGULATORY ASSESSMENT
                             |
                             v
                 REGULATORY NOTIFICATION
                             |
                             v
                       ASSURANCE
                             |
                             v
                 CONTINUOUS IMPROVEMENT
```

Chapter 17 therefore provides the operational and governance foundation for managing AI incidents from initial detection through response, containment, recovery, continuity, regulatory engagement, assurance, and organizational learning.
