# Hi, I am Rakesh Ganapathy

Backend Engineer focused on building production AI systems — RAG pipelines, LLM agents, and hybrid search.

---

## What I Build

- **AI / RAG Systems** — Hybrid search (BM25 + dense vector), cross-encoder reranking, semantic caching, multi-turn conversation, RBAC, RAGAS evaluation
- **Backend APIs** — FastAPI, LangGraph, pgvector, JWT auth, streaming SSE, rate limiting
- **Cloud & DevOps** — AWS (ECS, ECR, Lambda, S3, CloudFormation), Docker, Jenkins CI/CD

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
Languages   Python, Java
Frameworks  FastAPI, LangGraph, LangChain, Spring Boot
Databases   pgvector, PostgreSQL
AI / ML     OpenAI, sentence-transformers, BM25, RAGAS, Langfuse
Cloud       AWS (ECS, ECR, Lambda, S3, CloudFormation)
DevOps      Docker, Jenkins, GitHub Actions
```

---

## Connect

- LinkedIn: [linkedin.com/in/rakesh-ganapathy](https://linkedin.com/in/rakesh-ganapathy)

