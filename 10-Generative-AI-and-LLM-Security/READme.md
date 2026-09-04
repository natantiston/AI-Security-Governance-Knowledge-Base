# Chapter 10 — AI Threats and Attack Techniques

## Purpose

Chapter 10 establishes a structured security and governance knowledge base for understanding, preventing, detecting, responding to, and assuring threats and attack techniques targeting AI systems, particularly LLM-based applications, RAG systems, agents, tools, data pipelines, model infrastructure, and AI supply chains.

The chapter follows an enterprise security perspective rather than treating AI threats as isolated model-behavior problems.

## Core Security Model

The chapter uses the following specialization chain:

**LLM Threat → Attack Surface → Security Control → Risk → Governance → Evidence → Monitoring → Incident Response**

This means every threat should ultimately be connected to:

- the technical attack surface;
- preventive and detective controls;
- enterprise risk;
- governance ownership;
- auditable evidence;
- continuous monitoring;
- incident response;
- assurance.

## Chapter Structure

Each topic is divided into four parts:

### Part 1 — Foundations and Core Concepts

Part 1 establishes the conceptual foundation of the threat.

It covers:

- definition;
- security problem;
- attack characteristics;
- attack surface;
- attack lifecycle;
- relationships with other AI threats;
- confidentiality, integrity, and availability;
- enterprise risk;
- Zero Trust;
- defense in depth;
- high-impact AI considerations;
- security objectives;
- fundamental security principles.

### Part 2 — Technical Security and Control Mechanisms

Part 2 translates the threat into technical controls.

It covers areas such as:

- identity;
- authorization;
- least privilege;
- input and output controls;
- data security;
- tool and agent controls;
- network security;
- isolation;
- resource controls;
- monitoring;
- detection;
- logging;
- containment;
- rollback;
- emergency controls;
- independent enforcement.

### Part 3 — Governance, Risk, GRC, and Operational Controls

Part 3 converts the technical threat into an enterprise governance capability.

It covers:

- ownership and accountability;
- risk classification;
- AI application tiering;
- risk registers;
- risk appetite;
- data governance;
- model governance;
- tool and agent governance;
- third-party and supply-chain governance;
- security requirements;
- threat modeling;
- secure SDLC;
- change management;
- testing;
- monitoring;
- incident response;
- SOC integration;
- evidence and auditability;
- GRC integration;
- risk-to-control traceability;
- continuous control monitoring;
- independent assurance;
- maturity.

### Part 4 — Advanced Enterprise Application, Assurance, and Operationalization

Part 4 extends the threat into an enterprise-scale operating model.

It covers:

- enterprise security architecture;
- AI security gateways;
- policy-as-code;
- Zero Trust;
- dynamic authorization;
- fine-grained controls;
- agentic AI security;
- security observability;
- SOC integration;
- incident response;
- kill switches;
- blast-radius reduction;
- cryptographic integrity;
- supply-chain assurance;
- continuous and adversarial testing;
- security dashboards;
- risk-based assurance;
- continuous control monitoring;
- security drift;
- risk quantification;
- assurance packages;
- lifecycle governance;
- enterprise integration;
- strategic security principles.

---

# Topics Covered

## 10.01 — [Chapter Topic]

Foundational AI security threat topic.

## 10.02 — [Chapter Topic]

AI security threat and attack technique topic.

## 10.03 — Prompt Security

Prompt security treats prompts and model context as security-sensitive control surfaces.

Key principle:

> Treat prompts and model context as security-sensitive control surfaces, not merely text.

## 10.04 — System Prompts and Prompt Governance

System prompts are treated as managed enterprise artifacts rather than informal configuration.

Key principle:

> System prompts are behavioral controls, not substitutes for deterministic security enforcement.

## 10.05 — Prompt Injection

Prompt injection is treated as an instruction-integrity threat involving malicious or untrusted instructions entering AI context.

Key principle:

> Externally supplied instructions and retrieved content must be treated as potentially untrusted.

## 10.06 — Direct Prompt Injection

Direct prompt injection focuses on attacks in which an attacker directly manipulates the model's instruction context.

Key principle:

> Prompt behavior must never be confused with enterprise security authorization.

## 10.07 — Indirect Prompt Injection

Indirect prompt injection focuses on malicious instructions embedded in externally sourced or retrieved content.

Key principle:

> Externally sourced content must be treated as potentially hostile data even when it originates from a legitimate business system.

## 10.08 — Jailbreaking

Jailbreaking focuses on techniques intended to bypass model safeguards or behavioral restrictions.

Key principle:

> A successful jailbreak should remain a model-security failure and must not automatically become an authorization failure.

## 10.09 — System Prompt Leakage

System prompt leakage addresses disclosure of system instructions, hidden behavioral configuration, and related information.

Key principle:

> System prompts should be treated as security-sensitive configuration, not secret storage or primary authorization mechanisms.

## 10.10 — Sensitive Information Disclosure

Sensitive information disclosure addresses unauthorized exposure of sensitive data through AI systems.

Key principle:

> Sensitive information should be authorized before entering AI context and validated again before leaving the AI system.

## 10.11 — Data Poisoning

Data poisoning addresses malicious or compromised data influencing training, fine-tuning, RAG, evaluation, feedback, embeddings, or AI behavior.

Key principle:

> Protect the integrity and trustworthiness of AI data before it enters learning or inference.

## 10.12 — Model Inversion Attacks

Model inversion addresses inference of sensitive information from model behavior or outputs.

Key principle:

> A model trained on sensitive information can become an inference surface rather than a trusted confidentiality boundary.

## 10.13 — Membership Inference Attacks

Membership inference addresses attempts to determine whether particular information was included in model training data.

Key principle:

> Model interfaces can become privacy inference channels.

## 10.14 — Data Extraction Attacks

Data extraction addresses unauthorized retrieval of information through AI-mediated access.

Key principle:

> AI-mediated access must never create a path around established enterprise authorization boundaries.

## 10.15 — Data Exfiltration Through AI Systems

This topic addresses the use of AI systems as channels for unauthorized data transfer.

Key principle:

> Sensitive information must not cross an AI system's security boundary unless the data, destination, identity, purpose, and transfer mechanism are independently authorized.

## 10.16 — Excessive Agency

Excessive agency addresses AI systems possessing more authority, autonomy, access, or operational capability than required.

Key principle:

> AI autonomy must never exceed the authority necessary to perform its approved business purpose.

## 10.17 — Improper Output Handling

Improper output handling addresses risks created when AI-generated output is treated as trusted, executable, or authoritative input.

Key principle:

> AI-generated output must never acquire trusted, executable, or authoritative status merely because it originated from an approved AI system.

## 10.18 — Model Denial of Service and Unbounded Consumption

This topic addresses uncontrolled computational, operational, and financial resource consumption.

Key principle:

> No AI user, application, model, or agent should be capable of consuming unlimited enterprise or third-party resources merely because the underlying AI capability technically permits it.

## 10.19 — LLM Supply-Chain and Application Security

This topic addresses security risks across models, datasets, dependencies, frameworks, APIs, plugins, tools, agents, providers, and AI applications.

Key principle:

> Every AI model, dataset, dependency, framework, plugin, tool, provider, API, and application component must remain identifiable, authorized, integrity-protected, risk-assessed, monitored, and replaceable throughout its lifecycle.

## 10.20 — Insecure AI Model Configuration

This topic addresses security weaknesses caused by insecure model, application, agent, infrastructure, data, network, provider, or operational configuration.

Key principle:

> AI model configuration must be treated as a security-critical control surface rather than a collection of technical settings.

---

# Cross-Chapter Security Principles

## 1. Model Behavior Is Not Authorization

A recurring principle throughout Chapter 10 is:

**Model Behavior ≠ Security Authorization**

The model should never be the sole authority determining whether a user may:

- access data;
- invoke a tool;
- execute code;
- perform a transaction;
- communicate externally;
- modify infrastructure;
- consume resources.

Authorization should be independently enforced.

## 2. Prompt Instructions Are Not Security Controls

Instructions can influence model behavior, but they should not be treated as deterministic authorization, DLP, network, identity, or privilege controls.

## 3. AI Is Part of a Larger Security Boundary

The effective AI security boundary includes:

- models;
- prompts;
- context;
- RAG;
- memory;
- data;
- agents;
- tools;
- APIs;
- applications;
- infrastructure;
- networks;
- providers;
- dependencies.

## 4. Least Privilege

AI systems should receive only the:

- data;
- tools;
- permissions;
- network access;
- credentials;
- compute;
- autonomy

required for the approved business purpose.

## 5. Zero Trust

AI components should not receive permanent trust simply because they are:

- inside the enterprise;
- previously approved;
- from a known provider;
- open source;
- authentic;
- technically valid.

Trust should be continuously evaluated.

## 6. Defense in Depth

No single AI security mechanism should be expected to prevent all attacks.

A mature architecture uses multiple independent layers:

```text
Identity
   ↓
Authorization
   ↓
Data Security
   ↓
Prompt / Context Security
   ↓
Model Security
   ↓
Tool / Agent Security
   ↓
Network Security
   ↓
Output Security
   ↓
Resource Security
   ↓
Monitoring
   ↓
Detection
   ↓
Incident Response
```

## 7. Blast-Radius Reduction

The organization should assume that individual AI components can eventually fail or become compromised.

The objective is to ensure that:

**Component Compromise ≠ Enterprise Compromise**

Compromise should remain bounded by:

- privilege segmentation;
- tenant isolation;
- network segmentation;
- data authorization;
- tool authorization;
- resource limits;
- egress controls;
- monitoring;
- emergency response.

## 8. Continuous Assurance

AI security cannot rely solely on point-in-time certification.

The security posture must account for:

- model changes;
- configuration changes;
- provider changes;
- dependency changes;
- data changes;
- RAG changes;
- tool changes;
- behavioral drift;
- new vulnerabilities.

---

# Common Enterprise AI Security Architecture

The chapter consistently builds toward an architecture similar to:

```text
                    Enterprise AI Security
                             |
       +---------------------+---------------------+
       |                     |                     |
     Identity              Data                AI Platform
       |                     |                     |
   Authentication      Classification        Model Security
   Authorization       Authorization          Configuration
   PAM                 DLP                   Prompt Security
                       RAG                   Agent Security
                                             Tool Security
       |                     |                     |
       +---------------------+---------------------+
                             |
                      AI Security Gateway
                             |
                 +-----------+-----------+
                 |           |           |
              Model        Agent        RAG
                 |           |           |
                 +-----------+-----------+
                             |
                      Enterprise Systems
                             |
                 +-----------+-----------+
                 |           |           |
               APIs        Tools       Data
                 |
          Network / Egress Controls
                 |
          Monitoring / Detection
                 |
              SIEM / SOC
                 |
        Incident Response / SOAR
                 |
              GRC / Risk
                 |
        Independent Assurance
```

---

# Enterprise AI Security Lifecycle

Chapter 10 applies security throughout the AI lifecycle:

```text
Identify
   ↓
Classify
   ↓
Threat Model
   ↓
Define Requirements
   ↓
Design Controls
   ↓
Build
   ↓
Test
   ↓
Approve
   ↓
Deploy
   ↓
Monitor
   ↓
Detect
   ↓
Respond
   ↓
Assure
   ↓
Improve
   ↓
Retire
```

Security controls should remain active throughout the entire lifecycle.

---

# AI Threat-to-Control Model

A threat should be translated into an enterprise control chain:

```text
Threat
  ↓
Attack Surface
  ↓
Security Requirement
  ↓
Preventive Control
  ↓
Detective Control
  ↓
Response Control
  ↓
Evidence
  ↓
Risk Assessment
  ↓
Assurance
```

This provides traceability from technical threats to enterprise governance.

---

# AI Security Evidence Model

Evidence should demonstrate not only that a control exists, but that it operates effectively.

Examples include:

- configuration baselines;
- model inventories;
- AI BOMs;
- SBOMs;
- access-control records;
- authorization decisions;
- security-test results;
- adversarial testing;
- monitoring records;
- configuration-drift reports;
- vulnerability findings;
- incident records;
- exception records;
- risk acceptance;
- assurance reports.

---

# AI Security Monitoring Model

Monitoring should correlate:

```text
Identity
 ↓
AI Application
 ↓
Model
 ↓
Configuration
 ↓
Prompt / Context
 ↓
Data
 ↓
Agent
 ↓
Tool
 ↓
API
 ↓
Network
 ↓
Action
```

This enables the SOC and security teams to understand not only what happened, but how an AI threat moved through the environment.

---

# GRC Integration Model

Chapter 10 connects AI security engineering to enterprise GRC:

```text
AI Threat
   ↓
Risk
   ↓
Risk Owner
   ↓
Security Requirement
   ↓
Control
   ↓
Control Owner
   ↓
Evidence
   ↓
Control Test
   ↓
Monitoring
   ↓
Residual Risk
   ↓
Assurance
```

This provides a defensible relationship between AI threats and enterprise risk management.

---

# Maturity Model

A general Chapter 10 maturity model can be applied across individual AI threats.

| Level | Capability |
|---|---|
| 1 — Initial | Reactive controls, limited visibility |
| 2 — Managed | Basic policies, ownership, and controls |
| 3 — Defined | Standardized architecture, governance, testing |
| 4 — Automated | Policy-as-code, continuous monitoring, automated detection |
| 5 — Adaptive | Continuous assurance, risk-based enforcement, automated response |

Organizations should progress from individual technical controls toward integrated, continuously assured AI security.

---

# Core Chapter Principle

The central principle of Chapter 10 is:

> **AI security threats must be treated as enterprise security risks rather than isolated model-behavior problems. Every AI threat should be mapped to its attack surface, independently enforced controls, risk ownership, governance requirements, monitoring, evidence, incident response, and assurance mechanisms.**

The ultimate security objective is:

```text
AI Threat
   ↓
Contained at AI Boundary
   ↓
Independent Security Controls
   ↓
Detection
   ↓
Controlled Response
   ↓
Evidence
   ↓
Risk Management
   ↓
Continuous Assurance
```

A successful prompt injection, jailbreak, data-poisoning event, compromised dependency, insecure configuration, model failure, excessive agency condition, data-exfiltration attempt, or resource-abuse event should **not automatically become an enterprise compromise**.

The mature enterprise objective is:

**AI Threat → Controlled Exposure → Independent Enforcement → Detection → Containment → Recovery → Assurance**
