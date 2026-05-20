# Kethan Goparapu

MLOps engineer focused on applied AI systems, model reliability, evaluation, and deployment
workflows.

I like building the parts around models that make them useful in the real world: data
pipelines, APIs, monitoring, evals, release gates, and clear failure visibility. Right
now I am going deeper into AI/ML engineering through RAG systems, LLM evaluation, and ML
infrastructure projects.

## Current Focus

- Reliable RAG and document intelligence systems
- ML evaluation, regression checks, and model release gates
- FastAPI services for ML/AI workloads
- Dockerized local development and deployment workflows
- MLOps patterns: experiment tracking, monitoring, rollback, and reproducibility

## Selected Projects

Portfolio proof ledger:
https://github.com/GoparapukethaN/kethan-portfolio/blob/main/docs/proof-ledger.md

Portfolio project map:
https://github.com/GoparapukethaN/kethan-portfolio/blob/main/docs/project-map.md

### AI Reliability Platform

Local-first RAG reliability platform for MLOps runbooks and uploaded documents.

- FastAPI backend and Next.js dashboard for ingestion, query, evals, traces, and metrics
- Provider interface with deterministic local mode plus optional OpenAI/Ollama adapters
- Document upload path for Markdown, text, and PDF inputs
- Eval reports with pass/fail, latency, source coverage, cost, citations, and refusal behavior
- Optional providers only receive citation credit for explicit evidence markers
- Secret-extraction requests refuse even when retrieved evidence contains matching terms
- Local verification covers 29 Python tests, frontend typecheck/build, CLI smoke checks, Docker Compose smoke, and rerunnable Playwright dashboard QA
- Demo walkthrough and dashboard screenshot: https://github.com/GoparapukethaN/ai-reliability-lab/blob/main/docs/demo.md#dashboard-demo
- Verification: https://github.com/GoparapukethaN/ai-reliability-lab/blob/main/docs/verification.md
- Proof artifact: https://github.com/GoparapukethaN/ai-reliability-lab/blob/main/docs/proof/verification-2026-05-20.md
- Repo: https://github.com/GoparapukethaN/ai-reliability-lab

### Applied AI Eval Lab

Document intelligence and AI evaluation workspace.

- Next.js dashboard and FastAPI backend
- Document ingestion, chunking, retrieval, citations, answer-fact coverage, and release-gate checks
- Paired JSON/Markdown report artifacts with report list/detail endpoints
- Local deterministic retrieval so the demo can run without API keys
- Verified with 21 backend tests, frontend audit/typecheck/build/static export, static demo data checks, tracked static demo browser QA, and Docker smoke
- Live static demo: https://goparapukethan.github.io/applied-ai-eval-lab/
- Demo screenshot: https://github.com/GoparapukethaN/applied-ai-eval-lab/blob/main/docs/assets/static-demo-query-eval.png
- Case study: https://github.com/GoparapukethaN/applied-ai-eval-lab/blob/main/docs/case-study.md
- Verification: https://github.com/GoparapukethaN/applied-ai-eval-lab/blob/main/docs/verification.md
- Repo: https://github.com/GoparapukethaN/applied-ai-eval-lab

### RAG Forge

Retrieval benchmark runner for comparing RAG configuration choices.

- Compares chunking, embedding, dense/BM25/hybrid retrieval, and optional reranking
- Reports hit rate, MRR, context precision, cached query latency, chunk count, and top configuration
- Generates Markdown, JSON, and Pareto plot artifacts for follow-up analysis
- Compares baseline/current benchmark reports with a regression gate for retrieval-quality changes
- Verified with 37 tests, Ruff, a keyless sample benchmark, and a repeatable sample regression gate
- Sample benchmark: https://github.com/GoparapukethaN/rag-forge/blob/main/docs/sample-benchmark.md
- Regression gate: https://github.com/GoparapukethaN/rag-forge/blob/main/docs/sample-regression-gate.md
- Case study: https://github.com/GoparapukethaN/rag-forge/blob/main/docs/case-study.md
- Verification: https://github.com/GoparapukethaN/rag-forge/blob/main/docs/verification.md
- Repo: https://github.com/GoparapukethaN/rag-forge

### StreamInfer

Local inference serving and benchmark sweeps in plain Python.

- Adaptive batching for WebSocket and HTTP prediction paths
- Backpressure controls for HTTP/WebSocket rate limits and pending-request guards
- Model hot-swap endpoint with service metrics
- JSON load-test reports for local latency and throughput checks
- Deterministic LLM-style benchmark sweeps for batch size and timeout tradeoffs
- JSON and Markdown benchmark reports, with a tracked sample sweep artifact
- Benchmark gate for throughput, p95 latency, error, and recommendation-change checks
- Verified with 40 tests, Ruff, live smoke checks, Docker smoke, sample benchmark gate, and a small load-report run
- Case study: https://github.com/GoparapukethaN/streaminfer/blob/main/docs/case-study.md
- Sample sweep: https://github.com/GoparapukethaN/streaminfer/blob/main/docs/sample-inference-sweep.md
- Sample gate: https://github.com/GoparapukethaN/streaminfer/blob/main/docs/sample-inference-gate.md
- Verification: https://github.com/GoparapukethaN/streaminfer/blob/main/docs/verification.md
- Repo: https://github.com/GoparapukethaN/streaminfer

### MLGuard

Pre-deployment release-gate checks for ML models.

- Data drift checks
- Performance regression checks
- Latency regression checks
- CLI-style release gate with Markdown and JSON deployment reports
- Composite action uploads both Markdown and JSON release-gate artifacts
- Missing baseline fails fast unless drift-only mode is explicit
- Local verification covers 26 tests, Ruff, JSON summary counts, CLI/action metadata artifact boundaries, and the sklearn example
- Case study: https://github.com/GoparapukethaN/mlguard/blob/main/docs/case-study.md
- Verification: https://github.com/GoparapukethaN/mlguard/blob/main/docs/verification.md
- Repo: https://github.com/GoparapukethaN/mlguard

### MLOps End-to-End Pipeline

Customer churn prediction pipeline with model training, API serving, monitoring, and
deployment-oriented project structure.

- Data ingestion and preprocessing
- Model training and experiment tracking
- FastAPI prediction service with request validation and unavailable-model checks
- Prometheus config, Dockerfile, Docker Compose, Kubernetes deployment artifacts, and Docker smoke verification
- Local verification covers 15 tests, strict lint/format checks, Compose config, and Docker health/prediction smoke
- Case study: https://github.com/GoparapukethaN/mlops-end-to-end-pipeline/blob/main/docs/case-study.md
- Verification: https://github.com/GoparapukethaN/mlops-end-to-end-pipeline/blob/main/docs/verification.md
- Repo: https://github.com/GoparapukethaN/mlops-end-to-end-pipeline

### Prism CLI

Experimental model-routing CLI and developer-tooling playground.

- Explores provider routing, local tool execution, cost tracking, project memory, and CLI workflows
- Local verification passes Ruff, 5,817 tests, and CLI smoke checks
- Public status doc tracks non-gating mypy, Bandit, format, and live-provider validation gaps
- Showcase status: https://github.com/GoparapukethaN/prism-cli/blob/main/SHOWCASE_STATUS.md
- Repo: https://github.com/GoparapukethaN/prism-cli

### Open Source Contributions

Open upstream PRs proposing focused fixes in AI infrastructure and evaluation tooling.

- Ray/RLlib: PR clarifies `set_extra_model_outputs` behavior against the current implementation
- Hugging Face LightEval: PR fixes an invalid `callable` type annotation in the parallelism helper
- BentoML: PR adds Python API docs for starting local HTTP/gRPC servers and creating clients
- BentoML: PR adds testing docs for mocking decorated API method bodies
- BentoML: PR adds `bentoml.Model` API reference coverage for export/import methods
- Ray PR: https://github.com/ray-project/ray/pull/63524
- LightEval PR: https://github.com/huggingface/lighteval/pull/1239
- BentoML server API PR: https://github.com/bentoml/BentoML/pull/5616
- BentoML testing PR: https://github.com/bentoml/BentoML/pull/5617
- BentoML Model API PR: https://github.com/bentoml/BentoML/pull/5618

## How I Think About AI Systems

I am interested in the space between model quality and production reliability. A model
can look good in a notebook and still fail once it meets messy data, latency constraints,
retrieval misses, unclear evals, and release pressure. My projects are aimed at closing
that gap with measurable workflows.

## Writing

- [What I Learned Building Evals Before Adding an LLM](https://github.com/GoparapukethaN/ai-reliability-lab/blob/main/docs/notes/evals-before-llms.md)
- [RAG Forge Case Study](https://github.com/GoparapukethaN/rag-forge/blob/main/docs/case-study.md)
- [StreamInfer Case Study](https://github.com/GoparapukethaN/streaminfer/blob/main/docs/case-study.md)
- [MLGuard Case Study](https://github.com/GoparapukethaN/mlguard/blob/main/docs/case-study.md)

## Tech I Work With

Python, FastAPI, Docker, Kubernetes, SQL, scikit-learn, XGBoost, PyTorch basics, RAG,
retrieval evaluation, model monitoring, MLflow-style experiment tracking, GitHub, and
cloud-oriented deployment patterns.

## Contact

- Portfolio: https://goparapukethan.github.io/kethan-portfolio/
- GitHub: https://github.com/GoparapukethaN
- LinkedIn: https://www.linkedin.com/in/kethan-goparapu/
