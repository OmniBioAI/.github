# 🧬 OmniBioAI

## AI-Native Computational Biology Platform

**OmniBioAI** is an AI-native computational biology platform that unifies bioinformatics workflows, scientific AI, biomedical knowledge, reproducible execution, and governed computational infrastructure.

It provides a common operating layer for moving from:

**scientific question → data → workflow → computation → evidence → interpretation**

across local workstations, HPC clusters, containerized infrastructure, and cloud execution environments.

Built for computational scientists, bioinformatics engineers, AI engineers, and research teams developing reproducible biomedical AI systems.

> **OmniBioAI Studio** is the primary user-facing environment for accessing and operating the platform.

---

## 🚀 Start Here

🌐 **Website**  
https://omnibioai.org

🖥️ **OmniBioAI Studio**  
https://github.com/OmniBioAI/omnibioai-studio

📚 **Documentation**  
https://github.com/OmniBioAI/omnibioai-docs

📊 **Platform Control Center**  
https://control.omnibioai.org

🧬 **Workflows**  
https://github.com/OmniBioAI/omnibioai-workflow-bundles

📦 **Containers**  
https://github.com/orgs/OmniBioAI/packages

🎥 **Tutorials**  
https://github.com/OmniBioAI/omnibioai-videos

---

## 📊 Platform at a Glance

| Platform | Scale |
|---|---:|
| Source repositories | **33** |
| Codebase | **5.2M+** |
| Automated tests | **65,000+** |
| Microservices / platform services | **28+** |
| Bioinformatics & AI/ML plugins | **500+** |
| Workflow bundles | **1,000+** |
| Execution / HPC / cloud tools | **12,000+** |
| Container artifacts | **1,500+** |
| PubMed corpus | **28M+ unique abstracts** |
| Biomedical vector index | **75M+ vectors** |

> Public counts distinguish verified or usable platform resources from registry entries where appropriate.

Live architecture, service health, and platform metrics:

**https://control.omnibioai.org**

---

# 🌐 From Scientific Question to Evidence

OmniBioAI connects the major layers required for modern computational biology:

![OmniBioAI Architecture](https://raw.githubusercontent.com/OmniBioAI/.github/main/profile/assets/OmniBioAI_Flow.png)


---

# ✨ Core Capabilities

## 🧬 Multi-Omics Computing

Integrated computational workflows for:

- Genomics
- Transcriptomics
- Single-cell analysis
- Variant analysis
- Proteomics
- Functional annotation
- Pathway analysis
- Comparative genomics
- Biomedical knowledge integration

## 🤖 Scientific AI

AI operates alongside deterministic scientific workflows rather than replacing them.

Capabilities include:

- Scientific workflow planning
- Biomedical RAG
- Literature-aware reasoning
- Biological knowledge retrieval
- Scientific hypothesis generation
- AI-assisted interpretation
- Agent-driven tool execution
- Model lifecycle management
- Human-in-the-loop scientific review

## 📚 Biomedical Knowledge & RAG

OmniBioAI integrates biomedical literature and structured biological knowledge into a local retrieval and reasoning layer.

Current infrastructure includes:

- **28M+ unique PubMed abstracts**
- **75M+ biomedical vectors**
- Domain-oriented biomedical indexes
- Semantic retrieval
- Evidence-linked RAG
- Biological knowledge services
- Literature-aware scientific agents

External biological resources can be integrated through governed platform services and APIs.

## ⚙️ Workflow Orchestration

A common workflow architecture supports:

**Nextflow · WDL · Snakemake · CWL**

Workflows can execute through a unified computational layer rather than being tied to a single infrastructure backend.

## 🖥️ Execution Fabric

Scientific workloads can run across:

**Local · Slurm/HPC · AWS Batch · Azure Batch · Kubernetes · Containers**

The **Tool Execution Service (TES)** separates scientific workflow intent from the infrastructure on which computation executes.

---

# 🔬 Reproducibility & Provenance

Reproducibility is a platform primitive rather than an afterthought.

OmniBioAI captures computational execution context including:

- Inputs and references
- Workflow definitions
- Tool and software versions
- Containers and environments
- Execution backend
- DAG and lineage
- Logs and metrics
- Output artifacts

### Run Bundles

Each execution can produce an auditable **Run Bundle**:

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

This makes computational results easier to reproduce, inspect, trace, and audit.

---

# 🏗️ Platform Architecture

![OmniBioAI Architecture](https://raw.githubusercontent.com/OmniBioAI/.github/main/profile/assets/Architecture.png)

*AI-native computational biology architecture spanning scientific AI, bioinformatics workflows, execution infrastructure, provenance, security, governance, and observability.*

---

# 🧩 Platform Ecosystem

## 🚀 Platform & User Experience

| Repository | Responsibility |
|---|---|
| **omnibioai** | Scientific platform and plugin ecosystem |
| **omnibioai-studio** | Primary user-facing environment and stack orchestration |
| **omnibioai-control-center** | Operations, security, readiness, and observability |
| **omnibioai-workbench** | Scientific plugin and analysis execution |
| **omnibioai-launcher** | Jupyter, VS Code, and RStudio integration |
| **omnibioai-sdk** | Python platform SDK |

## ⚙️ Execution & Workflows

| Repository | Responsibility |
|---|---|
| **omnibioai-tes** | Unified local/HPC/cloud Tool Execution Service |
| **omnibioai-toolserver** | Governed scientific tool API |
| **omnibioai-tool-runtime** | Container execution runtime |
| **omnibioai-tool-images** | Bioinformatics and AI/ML execution images |
| **omnibioai-workflow-bundles** | Versioned reproducible scientific workflows |

## 🤖 AI & Knowledge

| Repository | Responsibility |
|---|---|
| **omnibioai-rag** | Biomedical retrieval-augmented generation |
| **omnibioai-dev-hub** | Semantic development and AI intelligence services |
| **omnibioai-model-registry** | Governed model lifecycle and provenance |

## 🔐 Identity, Security & Governance

| Repository | Responsibility |
|---|---|
| **omnibioai-auth** | Authentication and identity |
| **omnibioai-api-gateway** | Zero-trust API gateway |
| **omnibioai-policy-engine** | RBAC/ABAC policy enforcement |
| **omnibioai-hpc-policy-engine** | Computational quota governance |
| **omnibioai-security-audit** | Durable security-event processing |
| **omnibioai-security-sdk** | Shared security primitives |
| **omnibioai-iam-client** | IAM client SDK |
| **omnibioai-usage-client** | Usage-event SDK |

## 🧪 Scientific Infrastructure

| Repository | Responsibility |
|---|---|
| **omnibioai-lims** | Biological sample and metadata management |
| **omnibioai-data** | Reference and example datasets |
| **omnibioai-docs** | Technical documentation |
| **omnibioai-videos** | Tutorials and onboarding |

---

# 🔐 Security & Governance

OmniBioAI is engineered around **zero-trust** and **least-privilege** principles for biomedical computational environments.

The security architecture includes:

- Identity and Access Management
- JWT-based authentication
- RBAC / ABAC authorization
- Organization and tenant isolation
- SAML-based enterprise SSO
- API gateway enforcement
- Service-to-service identities
- Scoped infrastructure identities
- Audit-event pipelines
- Policy enforcement
- Security posture monitoring
- Evidence-backed readiness tracking

Security controls are tracked through separate lifecycle states:

**Implementation → Testing → Deployment → Operational Verification**

This prevents source-code implementation or successful unit tests from being treated as equivalent to production verification.

## HIPAA-Aligned Engineering

OmniBioAI includes **HIPAA-aligned technical safeguards and evidence tracking** designed to support environments handling sensitive biomedical data.

These include:

**least-privilege access · audit logging · retention controls · integrity verification · backup and recovery · security monitoring · evidence-backed control tracking**

OmniBioAI does **not** describe these controls as HIPAA certification.

Operational and organizational compliance depends on the deployment environment, policies, procedures, agreements, and other applicable requirements.

---

# 🛠️ Technology

| Layer | Technologies |
|---|---|
| **Scientific Computing** | Python · R · Bioinformatics · Multi-omics |
| **AI** | LLMs · RAG · Vector Search · Knowledge Graphs · Scientific Agents |
| **Workflow** | Nextflow · WDL · Snakemake · CWL |
| **Backend** | FastAPI · Django · MySQL · Redis · Redis Streams |
| **Frontend** | React · TypeScript · Vite |
| **Infrastructure** | Docker · Apptainer/SIF · Kubernetes · Slurm · AWS Batch · Azure Batch |
| **Security** | IAM · JWT · RBAC · ABAC · SAML · Service Identities · Audit · Policy Enforcement |

---

# 🧭 Engineering Principles

### 🔬 Reproducibility Before Convenience

Scientific results should carry enough execution context to be reproduced and audited.

### ⚙️ Deterministic Execution Before AI Reasoning

AI assists scientific workflows, while deterministic computational tools remain the execution authority.

### 📚 Evidence Before Claims

Scientific interpretation should remain connected to evidence and provenance.

### 🔐 Least Privilege by Default

Users and services receive only the permissions and computational resources required for their responsibilities.

### 👥 Human Review for Critical Decisions

AI-generated scientific interpretations remain subject to human review.

### 🛡️ Operational Verification Matters

A security or operational control is not considered operational simply because its source code exists or its unit tests pass.

---

# 🚀 Explore OmniBioAI

| Resource | Link |
|---|---|
| 🌐 **Website** | https://omnibioai.org |
| 📊 **Control Center** | https://control.omnibioai.org |
| 🐙 **GitHub** | https://github.com/OmniBioAI |
| 📚 **Documentation** | https://github.com/OmniBioAI/omnibioai-docs |
| 🧬 **Workflows** | https://github.com/OmniBioAI/omnibioai-workflow-bundles |
| 📦 **Container Registry** | https://github.com/orgs/OmniBioAI/packages |
| 🤗 **Hugging Face** | https://huggingface.co/omnibioai |
| 🎥 **Tutorials** | https://github.com/OmniBioAI/omnibioai-videos |
| 💬 **Discord** | https://discord.gg/Hu6vgfAFn |
| 🐦 **X / Twitter** | https://twitter.com/OmniBioAI |

---

# 👨‍💻 Creator

## Manish Kumar

**Senior Computational Scientist · AI-Native Bioinformatics Engineer**

19 years of experience spanning bioinformatics, multi-omics, computational biology, HPC, cloud computing, software engineering, and scientific AI across the United States, Qatar, Malaysia, Saudi Arabia, and India.

**Creator and lead engineer of OmniBioAI.**

Building computational systems at the intersection of:

**Biology × AI × Software Engineering × HPC × Reproducibility**

---

# 🌟 Vision

> **Build the computational operating layer where biological data, scientific workflows, reproducible execution, and artificial intelligence converge to accelerate biomedical discovery.**

---

⭐ **Explore the platform, architecture, workflows, and open-source ecosystem at https://omnibioai.org**
