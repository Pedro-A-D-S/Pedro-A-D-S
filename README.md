# Pedro Alves
**Senior MLOps & LLMOps Engineer**  
São Paulo, Brazil · [LinkedIn](https://www.linkedin.com/in/pedro-a-d-s/) · [GitHub](https://github.com/Pedro-A-D-S) · [Email](mailto:pedroalves0409@gmail.com)

Senior MLOps & LLMOps Engineer specializing in distributed machine learning infrastructure, multi-agent LLM systems, and enterprise AI security guardrails (Itaú Unibanco, ex-NTT DATA). Proven track record designing scalable model serving platforms, automating high-throughput parallel compute, and productionizing cognitive architectures with strict cost and latency governance.

---

### Selected Production Impact

- **Distributed Batch Acceleration (-99.4% Wall-Clock Time)**: Architected high-parallelism ML training pipelines using **AWS Step Functions Distributed Map + AWS Batch Array Jobs**, slashing batch processing duration from **250 hours to 1.5 hours** for large-scale financial and analytical workloads.
- **Inference FinOps & SLA Optimization (-23% Cloud Spend)**: Implemented Step Scaling and Target Tracking autoscaling policies across **SageMaker Realtime Endpoints** (including deep learning and Whisper ASR models) and **ECS Fargate**, maintaining strict p99 latency SLAs while cutting infrastructure costs by **23%**.
- **Mission-Critical Enterprise Serving (R$ 7M+/mo Revenue)**: Engineered containerized, high-availability MLOps serving platforms on AWS ECS Fargate and API Gateway supporting machine learning models directly driving over **R$ 7 million/month** in commercial revenue.
- **Multi-Agent LLMOps & Token Optimization (-90% Tokens)**: Designed production multi-agent systems following Clean Architecture and DDD principles. Author of the **5-Layer Agent Memory Architecture** (Working, Episodic, Semantic Knowledge Graph, Procedural Skills, and Forgetting Engine), cutting prompt token overhead by **90%** and preventing context decay across agent sessions.
- **AI AppSec & Governance**: Applied **OWASP ASVS**, **OWASP Top 10 for LLM Applications**, and **OpenSAMM** maturity frameworks for financial LLM applications, instituting PII redaction, prompt injection boundaries, and LLM-as-a-Judge automated evaluation gates.

---

### System Design & Architecture Portfolio

| System / Repository | Domain & Focus | Core Architecture & Technology Stack | Key Engineering Highlight |
| :--- | :--- | :--- | :--- |
| **[ChatResume-HR-App](https://github.com/Pedro-A-D-S/ChatResume-HR-App)** | Multi-Agent LLMOps Platform | Clean Arch/DDD, 5-Layer Memory (Mem0/SQLite), LLM-as-a-Judge, Datadog LLMOps | Eliminates unsafe pickle deserialization; integrates OWASP ASVS/LLM01 guards & prompt injection defense. |
| **[abalone-mlops-pipeline](https://github.com/Pedro-A-D-S/abalone-mlops-pipeline)** | Distributed High-Throughput Batch | AWS Step Functions Distributed Map, AWS Batch Array Jobs, EventBridge, Terraform | 250h → 1.5h batch parallelization; self-serve homologation environment for data scientists. |
| **[mlops-codebuild-pipeline](https://github.com/Pedro-A-D-S/mlops-codebuild-pipeline)** | High-Availability Model Serving | AWS ECS Fargate, ALB, Terraform Datadog Provider, GitHub Actions OIDC | Enterprise serving platform for R$ 7M/mo revenue models; automated Datadog monitors & autoscaling. |
| **[sagemaker-deploy](https://github.com/Pedro-A-D-S/sagemaker-deploy)** | Low-Latency Real-Time Inference | SageMaker Endpoints, Application AutoScaling, Canary Variants, Terraform | 23% FinOps cost reduction via Target Tracking + Step Scaling; production DL & Whisper ASR inference. |
| **[churn_prediction_system](https://github.com/Pedro-A-D-S/churn_prediction_system)** | End-to-End MLOps & Drift | SageMaker Pipelines SDK, Evidently AI, XGBoost ColumnTransformer, CloudWatch | Replaces notebooks with modular Python pipeline; automated feature/concept drift triggers. |
| **[diamonds_price_prediction](https://github.com/Pedro-A-D-S/diamonds_price_prediction)** | Production Tabular Platform | Kedro 0.19+, MLflow Model Registry, FastAPI Microservice, Great Expectations | Strict data contracts, reproducible pipeline without binary tracking, and sub-10ms REST serving. |
| **[agent-memory-playbook](https://github.com/Pedro-A-D-S/agent-memory-playbook)** | Agentic AI Memory Framework | CoALA Cognitive Architecture, SQLite Semantic Graph, YAML Skills, Forgetting Engine | Complete 5-layer agent memory implementation cutting token consumption by 90%+ in long tasks. |

---

### Core Engineering Capabilities

```
MLOps & Platforms     :: SageMaker Pipelines, MLflow, Kedro, Feature Stores, Evidently AI, Great Expectations
LLMOps & Agents       :: Multi-Agent Workflows, 5-Layer Cognitive Memory, LLM-as-a-Judge, RAG, Datadog LLMOps
Cloud & Compute (AWS) :: ECS Fargate, AWS Batch (Array Jobs), Step Functions, Lambda, API Gateway, S3, ECR
Infra as Code & CI/CD :: Terraform (Datadog & AWS providers), GitHub Actions (OIDC Auth), Docker, Helm
Software & Security   :: Python (Clean Arch / DDD / Async), REST APIs (FastAPI), OWASP ASVS, OWASP LLM Top 10
```

---

### Open Source & Community

- **Gaming Community Tooling**: In my spare time, I actively contribute to the open-source gaming and systems ecosystem—building low-latency HUD overlays, telemetry pipelines, hardware sensor integrations (NVML, Steam API), and real-time controller haptic runtimes ([SenseForge](https://github.com/Pedro-A-D-S)).
- **AI Agent Research**: Author of the [agent-memory-playbook](https://github.com/Pedro-A-D-S/agent-memory-playbook), packaging cognitive architectures and deterministic token-savings audits for modern agent runtimes.
