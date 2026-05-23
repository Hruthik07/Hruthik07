# Hruthik Gali Dileep

AI/ML Engineer at Scale AI | Boston, MA | M.S. Data Science & Analytics

I build production-grade AI systems — multimodal transformers, RAG pipelines, fine-tuned LLMs, and end-to-end MLOps infrastructure. My work focuses on closing the gap between research-quality models and systems that actually run in production.

---

## Experience

**AI Engineer — Scale AI** *(Jan 2025 – Present)*

- Migrated Llama-3.3-70B from TGI to vLLM on H100 clusters; applied AWQ INT4 quantization (140GB → 35GB VRAM), delivering **4.1× throughput** and **$290K/month** in infrastructure savings
- Engineered a multi-tenant LLMOps telemetry stack on AWS EKS with deterministic cost-per-token attribution; reduced GPU waste by **36%** across thousands of instances
- Scaled a Hybrid RAG system on Vespa across 10M+ documents (BGE-M3 + Cross-Encoder reranking); lifted Faithfulness from 0.74 → **0.93**, eliminating hallucinations in production
- Boosted Llama-3 reasoning accuracy by **22%** via QLoRA fine-tuning with RLVR; deployed on SageMaker with W&B drift monitoring
- Architected OpenTelemetry-based telemetry for SGP, correlating reasoning traces with NVIDIA DCGM signals to surface silent reasoning loops

**Machine Learning Engineer — Paytm** *(Jan 2021 – Aug 2023)*

- Built a real-time UPI fraud detection engine (XGBoost) handling **2,000+ TPS** with end-to-end scoring latency under **300ms**; served 30M+ users
- Developed credit risk models for BNPL (LightGBM); increased loan approval rates by **15%** while keeping NPA below 5%
- Fine-tuned BERT for intent classification across 50+ support categories; automated **25%** of routine wallet queries
- Reduced model iteration cycles by **40%** by engineering end-to-end ML pipelines with Apache Airflow and MLflow

---

## Tech Stack

**Core** — Python · FastAPI · PyTorch · HuggingFace Transformers

**LLMs & Inference** — vLLM · TensorRT-LLM · AWQ INT4 · EAGLE-3 Speculative Decoding · LoRA/QLoRA · Unsloth · DeepSpeed

**RAG & Retrieval** — LangChain · LlamaIndex · LangGraph · Vespa · ChromaDB · FAISS · Milvus · BGE-M3 · Cohere Reranking

**MLOps & Cloud** — AWS (SageMaker · EKS · Bedrock · Lambda) · MLflow · DVC · Docker · Kubernetes · Terraform · GitHub Actions

**Observability** — OpenTelemetry · NVIDIA DCGM · Langfuse · Prometheus · Grafana · Datadog · W&B

**ML** — XGBoost · LightGBM · BERT · SHAP · SMOTE · Anomaly Detection

---

## Selected Projects

**[Bujji-Coder-AI](https://github.com/Hruthik07/Bujji-Coder-AI)**
Multi-agent AI coding assistant with AST-aware codebase understanding, persistent cross-session memory (SQLite + ChromaDB), and intelligent routing across DeepSeek, Claude, and GPT.

**[llmforge-multimodal-transformer](https://github.com/Hruthik07/llmforge-multimodal-transformer)**
End-to-end platform for training and serving multimodal transformers. Custom Triton GPU kernels for RMSNorm deliver 1.5-2x speedup. Full serving infra: batching, Prometheus, Docker.

**[arxiv-paper-summarizer](https://github.com/Hruthik07/arxiv-paper-summarizer)**
LoRA fine-tune of Flan-T5-base on 31K arXiv papers deployed as a SageMaker endpoint. 3.4x ROUGE-1 improvement over the base model.

**[SmartHire_AI](https://github.com/Hruthik07/SmartHire_AI)**
Resume analysis and job matching using LangChain + FAISS with a full MLOps pipeline: DVC, MLflow, GitHub Actions CI/CD.

**[hospital-readmission-mlops](https://github.com/Hruthik07/hospital-readmission-mlops)**
Production-ready 30-day readmission risk classifier (XGBoost) with FastAPI serving, MLflow tracking, and CI/CD.

---

## Education

M.S. Data Science & Analytics — New England College, Henniker, NH

---

## Contact

hruthikgd07@gmail.com · [LinkedIn](https://linkedin.com/in/hruthik07) · Open to senior AI/ML engineering roles
