# Clifford Imaguezegie

### Telecom & AI Solutions Architecture | 5G / Open RAN | Cloud-Native & Kubernetes | Agentic AI & Autonomous Networks

Telecommunications technology leader and solutions architect with **16+ years at Ericsson**, spanning RAN integration, solution architecture, 5G technology introduction, regional technical leadership and large-scale network delivery across Africa. My work combines hands-on mobile-network engineering and executive-level delivery responsibility with independent, practical development of AI/ML, knowledge-grounded LLM applications, agentic systems and cloud-native services.

I focus on **making AI useful, verifiable and operationally grounded in complex telecom systems**—from network telemetry and root-cause investigation to reliable orchestration, evaluation, governance and eventual intent-driven autonomy.

**Location:** London, United Kingdom  
**Focus:** Telecom architecture · Applied AI/ML · Agentic AI · Network automation · Cloud-native engineering

## Featured projects

### [TEAD AI — Agentic Telecom Network Investigation & RCA Platform](https://github.com/clifford-imaguezegie/telecom-ai-engineering-demo)

**[Explore the TEAD AI Interactive Demo](https://tead-ai.streamlit.app/)** · [View Source Repository](https://github.com/clifford-imaguezegie/telecom-ai-engineering-demo)

**Evidence-Grounded Network Investigation and RCA in Under Five Minutes**

TEAD AI is an experimental agentic AI platform designed to accelerate telecommunications network fault investigation through intelligent localisation, multi-agent engineering analysis and evidence-grounded root cause assessment.

Complex mobile-network incidents can require hours of manual investigation, with engineers correlating network performance counters, alarms, telemetry, configurations and technical documentation. Preparation and approval of formal RCA reports can take considerably longer, depending on incident complexity and operational procedures.

**TEAD AI completed eight synthetic 5G incident investigations, producing evidence-grounded RCA conclusions in 2 to 5 minutes, alongside a separate healthy-network control in under 25 seconds.**

The platform demonstrates the potential to reduce manual evidence-correlation effort, accelerate fault diagnosis, improve engineering productivity and support more consistent operational decision-making.

#### What I Designed and Built

Designed and implemented an experimental 5G RAN investigation architecture integrating:

- **ML-Assisted Fault Localisation:** Network health assessment and affected-scope identification using two ML prediction tools and 15-minute network performance and event telemetry.
- **Agentic Investigation & Orchestration:** LangGraph-based conditional routing, sequential specialist investigations across KPI, cell/peer, radio, processing, transport and configuration domains, and dedicated CU-domain investigation.
- **Evidence-Grounded RCA:** Supervisor-led correlation of specialist findings, competing explanations and domain-specific RAG knowledge support to produce traceable root cause conclusions.
- **Large-Scale Evidence Optimisation:** Deterministic evidence restructuring, compression and structured engineering representations to support LLM inference over large telecom telemetry datasets while retaining original source evidence.
- **Inference Optimisation & Evaluation:** Token-budget management, cost-aware inference controls, structured-output validation, failure-handling mechanisms and recorded agent execution traces.
- **Interactive Investigation Cockpit:** Streamlit-based Executive and Full Engineering experiences enabling inspection of recorded agent workflows, tool interactions, supporting network evidence and RCA findings.

#### Measured Engineering Achievements

| Engineering Metric | Experimental Result |
| --- | --- |
| Network assessment and fault localisation | **15.0–24.3 seconds** |
| End-to-end incident investigation and RCA | **2m 48s–4m 33s** |
| Specialist investigation | **42.1 seconds–1m 51.6s** |
| Supervisor evidence synthesis and RCA | **1m 38.8s–2m 53.4s** |
| CU-domain evidence representation optimisation | **Approximately 17.29 MB → 227 KB** |
| Evidence payload-size reduction | **Approximately 98.7%** |
| Recorded experimental scenarios | **9 total: 8 incidents + 1 healthy control** |

The evidence optimisation result comes from Module 5 architecture development experiments. It measures payload representation size, not equivalent reductions in billed tokens, inference cost or end-to-end latency.

#### Operational and Business Value

- **Accelerated fault diagnosis:** Demonstrates the feasibility of completing structured, multi-domain AI investigations in minutes rather than requiring exclusively manual evidence correlation.
- **Engineering productivity:** Automates significant portions of telemetry interpretation, specialist evidence analysis and draft RCA generation.
- **Inference efficiency:** Reduces redundant evidence representation and supports more manageable context requirements, creating opportunities for lower-cost LLM execution.
- **Explainable operational intelligence:** Preserves supporting observations, specialist outputs, uncertainty qualifications and investigation traceability for engineering review.
- **Foundation for autonomous networks:** Establishes evidence-grounded diagnosis and decision-support capabilities that can evolve toward governed closed-loop automation, verification and self-healing operations.

**Experimental scope:** Results are derived from completed synthetic 5G network investigations. The public application replays previously recorded agent executions rather than performing live network diagnosis. Production MTTR reduction, monetary savings, operator-approved RCA turnaround and autonomous remediation have not been demonstrated.

### [Telecom AI Knowledge Orchestration — RAG, MCP & Evidence-Aware Reasoning](https://github.com/clifford-imaguezegie/telecom-ai-knowledge-orchestration-demo)

**[Explore the Telecom AI Knowledge Orchestration Demo](https://telecom-ai-orchestration-693254716479.europe-west2.run.app/)** · [View Source Repository](https://github.com/clifford-imaguezegie/telecom-ai-knowledge-orchestration-demo)


**The problem.** Technical telecom questions often require standards, architecture documentation and accurate domain context. Conventional LLM responses may be unsupported, but rigid retrieval-augmented generation can also become incomplete or misleading when retrieved evidence is insufficient. This project investigates **when retrieval helps, when it degrades answers and how to make the trade-off visible**.

**What I designed and built.** A telecom knowledge-orchestration demonstration comparing **three reasoning modes**: (1) LLM-only answers, (2) strict evidence-grounded answers and (3) augmented reasoning that combines connected knowledge, controlled external evidence where appropriate and pretrained model knowledge with provenance. Its architecture uses **Gemma** for generation, **Granite** for routing/comparative evaluation, **BGE-M3 embeddings and FAISS** for semantic RAG, and **MCP-based knowledge access**. The documented vector corpus contains approximately **1.5 million telecom vectors**. The application was containerised and deployed using **Docker and Google Cloud Run**, with related Google Cloud build, registry and secret-management services.

**What was established.** The experiments illustrate that **retrieval relevance is not the same as answer sufficiency**: a grounded answer may be safer but less complete if the corpus omits needed information. Adaptive orchestration provides a way to compare answer completeness with source grounding and explicit provenance. Cloud deployment also surfaced practical constraints involving vector-index/model memory, cold starts, latency and infrastructure cost.

**Why it matters.** Offers a practical decision-support architecture for **telecom knowledge assistants and future AI-agent evidence services**: better visibility into which sources justify a response, when retrieval is insufficient and what deployment trade-offs must be managed. Its principal contribution is comparative engineering and controlled knowledge access—not a claim that RAG always improves accuracy or that the prototype is a production-validated enterprise service.

> **Scope:** Evaluation findings are specific to documented experiments and test questions; wider telecom reliability, operational SLAs and production-scale outcomes have not been independently established.

### Applied ML and deployment projects

| Project | Demonstrated capability |
| --- | --- |
| [Telecom Customer Churn](https://github.com/clifford-imaguezegie/customer-churn-prediction-telecom) | XGBoost classification and Streamlit presentation |
| [Bank Customer Churn](https://github.com/clifford-imaguezegie/customer-churn-prediction-bank) | Data preprocessing, XGBoost tuning, model serialisation and interactive inference |
| [Rental Price Prediction REST API](https://github.com/clifford-imaguezegie/rental-price-prediction-rest-api) | Flask API back end, Streamlit front end and Docker containerisation |
| [Airbnb Rental Price Prediction](https://github.com/clifford-imaguezegie/rental-price-prediction-airbnb) | Regression modelling and Streamlit app |
| [Boston Housing Price Predictor](https://github.com/clifford-imaguezegie/boston-housing-price-predictor) | Educational XGBoost regression and reproducible model deployment |

## Engineering capabilities

- **Telecom and network architecture:** 2G–5G RAN, Open RAN / Cloud RAN concepts, RAN–Transport–Core interfaces, OSS integration, network rollout, migration, technical assurance and root-cause analysis.
- **AI/ML:** Python, pandas, NumPy, scikit-learn, XGBoost, LightGBM, CatBoost, TensorFlow/Keras, model assessment and experimental reproducibility.
- **LLMs and agentic systems:** RAG, MCP, LangChain, LangGraph, evidence orchestration, structured outputs, evaluation, traceability, bounded tool use and human-review controls.
- **Cloud-native and deployment:** Kubernetes, Docker, GCP Cloud Run and Compute Engine, Streamlit, Flask, REST APIs, Git/GitHub and software validation.
- **Architecture and delivery governance:** Solution scoping, interfaces, integration strategy, technical risk, testing/acceptance, stakeholder leadership and large-scale delivery governance.

## Career highlights

- Led an Ericsson network implementation organisation of **150+ people**, with regional delivery, quality and partner governance responsibilities.
- Led teams delivering **12,500+ site integrations annually** across African markets.
- Advanced **Zero Touch Integration**, reducing radio-node commissioning time from approximately **120 to 20 minutes** in the reported deployment context.
- Expanded radio-site analytics that reduced field troubleshooting time by **more than 50%** in reported use cases.
- Established and led the **5G Africa Competence Hub**, supporting trials, technology introduction and commercial readiness.

## Education and professional credentials

- **Postgraduate Program in Artificial Intelligence & Machine Learning: Business Applications** — University of Texas at Austin, McCombs School of Business. **Coursework and practical modules completed; final evaluation and graduation pending.**
- **MBA**, University of Bradford · **MSc Telecommunications**, Birmingham City University · **B.Eng. Computer Engineering (First Class Honours)**, University of Benin.
- **CNCF Kubestronaut**, including **CKA, CKAD, CKS, KCNA and KCSA** certifications.
- **AWS Certified AI Practitioner** and **AWS Certified Cloud Practitioner**.
- **PRINCE2 7** and **PRINCE2 Agile** Practitioner/Foundation certifications.
- Ericsson certifications spanning 5G RAN solutions, RAN transport, IP/MPLS and network integration.

## Current engineering direction

My independent Telecom AI Engineering programme advances from LLM evaluation and retrieval systems through **agentic telecom investigation, predictive network intelligence and controlled autonomous-network research**. Future scope includes intent-management alignment (including **TMF921**), policy-governed closed-loop operations, digital-twin/graph integration and enterprise-level validation. **These are research and roadmap objectives, not claims of completed commercial ANO deployments.**

---

*This profile distinguishes commercial telecommunications leadership from independent AI engineering experiments. Project performance figures refer to the documented test conditions and should not be interpreted as production network performance.*
