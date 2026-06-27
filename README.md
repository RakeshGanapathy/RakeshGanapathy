# Hi, I am Rakesh Ganapathy

Backend Engineer focused on building production AI systems — RAG pipelines, LLM agents, and hybrid search on AWS and Azure.

---

## What I Build

- **Generative AI & RAG Systems** — Hybrid search (BM25 + dense vector), cross-encoder reranking, semantic caching, multi-turn conversation, RBAC, RAGAS evaluation
- **Agentic AI** — LangGraph ReAct agents, Microsoft Fabric Agentic AI, multi-agent orchestration
- **Backend APIs** — FastAPI, LangGraph, pgvector, JWT auth, streaming SSE, rate limiting
- **Cloud & DevOps** — AWS (ECS, ECR, Lambda, S3, CloudFormation), Azure (AI Studio, Fabric), Docker, Jenkins CI/CD

---

## Featured Project

### [Enterprise RAG Knowledge Assistant](https://github.com/RakeshGanapathy/enterprise-rag-assistant)
Production-grade RAG system built with FastAPI + LangGraph + pgvector.

- Hybrid BM25 + dense vector search in parallel, merged with Reciprocal Rank Fusion
- Cross-encoder reranker (local sentence-transformers or Cohere)
- Deterministic query router — no LLM call for routing
- JWT-enforced RBAC filtering inside pgvector before the HNSW scan
- Semantic answer cache keyed on retrieved chunk IDs — shared across roles
- Multi-turn conversation with 6-turn context window
- S3 + Lambda event-driven ingestion with two-tier change detection (mtime + SHA-256)
- PDF and Word (.docx) table extraction as structured markdown chunks
- RAGAS evaluation framework on golden question set

---

## Stack

```
Languages     Python, Java
Frameworks    FastAPI, LangGraph, LangChain, Spring Boot
Databases     pgvector, PostgreSQL
AI / Gen AI   OpenAI, sentence-transformers, BM25, RAGAS, Langfuse
Agentic AI    LangGraph, Microsoft Fabric Agentic AI, CrewAI
Cloud AWS     ECS, ECR, Lambda, S3, CloudFormation
Cloud Azure   AI Studio, Azure Fabric, Blob Storage
DevOps        Docker, Jenkins, GitHub Actions
```

---

## GitHub Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=RakeshGanapathy&show_icons=true&theme=dark&hide_border=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=RakeshGanapathy&layout=compact&theme=dark&hide_border=true)

---

## Connect

- LinkedIn: [linkedin.com/in/rakesh-ganapathy](https://linkedin.com/in/rakesh-ganapathy)

