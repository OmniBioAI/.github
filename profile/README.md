# 🧬 OmniBioAI Studio

## AI-Native Computational Biology Platform

**OmniBioAI Studio** is an AI-native computational biology platform that
unifies bioinformatics workflows, scientific AI, biomedical knowledge,
reproducible execution, and governed computational infrastructure.

It provides a common operating layer for moving from:

**scientific question → data → workflow → computation → evidence → interpretation**

across local workstations, HPC clusters, containerized infrastructure,
and cloud execution environments.

Built for computational scientists, bioinformatics engineers, AI engineers,
and research teams developing reproducible biomedical AI systems.

---

## 📊 Platform at a Glance

| Platform | Scale |
|---|---:|
| Source repositories | **33** |
| Codebase | **[CURRENT LOC]** |
| Automated tests | **[CURRENT TEST COUNT]+** |
| Microservices / platform services | **28+** |
| Bioinformatics & ML plugins | **[CURRENT VERIFIED COUNT]** |
| Workflow bundles | **[CURRENT VERIFIED COUNT]** |
| Execution / HPC / cloud tools | **[CURRENT VERIFIED COUNT]** |
| Container artifacts | **[CURRENT VERIFIED COUNT]** |
| PubMed corpus | **39M+ abstracts** |
| Biomedical vector index | **75M+ vectors** |

📊 **Live architecture, service health, and platform metrics:**  
https://control.omnibioai.org

> Public counts distinguish verified/usable platform resources from
> registry entries where appropriate.

---

# 🌐 What OmniBioAI Does

OmniBioAI connects six major layers of computational biology:

```text
                     Scientific Question
                              │
                              ▼
                 ┌────────────────────────┐
                 │   Scientific AI Layer  │
                 │ Agents · RAG · Models  │
                 └───────────┬────────────┘
                             │
                             ▼
                 ┌────────────────────────┐
                 │ Bioinformatics Layer   │
                 │ Genomics · Multi-Omics │
                 └───────────┬────────────┘
                             │
                             ▼
                 ┌────────────────────────┐
                 │ Workflow Orchestration │
                 │ NF · WDL · CWL · Snake │
                 └───────────┬────────────┘
                             │
                             ▼
                 ┌────────────────────────┐
                 │ Execution Fabric       │
                 │ Local · HPC · Cloud    │
                 └───────────┬────────────┘
                             │
                             ▼
                 ┌────────────────────────┐
                 │ Provenance & Evidence  │
                 │ Lineage · Runs · Audit │
                 └───────────┬────────────┘
                             │
                             ▼
                 ┌────────────────────────┐
                 │ Security & Governance  │
                 │ IAM · Policy · Audit   │
                 └────────────────────────┘
````

---

# ✨ Core Capabilities

## 🧬 Multi-Omics Computing

Integrated computational workflows for:

* Genomics
* Transcriptomics
* Single-cell analysis
* Variant analysis
* Proteomics
* Functional annotation
* Pathway analysis
* Comparative genomics
* Biomedical knowledge integration

---

## 🤖 Scientific AI

AI services operate alongside deterministic computational workflows rather
than replacing them.

Capabilities include:

* Scientific workflow planning
* Biomedical RAG
* Literature-aware reasoning
* Biological knowledge retrieval
* Scientific hypothesis generation
* AI-assisted interpretation
* Agent-driven tool execution
* Model lifecycle management
* Human-in-the-loop scientific review

---

## 📚 Biomedical Knowledge & RAG

OmniBioAI integrates biomedical literature and structured biological
knowledge into a local retrieval and reasoning layer.

Current infrastructure includes:

* **39M+ PubMed abstracts**
* **75M+ biomedical vectors**
* Domain-oriented biomedical indexes
* Semantic retrieval
* Evidence-linked RAG
* Biological knowledge services
* Literature-aware scientific agents

External biological resources can be integrated through governed platform
services and APIs.

---

## ⚙️ Workflow Orchestration

OmniBioAI provides a common workflow layer supporting:

* Nextflow
* WDL
* Snakemake
* CWL

Workflows can execute through a unified computational architecture rather
than being tied to a single infrastructure backend.

---

## 🖥️ Execution Fabric

The execution layer supports:

* Local execution
* Slurm / HPC
* AWS Batch
* Azure Batch
* Kubernetes
* Containerized execution

The Tool Execution Service (TES) separates scientific workflow intent from
the infrastructure on which computation runs.

---

# 🔬 Reproducibility & Provenance

Reproducibility is a platform primitive rather than an afterthought.

OmniBioAI captures execution context including:

* Inputs
* References
* Tool versions
* Container/environment
* Workflow definition
* Execution backend
* DAG and lineage
* Logs and metrics
* Output artifacts

### Run Bundles

A Run Bundle provides an auditable record of a computational execution:

```text
Run Bundle
├── Inputs
├── References
├── Workflow
├── Toolchain
├── Containers
├── Execution Backend
├── DAG / Lineage
├── Logs
├── Metrics
└── Outputs
```

This makes computational results easier to reproduce, inspect, and audit.

---

# 🔐 Security & Governance

OmniBioAI is being engineered around zero-trust and least-privilege
principles for biomedical computational environments.

Current security architecture includes:

* Identity and Access Management
* JWT-based authentication
* RBAC / ABAC authorization
* Organization and tenant isolation
* SAML-based enterprise SSO
* API gateway enforcement
* Service-to-service identities
* Scoped Redis ACL identities
* Audit-event pipelines
* Policy enforcement
* Security posture monitoring
* Evidence-backed readiness tracking

### HIPAA-Aligned Engineering

The platform includes **HIPAA-aligned security controls** and evidence
tracking designed to support environments handling sensitive biomedical
data.

Technical safeguards include:

* PHI protection and secure data handling
* Least-privilege access controls
* Audit logging
* Retention controls
* Integrity verification
* Backup and recovery controls
* Security-event monitoring
* Evidence-backed control lifecycle tracking

OmniBioAI does **not** describe these controls as HIPAA certification.
Operational and organizational compliance remains dependent on the
deployment environment, policies, procedures, and applicable agreements.

---

# 🛡️ Auditable Security Architecture

Security events flow through a durable audit architecture:

```text
Platform Services
       │
       ▼
Audit Producers
       │
       ▼
 Redis Stream
 audit:events
       │
       ▼
Audit Worker
       │
       ▼
 Durable Audit Store
       │
       ├── Integrity Controls
       ├── Retention
       ├── Legal Hold
       ├── Evidence
       └── Operational Monitoring
```

Security controls are tracked using separate lifecycle states for:

**Implementation → Testing → Deployment → Operational Verification**

This avoids treating source-code implementation as equivalent to
production verification.

---

# 🏗️ Platform Architecture

![OmniBioAI Architecture](https://raw.githubusercontent.com/OmniBioAI/.github/main/profile/assets/omnibioai-architecture.png)

*AI-native computational biology architecture spanning scientific AI,
bioinformatics workflows, execution infrastructure, provenance,
security, governance, and observability.*

---

# 🧩 Platform Services

## 🚀 Core Platform

| Repository                   | Responsibility                                              |
| ---------------------------- | ----------------------------------------------------------- |
| **omnibioai**                | Main scientific workbench and plugin ecosystem              |
| **omnibioai-studio**         | Desktop platform and stack orchestration                    |
| **omnibioai-control-center** | Operations, security, readiness, and platform observability |
| **omnibioai-workbench**      | Scientific plugin and analysis execution                    |
| **omnibioai-launcher**       | Jupyter, VS Code, and RStudio integration                   |
| **omnibioai-sdk**            | Python platform SDK                                         |
| **omnibioai-utils**          | Platform automation, CI/CD, lifecycle and coverage tooling  |

## ⚙️ Execution & Workflows

| Repository                     | Responsibility                                 |
| ------------------------------ | ---------------------------------------------- |
| **omnibioai-tes**              | Unified local/HPC/cloud Tool Execution Service |
| **omnibioai-toolserver**       | Governed tool API                              |
| **omnibioai-tool-runtime**     | Container execution runtime                    |
| **omnibioai-tool-images**      | Bioinformatics and ML execution images         |
| **omnibioai-workflow-bundles** | Versioned reproducible workflows               |

## 🤖 AI & Knowledge

| Repository                   | Responsibility                                    |
| ---------------------------- | ------------------------------------------------- |
| **omnibioai-rag**            | Biomedical retrieval-augmented generation         |
| **omnibioai-dev-hub**        | Semantic development and AI intelligence services |
| **omnibioai-model-registry** | Governed model lifecycle and provenance           |

## 🔐 Identity, Security & Governance

| Repository                      | Responsibility                    |
| ------------------------------- | --------------------------------- |
| **omnibioai-auth**              | Authentication and identity       |
| **omnibioai-api-gateway**       | Zero-trust API gateway            |
| **omnibioai-policy-engine**     | RBAC/ABAC policy enforcement      |
| **omnibioai-hpc-policy-engine** | Computational quota governance    |
| **omnibioai-security-audit**    | Durable security-event processing |
| **omnibioai-security-sdk**      | Shared security primitives        |
| **omnibioai-iam-client**        | IAM client SDK                    |
| **omnibioai-usage-client**      | Usage-event SDK                   |

## 🧪 Scientific Infrastructure

| Repository           | Responsibility                            |
| -------------------- | ----------------------------------------- |
| **omnibioai-lims**   | Biological sample and metadata management |
| **omnibioai-data**   | Reference and example datasets            |
| **omnibioai-docs**   | Technical documentation                   |
| **omnibioai-videos** | Tutorials and onboarding                  |

---

# 🛠️ Technology

**Scientific Computing**

Python · R · Bioinformatics tools · Multi-omics

**Backend**

FastAPI · Django · MySQL · Redis · Redis Streams

**AI**

LLMs · RAG · Vector Search · Knowledge Graphs · Scientific Agents

**Workflow**

Nextflow · WDL · Snakemake · CWL

**Infrastructure**

Docker · Apptainer/SIF · Kubernetes · Slurm · AWS Batch · Azure Batch

**Frontend**

React · TypeScript · Vite

**Security**

IAM · JWT · RBAC · ABAC · SAML · Service Identities · Audit · Policy Enforcement

---

# 🧭 Engineering Principles

### Reproducibility Before Convenience

Scientific results should carry enough execution context to be reproduced
and audited.

### Deterministic Execution Before AI Reasoning

AI assists scientific workflows, but deterministic tools remain the
execution authority.

### Evidence Before Claims

Scientific interpretation should be connected to evidence and provenance.

### Least Privilege by Default

Users and services receive only the permissions and resources required for
their responsibilities.

### Human Review for Critical Decisions

AI-generated scientific interpretations remain subject to human review.

### Operational Verification Matters

A control is not considered operational simply because its source code
exists or its unit tests pass.

---

# 🚀 Explore OmniBioAI

🌐 **Website**
[https://omnibioai.org](https://omnibioai.org)

📊 **Platform Control Center**
[https://control.omnibioai.org](https://control.omnibioai.org)

🐙 **GitHub**
[https://github.com/OmniBioAI](https://github.com/OmniBioAI)

📦 **Container Registry**
[https://github.com/orgs/OmniBioAI/packages](https://github.com/orgs/OmniBioAI/packages)

🤗 **Hugging Face**
[https://huggingface.co/omnibioai](https://huggingface.co/omnibioai)

📚 **Documentation**
See `omnibioai-docs`

🎥 **Tutorials**
See `omnibioai-videos`

💬 **Discord**
[https://discord.gg/Hu6vgfAFn](https://discord.gg/Hu6vgfAFn)

🐦 **X / Twitter**
[https://twitter.com/OmniBioAI](https://twitter.com/OmniBioAI)

---

# 👨‍💻 Creator

**Manish Kumar**

Senior Computational Scientist · AI-Native Bioinformatics Engineer

18 years of experience spanning bioinformatics, multi-omics,
computational biology, HPC, cloud computing, and scientific AI across
the United States, Qatar, Malaysia, Saudi Arabia, and India.

Creator and lead engineer of OmniBioAI Studio.

Building computational systems at the intersection of:

**Biology × AI × Software Engineering × HPC × Reproducibility**

---

# 🌟 Vision

> Build the computational operating layer where biological data,
> scientific workflows, reproducible execution, and artificial intelligence
> converge to accelerate biomedical discovery.

---

⭐ Explore the platform, architecture, workflows, and open-source ecosystem.

