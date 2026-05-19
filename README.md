# Kethan Goparapu

MLOps engineer focused on applied AI systems, model reliability, evaluation, and production
deployment.

I like building the parts around models that make them useful in the real world: data
pipelines, APIs, monitoring, evals, release gates, and clear failure visibility. Right
now I am going deeper into AI/ML engineering through RAG systems, LLM evaluation, and
production-minded ML infrastructure projects.

## Current Focus

- Reliable RAG and document intelligence systems
- ML evaluation, regression checks, and model release gates
- FastAPI services for ML/AI workloads
- Dockerized local development and deployment workflows
- MLOps patterns: experiment tracking, monitoring, rollback, and reproducibility

## Selected Projects

### AI Reliability Lab

Production-style RAG reliability lab for MLOps runbooks.

- FastAPI service with ingestion, retrieval, cited answers, evals, and metrics
- Local deterministic behavior so the workflow runs without API keys
- CLI demo path for ingesting docs, querying, running evals, and reviewing metrics
- Case study and interview guide included in the repo
- Repo: https://github.com/GoparapukethaN/ai-reliability-lab

### Applied AI Eval Lab

Document intelligence and AI evaluation workspace.

- Next.js dashboard and FastAPI backend
- Document ingestion, chunking, retrieval, citations, and evaluation metrics
- Local deterministic retrieval so the demo can run without API keys
- Verified with backend tests, frontend typecheck/build, and Docker Compose config
- Live static demo: https://goparapukethan.github.io/applied-ai-eval-lab/
- Repo: https://github.com/GoparapukethaN/applied-ai-eval-lab

### MLOps End-to-End Pipeline

Customer churn prediction pipeline with model training, API serving, monitoring, and
deployment-oriented project structure.

- Data ingestion and preprocessing
- Model training and experiment tracking
- FastAPI prediction service with smoke tests
- Prometheus config, Dockerfile, Docker Compose, and Kubernetes deployment artifacts
- Repo: https://github.com/GoparapukethaN/mlops-end-to-end-pipeline

### MLGuard

Pre-deployment safety checks for ML models.

- Data drift checks
- Performance regression checks
- Latency regression checks
- CLI-style workflow for release gates with local tests and example run
- Repo: https://github.com/GoparapukethaN/mlguard

### Open Source Contribution

Focused documentation fix in Ray/RLlib.

- Clarifies `set_extra_model_outputs` behavior against the current implementation
- PR: https://github.com/ray-project/ray/pull/63524

## How I Think About AI Systems

I am interested in the space between model quality and production reliability. A model
can look good in a notebook and still fail once it meets messy data, latency constraints,
retrieval misses, unclear evals, and release pressure. My projects are aimed at closing
that gap with measurable workflows.

## Writing

- [What I Learned Building Evals Before Adding an LLM](https://github.com/GoparapukethaN/ai-reliability-lab/blob/main/docs/notes/evals-before-llms.md)

## Tech I Work With

Python, FastAPI, Docker, Kubernetes, SQL, scikit-learn, XGBoost, PyTorch basics, RAG,
retrieval evaluation, model monitoring, MLflow-style experiment tracking, GitHub, and
cloud-oriented deployment patterns.

## Contact

- Portfolio: https://goparapukethan.github.io/kethan-portfolio/
- GitHub: https://github.com/GoparapukethaN
- LinkedIn: https://www.linkedin.com/in/kethan-goparapu/
