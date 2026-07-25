# Hi, I am Rakesh Ganapathy

Backend Engineer focused on building production AI systems — RAG pipelines, LLM agents, hybrid search, and Kotlin-based AI orchestration — across AWS, Azure, and Android.

---

## What I Build

- **Generative AI & RAG Systems** — Hybrid search (BM25 + dense vector), cross-encoder reranking, semantic caching, multi-turn conversation, RBAC, RAGAS evaluation
- **Agentic AI** — LangGraph ReAct agents, Microsoft Fabric Agentic AI, multi-agent orchestration
- **AI Orchestration Libraries** — Provider-agnostic Kotlin runtime (KaiOrc), open-sourced and published to Maven Central
- **Backend APIs** — FastAPI, LangGraph, pgvector, JWT auth, streaming SSE, rate limiting
- **Cloud & DevOps** — AWS (ECS, ECR, Lambda, S3, CloudFormation), Azure (AI Studio, Fabric), Docker, Jenkins CI/CD

---

## Featured Projects

### KaiOrc
**Repo:** [github.com/arkhes-dev/KaiOrc](https://github.com/arkhes-dev/KaiOrc)

Kotlin library for AI workflow orchestration — published to Maven Central.

- Provider-agnostic orchestration runtime (`AIRuntime` → `Workflow` → `AIProvider`) — swap LLM providers without touching workflow logic
- Published as [`io.github.arkhes-dev:kaiorc`](https://central.sonatype.com/artifact/io.github.arkhes-dev/kaiorc) on Maven Central, Apache 2.0 licensed
- API reference auto-published via Dokka + [javadoc.io](https://javadoc.io/doc/io.github.arkhes-dev/kaiorc)
- Retry policy with backoff, response validation, and short-term conversation memory built in
- Pure Kotlin/JVM — no Android or DI-framework dependency, wires into any host app's own DI graph

### Enterprise RAG Knowledge Assistant
**Repo:** [github.com/RakeshGanapathy/enterprise-rag-assistant](https://github.com/RakeshGanapathy/enterprise-rag-assistant)

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
Languages     Python, Java, Kotlin
Frameworks    FastAPI, LangGraph, LangChain, Spring Boot
Databases     pgvector, PostgreSQL
AI / Gen AI   OpenAI, sentence-transformers, BM25, RAGAS, Langfuse
Agentic AI    LangGraph, Microsoft Fabric Agentic AI, CrewAI
Cloud AWS     ECS, ECR, Lambda, S3, CloudFormation
Cloud Azure   AI Studio, Azure Fabric, Blob Storage
DevOps        Docker, Jenkins, GitHub Actions
Publishing    Gradle, Dokka, Maven Central
```

---

## Connect

- LinkedIn: [linkedin.com/in/rakesh-ganapathy](https://linkedin.com/in/rakesh-ganapathy)

