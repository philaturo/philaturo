<div align="center">

# Phil Aturo

**Full Stack Engineer · DevSecOps · Geospatial Intelligence · Open Source**

*Building systems that are secure by design, intelligent by nature, and grounded in the real world.*

</div>

---

## About

Full Stack DevSecOps engineer and geospatial technologist based in Kisumu, Kenya. Currently on an intensive apprenticeship at **Zone01 Kisumu** — writing Go, JavaScript, and Python with a DevOps specialization track. My background in GIS gives me an uncommon lens: I think about systems spatially, about data as terrain, and about security as a perimeter problem at every layer.

---

## Status

| | |
|:--|:--|
| **Apprenticeship** | Zone01 Kisumu — Go, JavaScript, Python · DevOps specialization |
| **Active Builds** | ZoneBridge · Mtaani · Quorix (PaaS, in design) |
| **Specialization Track** | Container orchestration · CI/CD · Infrastructure as Code |
| **Open to** | Collaborations · Open source · Freelance DevSecOps work |

---

## Full Stack Web

| Project | Description | Stack | Status |
|:--------|:------------|:------|:-------|
| [ZoneBridge](https://github.com/philaturo/zonebridge) | Peer knowledge network for Zone01 apprentices. Skill-based help matching, project post-mortems, real-time presence. JWT auth, OAuth via Gitea. | Go · Gin · React · TypeScript · PostgreSQL · WebSocket | In Progress |
| [Mtaani](https://github.com/philaturo/Mtaani) | AI-powered responsible tourism platform for Kenya. Real-time safety monitoring, verified local businesses, geospatial routing, RAG-powered recommendations. | Elixir · Phoenix · LiveView · PostGIS · Groq · MapLibre · Redis | In Progress |
| [PESALOCAL](https://github.com/philaturo/PESALOCAL) | Financial tooling for local businesses in Kenya. Exploring a lightweight SaaS layer for the informal economy. | TypeScript | Early Stage |
| [Mtaa Guide](https://github.com/philaturo/Mtaa-Guide) | Original local guide prototype — predecessor to Mtaani. | — | Archived |

---

## Security & DevSecOps

> Security isn't a feature — it's the architecture.

| Project | Description | Stack | Status |
|:--------|:------------|:------|:-------|
| Security Audit CLI | Static analysis and dependency vulnerability scanner for Go and JS projects. Designed as a CI/CD plugin with SARIF output. | Go · Shell | Planned |
| Pipeline Security Harness | Hardened CI/CD pipeline templates with SAST, secret scanning, container image signing, and policy enforcement gates. | GitHub Actions · Docker · OPA | Planned |
| Threat Surface Mapper | Maps the attack surface of a running service: open ports, exposed endpoints, misconfigured headers, TLS grading. | Go · Python | Planned |

*See also: [Openway](https://github.com/philaturo/openway) — full DevSecOps pipeline applied to Web3 infrastructure. SAST, Trivy container scanning, Cosign signing, Vault injection, and Kubernetes network hardening.*
*DevSecOps projects are being actively designed as the Zone01 specialization progresses.*

---

## DevOps & Infrastructure

| Project | Description | Stack | Status |
|:--------|:------------|:------|:-------|
| [Zone01 Projects](https://github.com/philaturo/zone01-projects) | Training projects from Zone01 Kisumu: algorithms, systems programming, networking challenges, Go exercises. | Go | Active |
| Quorix | Open source application deployment platform. Developer-first PaaS — self-hostable, git-push deploys, environment management, logs, metrics. Built in the open from day one. | Go · TBD | In Design |
| IaC Starter Templates | Infrastructure-as-code templates for common setups: VPS hardening, reverse proxy configs, monitoring stacks. | Terraform · Ansible · Docker | Planned |
| Observability Board | Lightweight self-hosted status page with latency tracking, alert routing, and incident timelines. | Go · Prometheus · Grafana | Planned |

---

## Geospatial & Earth Intelligence

A background in GIS and remote sensing that most engineers in this space don't have.

| Project | Description | Stack | Status |
|:--------|:------------|:------|:-------|
| [Groundwater GRACE/GLDAS Analysis](https://github.com/philaturo/INTEGRATED-ASSESSMENT-OF-GROUNDWATER-RESOURCES-AND-DEPLETION-TRENDS-IN-KENYA-USING-GRACE-AND-GLDAS) | Undergraduate thesis: groundwater depletion trends in Kenya using GRACE satellite gravimetry and GLDAS land surface models. ML-powered hotspot classification. | R · Python · TensorFlow · QGIS | Published |
| [Potato Pathogen Detector](https://github.com/philaturo/Potato_Pathogen) | Client project: 16S and ITS amplicon sequencing for pathogen detection and diversity analysis across 14 sub-regions in Eritrea. Geospatial hotspot mapping of infection clusters. | Python · Jupyter · R | Delivered |
| Geospatial DevOps Toolkit | CLI tools for automating geospatial data pipelines: raster processing, tile generation, spatial query runners — designed for CI/CD integration. | Go · GDAL · PostGIS | Planned |

---

## AI & Automation

| Project | Description | Stack | Status |
|:--------|:------------|:------|:-------|
| [DR777 Assistant](https://github.com/philaturo/DR777assistant) | Personal coding assistant experiment. Local LLM integration research and prompt engineering. Inspired by Claude. | Python · Local LLM | Exploring |
| Mtaani AI Core | RAG-powered travel and safety recommendations embedded in Mtaani. Groq API with Llama 3, HuggingFace embeddings, Pinecone vector store. | Elixir · Groq · Pinecone · HuggingFace | In Progress |
| Agentic DevOps Bot | AI agent that monitors CI/CD pipelines, triages failures, and suggests or auto-applies fixes. Integrates with Slack/Discord for alerts. | Python · LLM APIs · GitHub API | Planned |
| IaC Generator | Describe your infrastructure in plain English; get production-ready Terraform or Docker Compose output. | Go · LLM APIs | Planned |

---

## Blockchain & Web3

Approached from a security-first angle — auditing, DeFi safety, and infrastructure over speculation.

| Project | Description | Stack | Status |
|:--------|:------------|:------|:-------|
| [Openway](https://github.com/philaturo/openway) | Non-custodial B2B cross-border settlement protocol for African mobile money networks. Smart contract escrows, EIP-712 signing, Telco webhook ingestion (M-Pesa/MTN), Kubernetes hardening with Vault secrets injection, and a full DevSecOps CI/CD pipeline — SAST, container scanning, Cosign artifact signing. | Go · Solidity · Foundry · Next.js · PostgreSQL · Redis · Kubernetes · Vault · Prometheus | In Production |
| Smart Contract Auditor | Static analysis tool for Solidity contracts: reentrancy detection, access control checks, common vulnerability patterns. | Go · Solidity · Slither | Planned |
| On-chain Payment Rail | Stablecoin payment integration for PESALOCAL — programmable, low-fee transactions for the Kenyan informal economy. | TypeScript · Solidity · EVM | Researching |
| Decentralized Identity Module | DID-based auth for ZoneBridge — self-sovereign identity for peer verification without a central authority. | Go · W3C DID · IPFS | Planned |

---

## Open Source

| Project | Description | Role | Status |
|:--------|:------------|:-----|:-------|
| [Zoea Open Source](https://github.com/philaturo/zoea-opensource) | A guide to learning open source contribution professionally — co-maintained with the original author. | Contributor | Active |
| [Elixir Learning Journey](https://github.com/philaturo/Elixir-projects) | Documented Elixir progression: Phoenix LiveView, OTP, GenServers, concurrency patterns. | Author | Ongoing |
| Quorix | Open source PaaS platform — all development public from day one. | Author | In Design |

---

## SaaS & Commercial

| Project | Description | Stack | Status |
|:--------|:------------|:------|:-------|
| Logistics SaaS *(Codename TBD)* | Transport logistics management platform for a Kenyan operator. Route optimization, fleet tracking, delivery coordination. | TBD | Scoping |
| [PESALOCAL](https://github.com/philaturo/PESALOCAL) | Financial management and payments for informal Kenyan businesses. Potential fintech SaaS evolution. | TypeScript | Early Stage |
| [Mtaani](https://github.com/philaturo/Mtaani) | AI tourism platform with B2B potential for tour operators, local government, and travel agencies. | Elixir · PostGIS · AI | In Progress |

---

## Bioinformatics & Research

| Project | Description | Stack | Status |
|:--------|:------------|:------|:-------|
| [Potato Pathogen Mapping](https://github.com/philaturo/Potato_Pathogen) | Amplicon sequencing analysis (16S + ITS) for pathogen detection and regional hotspot mapping across 14 Eritrean sub-regions. Client-delivered research. | Python · Jupyter · R | Delivered |
| [Kenya Groundwater Study](https://github.com/philaturo/INTEGRATED-ASSESSMENT-OF-GROUNDWATER-RESOURCES-AND-DEPLETION-TRENDS-IN-KENYA-USING-GRACE-AND-GLDAS) | Satellite-based groundwater depletion assessment using GRACE + GLDAS. TensorFlow ML pipeline for trend classification. | R · Python · TensorFlow | Published |

---

## Tech Stack

**Languages** — Go · TypeScript · JavaScript · Python · Elixir · R · SQL · Shell

**Frontend** — React · Vite · Next.js · Phoenix LiveView · Tailwind CSS · MapLibre GL

**Backend & APIs** — Gin · Phoenix · REST · WebSocket · JWT · OAuth 2.0

**Data & Databases** — PostgreSQL · PostGIS · Supabase · Redis · Pinecone · SQLite

**Infrastructure** — Docker · Linux · Git · GitHub Actions · Nginx · Caddy

**Geospatial** — QGIS · GDAL · PostGIS · OpenStreetMap · GRACE satellite data

**AI & ML** — Groq API · Llama 3 · HuggingFace · TensorFlow · Pinecone · RAG pipelines

**Bioinformatics** — 16S/ITS amplicon sequencing · QIIME2 · BLAST · Jupyter

**Exploring** — Kubernetes · Terraform · Ansible · Solidity · WebAssembly

---

## Connect

| | |
|:--|:--|
| **Portfolio** | *Coming soon* |
| **LinkedIn** | ** |
| **Dev.to** | ** |
| **Zone01 Kisumu** | [zone01kisumu.ke](https://zone01kisumu.ke) |

---

<div align="center">

*Currently apprentice → next stop: engineer.*

</div>
