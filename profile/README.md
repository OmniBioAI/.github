# 🧬 OmniBioAI Studio

## AI-Native Bioinformatics Platform for the Future of Computational Biology

OmniBioAI Studio is an **AI-native bioinformatics platform** designed to accelerate scientific discovery through intelligent automation, reproducible workflows, and scalable computational infrastructure.

It provides a unified environment for **genomics, multi-omics, AI-driven biological reasoning, workflow orchestration, and reproducible computational research** across local machines, HPC clusters, and cloud environments.

🚀 Built for researchers, computational scientists, and developers building the next generation of biomedical AI systems.

---

## 📊 By the Numbers

| | |
|---|---|
| **3M+** lines of code | **4,000+** test files across the ecosystem |
| **33** repositories | **231** bioinformatics/ML plugins |
| **1,233** container images on GHCR (**1,000** ARM64 SIF + Docker) | **616** workflow bundles (Nextflow, WDL, CWL, Snakemake) |
| **36M** PubMed abstracts indexed | **12,110** execution, cloud, HPC, and orchestration tools |

📊 **[Live platform metrics & health →](https://control.omnibioai.org)** — real-time architecture, codebase stats, and service status, not just claims.

---

## 🌐 Platform Overview

OmniBioAI connects biological data, computational workflows, AI models, and scientific knowledge into a unified ecosystem.

```
Biological Data
      │
      ▼
 ┌──────────────────────┐
 │  OmniBioAI Platform  │
 └──────────────────────┘
      │
 ├── 🧬 Multi-Omics Analysis
 ├── 🤖 AI Agents & Scientific Reasoning
 ├── ⚙️ Workflow Orchestration
 ├── 🐳 Containerized Execution
 ├── 🖥 HPC & Cloud Compute
 ├── 📚 Knowledge Retrieval & RAG
 ├── 🔐 Security & Governance
 └── 🔬 Reproducible Research
```

---

# ✨ Core Capabilities

## 🧬 Multi-Omics Computing

Support for modern computational biology workflows:

* Genomics
* Transcriptomics
* Single-cell RNA sequencing
* Proteomics
* Variant analysis
* Functional annotation
* Biological pathway analysis
* Knowledge-driven discovery

---

## 🤖 AI-Powered Scientific Intelligence

OmniBioAI integrates AI systems designed for biological reasoning:

* AI-assisted workflow generation
* Biomedical knowledge retrieval
* Literature-aware analysis
* Scientific hypothesis generation
* Agent-driven computational workflows
* Model-assisted interpretation

---

## ⚙️ Unified Workflow Execution

Execute bioinformatics pipelines across multiple environments:

* Local workstation
* HPC clusters
* Slurm environments
* Cloud batch systems
* Containerized compute environments

**616 versioned workflow bundles** across:

* Nextflow
* WDL
* Snakemake
* CWL

---

# 🏗️ Platform Architecture

![OmniBioAI Architecture](https://raw.githubusercontent.com/OmniBioAI/.github/main/profile/assets/omnibioai-architecture.png)

*Unified AI-Native Bioinformatics Platform — 9-layer architecture from client access through security, observability, and development environments.*

---

# 🧩 Ecosystem Repositories

## 🚀 Core Platform

| Repository                   | Description                                             |
| ----------------------------- | -------------------------------------------------------- |
| **omnibioai**                 | Main Django workbench + 231 plugins                        |
| **omnibioai-studio**          | Electron desktop app — orchestrates the full stack        |
| **omnibioai-control-center**  | Platform monitoring and operational dashboard              |
| **omnibioai-workbench**       | Plugin execution environment                               |
| **omnibioai-launcher**        | Opens registry objects in Jupyter, VS Code, and RStudio    |
| **omnibioai-sdk**             | Python SDK client                                          |
| **omnibioai-utils**           | Ecosystem automation — stack lifecycle, CI/CD, coverage reporting |

---

## ⚙️ Workflow & Execution

| Repository                     | Description                                                |
| -------------------------------| ------------------------------------------------------------|
| **omnibioai-tes**              | Tool Execution Service for local, HPC, and cloud execution   |
| **omnibioai-toolserver**       | FastAPI tool API                                              |
| **omnibioai-tool-runtime**     | Cloud-agnostic container execution runtime                    |
| **omnibioai-tool-images**      | Bioinformatics and ML container images                        |
| **omnibioai-workflow-bundles** | Versioned reproducible workflow packages                      |

---

## 🤖 AI & Knowledge Systems

| Repository                   | Description                                      |
| ------------------------------| --------------------------------------------------|
| **omnibioai-rag**            | Biomedical retrieval augmented generation system   |
| **omnibioai-dev-hub**        | AI intelligence hub with semantic retrieval        |
| **omnibioai-model-registry** | ML model lifecycle and provenance management       |

---

## 🔐 Security & Governance

| Repository                     | Description                          |
| --------------------------------| ------------------------------------- |
| **omnibioai-auth**              | Authentication and identity services  |
| **omnibioai-api-gateway**       | Zero-trust API gateway                |
| **omnibioai-policy-engine**     | RBAC/ABAC policy enforcement          |
| **omnibioai-hpc-policy-engine** | GPU/CPU quota governance              |
| **omnibioai-security-audit**    | Security events and observability     |
| **omnibioai-security-sdk**      | Shared security framework             |
| **omnibioai-iam-client**        | Identity and access management client |
| **omnibioai-usage-client**      | Usage-metering event-emission SDK     |

---

## 💰 Billing & Operations

| Repository                | Description                                              |
| ---------------------------| -----------------------------------------------------------|
| **omnibioai-billing**      | Subscription billing, invoicing, and entitlement catalog  |
| **omnibioai-db-init**      | MySQL database initialization scripts                     |
| **omnibioai-dev-docker**   | GPU/DGX development environment image (CUDA, PyTorch)     |

---

## 🧪 Research Infrastructure

| Repository           | Description                               |
| ---------------------| -------------------------------------------|
| **omnibioai-lims**   | Biological sample and metadata management  |
| **omnibioai-data**   | Reference and example datasets              |
| **omnibioai-docs**   | Technical documentation                      |
| **omnibioai-videos** | Tutorials and onboarding resources           |

---

## 🎨 Design & Frontend

| Repository                    | Description                       |
| -------------------------------| ----------------------------------|
| **omnibioai-design-tokens**   | Shared design tokens and theme     |
| **omnibioai-ui**              | Shared UI component library        |
| **omnibioai-landing**         | Public-facing landing page         |

---

# 🔬 Design Principles

## Reproducibility First

Every analysis should be traceable:

* Input provenance
* Reference versions
* Tool versions
* Execution environment
* Workflow history
* Output artifacts

---

## AI With Scientific Guardrails

OmniBioAI follows:

✅ Deterministic execution before AI reasoning
✅ Evidence-based biological interpretation
✅ Human review for critical decisions
✅ Complete computational provenance

---

# 🛠️ Technology Stack

### Backend

* Python
* FastAPI
* Django
* MySQL
* Redis Streams

### Frontend

* React
* TypeScript
* Vite
* Design systems

### AI

* Large Language Models
* Retrieval Augmented Generation
* Vector search
* Knowledge graphs
* Scientific agents

### Infrastructure

* Docker
* Kubernetes
* Slurm
* Cloud batch computing

---

# 🚀 Getting Started

🌐 **Website**
https://omnibioai.org

📊 **Live Platform Stats**
https://control.omnibioai.org

🐙 **GitHub Organization**
https://github.com/OmniBioAI

📦 **Container Registry (1,233 images)**
https://github.com/orgs/OmniBioAI/packages

🤗 **Hugging Face**
https://huggingface.co/omnibioai

📚 **Documentation**
See the `omnibioai-docs` repository

🎥 **Tutorials**
See the `omnibioai-videos` repository

💬 **Discord**
https://discord.gg/Hu6vgfAFn

🐦 **Twitter**
https://twitter.com/OmniBioAI

---

# 👨‍💻 Creator

Created by **Manish Kumar**

🧬 Senior Computational Scientist | 🤖 AI-Native Bioinformatics Engineer

18 years across 🇺🇸 USA, 🇶🇦 Qatar, 🇲🇾 Malaysia, 🇸🇦 Saudi Arabia, and 🇮🇳 India, building genomics and precision medicine infrastructure for research and clinical environments.

🏥 Currently at the **University of Kansas Medical Center** — genomics, single-cell, exome & proteomics pipelines for rare disease and translational research.

Building intelligent computational systems at the intersection of:

**Biology × AI × Software Engineering × HPC**

---

# 🌟 Vision

> Build the operating layer where biological data, computational workflows, and artificial intelligence converge to accelerate discovery.

---

⭐ Star the repositories, explore the architecture, and join the future of AI-powered computational biology.
