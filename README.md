# Clifford Imaguezegie

### Telecom & AI Solutions Architecture | 5G / Open RAN | Cloud-Native & Kubernetes | Agentic AI & Autonomous Networks

Telecommunications technology leader and solutions architect with **16+ years at Ericsson**, spanning RAN integration, solution architecture, 5G technology introduction, regional technical leadership and large-scale network delivery across Africa. My work combines hands-on mobile-network engineering and executive-level delivery responsibility with independent, practical development of AI/ML, knowledge-grounded LLM applications, agentic systems and cloud-native services.

I focus on **making AI useful, verifiable and operationally grounded in complex telecom systems**—from network telemetry and root-cause investigation to reliable orchestration, evaluation, governance and eventual intent-driven autonomy.

**Location:** London, United Kingdom  
**Focus:** Telecom architecture · Applied AI/ML · Agentic AI · Network automation · Cloud-native engineering

## Featured projects

### [TEAD AI — Agentic Telecom Network Investigation & RCA Platform](https://github.com/clifford-imaguezegie/telecom-ai-engineering-demo)

**The problem.** Mobile-network incidents can involve interacting symptoms across radio access, capacity, signalling and supporting infrastructure. KPI thresholds alone may not explain the root cause, while manual investigations require engineers to correlate telemetry, technical knowledge and competing fault hypotheses. TEAD AI explores how evidence-grounded AI agents can support a more structured, explainable investigation process.

**What I designed and built.** An experimental **5G RAN investigation architecture** combining ML-assisted fault localisation, 15-minute network PM telemetry and structured observations, LangGraph-orchestrated specialist analysis, knowledge-grounded reasoning and a synthesis stage for root-cause conclusions. The work includes bounded execution, evidence provenance, evaluation traces and inference/cost controls. I also developed an interactive **Streamlit investigation cockpit** with executive and full-engineering views so stakeholders can replay recorded agent decisions, inspect supporting evidence and understand conclusions and limitations.

**Measured engineering outcomes.** Evaluated **nine recorded synthetic-network investigation scenarios**, with network assessment/localisation recorded at **15.0–24.3 seconds** and full incident investigations at **2 minutes 48 seconds–4 minutes 33 seconds**. An experimental representation optimisation reduced the **SP08 evidence payload by 98.7%**; this is a payload-size result, **not** a demonstrated equivalent reduction in end-to-end latency, token cost or network MTTR. The project also records bounded retries, token budgets and traceable investigation outputs.

**Why it matters.** Demonstrates an architectural approach to **auditable, explainable and potentially faster network-assurance decision support**, connecting traditional telecom expertise with ML, agent orchestration and evidence-based RCA. It provides a research foundation for future policy-controlled closed-loop operations, rather than claiming that autonomous remediation has already been deployed.

> **Scope:** The public application replays previously completed investigations against **synthetic** network scenarios. It does not execute fresh LLM calls, poll live networks, perform live remediation or prove production network performance.

### [Telecom AI Knowledge Orchestration — RAG, MCP & Evidence-Aware Reasoning](https://github.com/clifford-imaguezegie/telecom-ai-knowledge-orchestration-demo)

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
