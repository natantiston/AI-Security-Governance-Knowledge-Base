# Chapter 16 — AI Third-Party and Supply-Chain Security

## Overview

Chapter 16 addresses the governance, security, risk management, assurance, resilience, and lifecycle management of third-party and supply-chain dependencies within AI systems.

Modern AI systems rarely operate as isolated technologies. They commonly depend on:

* Large Language Model providers
* Foundation model providers
* AI SaaS platforms
* Cloud AI services
* Open-source models
* AI model marketplaces
* External AI APIs
* Third-party datasets
* Software libraries
* Model artifacts
* Model registries
* Containers
* Infrastructure providers
* Subprocessors
* Fourth-party providers
* External security and AI services

These dependencies create risks that extend beyond the organization's direct technical boundary.

Chapter 16 therefore examines the AI supply chain from **initial third-party selection through acquisition, integration, operation, monitoring, change, incident response, resilience, assurance, and exit**.

---

## Chapter Objectives

The objectives of this chapter are to establish a comprehensive understanding of:

1. AI third-party risk management.
2. AI vendor governance.
3. Large Language Model provider risk.
4. AI SaaS risk.
5. Cloud AI provider risk.
6. Foundation model provider risk.
7. Open-source AI model risk.
8. AI model marketplace risk.
9. AI API and third-party service security.
10. Third-party dataset risk.
11. AI software supply-chain security.
12. AI model supply-chain security.
13. SBOM and AI Bill of Materials governance.
14. Model provenance and supply-chain integrity.
15. AI vendor due diligence.
16. AI security questionnaires and assessments.
17. Contractual AI security requirements.
18. DPA, SLA, and right-to-audit requirements.
19. AI vendor exit and concentration risk.
20. Enterprise AI third-party risk management.

---

# Chapter Structure

## 16.01 — AI Third-Party Risk Management Foundations

Establishes the foundational concepts required to manage AI third-party risk.

Key areas include:

* AI third-party risk
* Third-party dependency
* AI supply-chain risk
* Trust boundaries
* Supplier classification
* Criticality
* Risk ownership
* Third-party governance
* Risk assessment
* Due diligence
* Supplier monitoring
* Assurance
* Concentration risk
* Exit risk
* Enterprise governance

The topic establishes the conceptual foundation for the remainder of Chapter 16.

---

## 16.02 — AI Vendor Risk Management

Examines governance of vendors that provide AI technologies, platforms, models, services, infrastructure, data, or supporting capabilities.

Key areas include:

* Vendor identification
* Vendor classification
* Vendor criticality
* Vendor due diligence
* Security assessment
* Privacy assessment
* Regulatory assessment
* Contractual governance
* Vendor monitoring
* Vendor performance
* Vendor incidents
* Vendor assurance
* Vendor concentration
* Vendor exit

The objective is to establish a lifecycle-based AI vendor risk-management approach.

---

## 16.03 — Large Language Model Provider Risk

Addresses risks arising from dependence on external Large Language Model providers.

Key areas include:

* LLM provider dependency
* Provider trust boundaries
* Data processing
* Training-data use
* Retention
* Deletion
* API security
* Model changes
* Provider assurance
* Model versioning
* Provider incidents
* Resilience
* Concentration
* Portability
* Exit
* Continuous assurance

The topic distinguishes provider assurance from assurance over the organization's actual implementation and use case.

---

## 16.04 — AI SaaS Risk

Examines security and governance risks associated with AI Software-as-a-Service platforms.

Key areas include:

* AI SaaS dependency
* SaaS architecture
* Data boundaries
* Identity and access
* API security
* Tenant isolation
* Data protection
* Subprocessors
* Software supply chain
* Model dependencies
* Licensing
* Change management
* Availability
* Concentration
* Exit
* Assurance
* Enterprise AI SaaS governance

The topic addresses AI SaaS as both a technology dependency and a third-party risk relationship.

---

## 16.05 — Cloud AI Provider Risk

Examines AI workloads operated through cloud providers and cloud AI platforms.

Key areas include:

* Shared responsibility
* Cloud AI architecture
* Identity
* Network security
* Storage
* Model services
* APIs
* Vector stores
* Retrieval
* Agent security
* Cloud dependencies
* Provider assurance
* Multi-region resilience
* Concentration
* Portability
* Disaster recovery
* Exit
* Continuous monitoring

The topic emphasizes that cloud-provider controls do not automatically establish security of the customer's AI implementation.

---

## 16.06 — Foundation Model Provider Risk

Addresses risks associated with organizations relying on external foundation-model providers.

Key areas include:

* Foundation-model dependency
* Provider boundaries
* Model governance
* Training-data considerations
* Model provenance
* Model evaluation
* Model changes
* Data governance
* Provider assurance
* Incident management
* Resilience
* Concentration
* Exit
* Strategic dependency
* Continuous assurance

The topic examines foundation models as strategic supply-chain dependencies.

---

## 16.07 — Open-Source AI Model Risk

Examines the security and governance risks associated with acquiring and using open-source AI models.

Key areas include:

* Open-source model provenance
* Publisher and maintainer risk
* Repository security
* Model authenticity
* Model integrity
* Model weights
* Fine-tuning
* Quantization
* Conversion
* Licensing
* Model supply chain
* Software dependencies
* Model evaluation
* Vulnerabilities
* Backdoors
* Poisoning
* Resilience
* Exit
* Assurance

A central principle is:

**Open-source availability ≠ Security Assurance.**

---

## 16.08 — AI Model Marketplaces

Addresses the risks associated with acquiring models through AI model marketplaces and distribution platforms.

Key areas include:

* Marketplace governance
* Publisher verification
* Artifact authenticity
* Model provenance
* Model integrity
* Mirrors
* Model modification
* Licensing
* Model evaluation
* Marketplace security
* Supply-chain security
* Model dependencies
* Incident management
* Concentration
* Portability
* Exit
* Continuous assurance

The topic emphasizes that publicly available or popular models should not automatically be treated as trusted enterprise artifacts.

---

## 16.09 — AI API Security and Third-Party Services

Examines security risks associated with external AI APIs and supporting third-party services.

Key areas include:

* API dependency
* Authentication
* Authorization
* API keys
* Secrets
* Rate limiting
* Data minimization
* Data retention
* Provider data use
* Subprocessors
* API changes
* Model changes
* Tool integration
* Agent security
* Incident management
* Resilience
* Provider concentration
* Portability
* Exit
* Continuous monitoring

The topic distinguishes API availability from actual business resilience.

---

## 16.10 — Third-Party Dataset Risk

Examines risks associated with datasets obtained from external parties.

Key areas include:

* Dataset provenance
* Data lineage
* Data integrity
* Data authenticity
* Data quality
* Dataset poisoning
* Licensing
* Intellectual property
* Privacy
* Sensitive data
* Data minimization
* Retention
* Deletion
* Dataset versioning
* Dataset changes
* Data supply chain
* Dataset concentration
* Recovery
* Exit
* Assurance

The topic establishes dataset governance as a critical component of AI supply-chain security.

---

## 16.11 — AI Software Supply Chain

Examines software dependencies required to develop, build, deploy, and operate AI systems.

Key areas include:

* Direct dependencies
* Transitive dependencies
* AI frameworks
* AI SDKs
* Package repositories
* Package provenance
* Artifact integrity
* Software signing
* Dependency confusion
* Typosquatting
* Malicious packages
* Build security
* CI/CD security
* Software attestation
* Vulnerability management
* SBOM
* Runtime security
* Dependency concentration
* Software supply-chain resilience

The topic establishes software supply-chain governance as a core component of AI security.

---

## 16.12 — Model Supply Chain

Examines the supply chain associated specifically with AI model artifacts.

Key areas include:

* Model artifacts
* Model weights
* Checkpoints
* Serialization
* Model repositories
* Model publishers
* Model maintainers
* Model provenance
* Model lineage
* Model parentage
* Model transformation
* Model integrity
* Model hashes
* Model signatures
* Model authenticity
* Model tampering
* Model backdoors
* Model poisoning
* Model release governance
* Model versioning
* Model evaluation
* Model recovery
* Model substitution
* Model exit

The topic treats the model itself as a supply-chain asset rather than merely as an application component.

---

## 16.13 — SBOM and AI Bill of Materials

Examines component visibility and dependency management through Software Bills of Materials and AI Bills of Materials.

Key areas include:

* SBOM
* AI BOM
* Component inventory
* Model dependencies
* Dataset dependencies
* Software dependencies
* API dependencies
* Infrastructure dependencies
* Component identity
* Provenance
* BOM integrity
* BOM completeness
* BOM accuracy
* BOM freshness
* Vulnerability mapping
* Dependency graphs
* Supply-chain visibility
* Continuous monitoring
* Automated analysis
* Enterprise BOM governance

The topic establishes BOM capabilities as a visibility mechanism for complex AI supply chains.

---

## 16.14 — Model Provenance and Supply-Chain Integrity

Examines how organizations establish confidence in the origin, lineage, identity, integrity, and transformation history of AI models.

Key areas include:

* Model provenance
* Provenance chains
* Model lineage
* Model parentage
* Model transformation
* Model artifacts
* Model repositories
* Publisher verification
* Model authenticity
* Model hashes
* Model signatures
* Model tampering
* Model substitution
* Model backdoors
* Model poisoning
* Provenance verification
* Integrity monitoring
* Behavioral integrity
* Dependency analysis
* Supply-chain compromise
* Resilience
* Exit
* Continuous assurance

Core distinctions include:

**Provenance ≠ Integrity.**

**Integrity ≠ Authenticity.**

**Authenticity ≠ Security.**

**Hash Verification ≠ Model Trustworthiness.**

**Signature Verification ≠ Model Security.**

**Model Evaluation ≠ Complete Assurance.**

**Alternative Model ≠ Tested Substitute.**

**Documented Recovery ≠ Tested Recovery.**

**Framework Mapping ≠ Regulatory Applicability.**

**Internal Governance Control ≠ Statutory Requirement.**

---

## 16.15 — AI Vendor Due Diligence

Establishes the methodology for evaluating AI vendors before entering or expanding a third-party relationship.

Key areas include:

* Vendor identification
* Vendor ownership
* Security posture
* AI governance
* Technical architecture
* Model governance
* Data governance
* Privacy
* Compliance
* Subprocessors
* Fourth parties
* Incident management
* Business continuity
* Disaster recovery
* Supply-chain security
* Assurance evidence
* Financial and operational resilience
* Concentration
* Exit readiness

---

## 16.16 — AI Security Questionnaires and Assessments

Examines structured methods for collecting and evaluating AI vendor security information.

Key areas include:

* AI security questionnaires
* Vendor assessment
* Evidence requirements
* Questionnaire design
* Risk-based questions
* Control validation
* Technical evidence
* Independent assurance
* Security architecture
* Model security
* Data security
* Privacy
* AI governance
* Supply-chain security
* Incident response
* Resilience
* Scoring limitations
* Assessment lifecycle
* Continuous reassessment

Questionnaires should be treated as evidence-collection mechanisms rather than automatically accepted as proof of security.

---

## 16.17 — Contractual AI Security Requirements

Examines how AI security requirements can be translated into contractual obligations.

Key areas include:

* Security clauses
* AI governance clauses
* Data-use restrictions
* Model security
* Provenance requirements
* Incident notification
* Vulnerability management
* Change notification
* Subprocessor controls
* Audit rights
* Assurance requirements
* Business continuity
* Disaster recovery
* Service levels
* Exit requirements
* Data deletion
* Regulatory cooperation
* Liability
* Risk allocation

Contractual requirements should be distinguished from statutory and regulatory requirements.

---

## 16.18 — DPA, SLA and Right-to-Audit Requirements

Examines contractual mechanisms governing AI data processing, service performance, and assurance rights.

Key areas include:

* Data Processing Agreements
* Controller and processor relationships
* Data-processing instructions
* Data retention
* Data deletion
* Subprocessors
* International transfers
* Service-Level Agreements
* Availability
* Recovery
* Incident response
* Security commitments
* Audit rights
* Assessment rights
* Evidence
* Certifications
* Independent assurance
* Regulatory cooperation

The topic connects privacy, operational resilience, and third-party assurance.

---

## 16.19 — AI Vendor Exit and Concentration Risk

Examines risks arising from excessive dependence on AI providers and the practical ability to replace them.

Key areas include:

* Vendor concentration
* Model concentration
* Infrastructure concentration
* Geographic concentration
* Common-mode dependency
* Lock-in
* Switching costs
* Portability
* Data portability
* Model portability
* Behavioral portability
* Alternative providers
* Substitution testing
* Exit planning
* Exit testing
* Recovery
* Resilience
* Strategic dependency

A key principle is:

**Provider diversity ≠ Effective diversification.**

---

## 16.20 — Enterprise AI Third-Party Risk Management Framework

Integrates the concepts from the preceding topics into an enterprise-level AI third-party risk-management framework.

Key areas include:

* Governance
* Risk appetite
* Third-party inventory
* AI vendor classification
* Criticality
* Due diligence
* Security assessments
* Questionnaires
* Contractual controls
* Data protection
* Technical controls
* Supply-chain security
* Continuous monitoring
* Assurance
* Incident management
* Resilience
* Concentration
* Exit
* Metrics
* Automation
* Internal audit
* Management reporting
* Regulatory traceability
* Maturity
* Continuous improvement

The enterprise framework should connect procurement, legal, privacy, security, risk, AI governance, business continuity, supplier management, and internal audit.

---

# Chapter 16 Governance Model

The chapter follows an AI third-party lifecycle:

```text
Identify
   |
   v
Classify
   |
   v
Assess
   |
   v
Due Diligence
   |
   v
Contract
   |
   v
Acquire
   |
   v
Integrate
   |
   v
Deploy
   |
   v
Monitor
   |
   v
Assure
   |
   v
Respond
   |
   v
Reassess
   |
   v
Exit / Replace
```

The lifecycle should be supported by:

* Risk ownership
* Evidence
* Control testing
* Continuous monitoring
* Supplier management
* Security engineering
* Privacy governance
* Legal review
* Business continuity
* Internal audit

---

# Core Chapter Principles

The following principles apply throughout Chapter 16:

1. **Third-party dependency ≠ Third-party assurance.**
2. **Supplier claim ≠ Verified evidence.**
3. **Certification ≠ Complete assurance.**
4. **Contractual right ≠ Demonstrated operational capability.**
5. **Provider security ≠ Customer security.**
6. **Model integrity ≠ Application security.**
7. **Model provenance ≠ Model security.**
8. **Open-source availability ≠ Trustworthiness.**
9. **Model popularity ≠ Security assurance.**
10. **Artifact signature ≠ Absence of vulnerabilities.**
11. **Hash verification ≠ Trustworthiness.**
12. **BOM existence ≠ BOM completeness.**
13. **BOM completeness ≠ BOM accuracy.**
14. **Vulnerability identification ≠ Vulnerability absence.**
15. **Multiple providers ≠ Effective diversification.**
16. **Multiple models ≠ Independence.**
17. **Alternative provider ≠ Tested substitute.**
18. **Data export ≠ Practical portability.**
19. **Technical portability ≠ Behavioral equivalence.**
20. **Documented recovery ≠ Tested recovery.**
21. **Backup ≠ Recovery capability.**
22. **Exit plan ≠ Exit readiness.**
23. **Monitoring ≠ Assurance.**
24. **Automation ≠ Accountability.**
25. **Risk acceptance ≠ Removal of risk.**
26. **Framework mapping ≠ Regulatory applicability.**
27. **Internal control ≠ Statutory requirement.**
28. **Recommended practice ≠ Legal obligation.**
29. **Contractual requirement ≠ Universal regulatory requirement.**
30. **Provider notification ≠ Organization's own legal notification obligation.**

---

# Legal, Regulatory and GRC Distinction

Throughout Chapter 16, requirements should be categorized according to their actual source.

```text
Law / Regulation
       |
       v
Applicable Legal Requirement
       |
       v
Organizational Interpretation
       |
       v
Internal Policy
       |
       v
Governance Control
       |
       v
Implementation Practice
```

The following categories should not be conflated:

### Legal Requirement

A requirement imposed by applicable legislation or regulation.

### Regulatory Authority

A power, obligation, or requirement established by a competent authority.

### Contractual Requirement

An obligation established through a binding agreement.

### Standard

A requirement or control framework established by a recognized standards organization.

### Internal Governance Control

An organizational control adopted to manage risk.

### Recommended Practice

A useful implementation practice that is not necessarily legally mandatory.

This distinction is essential when mapping Chapter 16 controls to:

* EU AI Act
* GDPR
* NIS2
* DORA
* Sector-specific regulation
* National legislation
* ISO standards
* NIST frameworks
* Organizational policies
* Supplier contracts

---

# Chapter 16 Assurance Model

AI third-party assurance should consider multiple evidence layers:

```text
Supplier Assertions
        |
        v
Supplier Evidence
        |
        v
Contractual Commitments
        |
        v
Technical Validation
        |
        v
Operational Evidence
        |
        v
Independent Assurance
        |
        v
Continuous Monitoring
        |
        v
Enterprise Risk Decision
```

No single evidence source should automatically be treated as complete assurance.

Assurance should consider:

* Scope
* Relevance
* Independence
* Recency
* Completeness
* Evidence quality
* Control effectiveness
* Residual uncertainty

---

# Chapter 16 Strategic Objective

The strategic objective of Chapter 16 is to enable organizations to use third-party AI capabilities while maintaining appropriate control over:

* Security
* Privacy
* Data
* Models
* Software
* Infrastructure
* Suppliers
* Dependencies
* Supply-chain integrity
* Regulatory exposure
* Operational resilience
* Concentration
* Exit capability

The central governance principle is:

**AI third-party risk must be managed as a lifecycle and ecosystem problem, not merely as a vendor questionnaire exercise.**

---

# Chapter Completion

Chapter 16 establishes the AI third-party and supply-chain security foundation required for enterprise AI governance.

It connects:

**Third-Party Risk → Vendor Risk → Model Risk → Data Risk → Software Supply Chain → Model Supply Chain → Provenance → Assurance → Contracts → Resilience → Exit → Enterprise Governance**

The chapter provides the foundation for evaluating and governing external AI dependencies throughout their complete lifecycle.
