# Hi, I'm Vedika 👋
**AI/ML & GenAI Engineer** · CSE '26 · Bengaluru, India

I build agentic and RAG systems and measure them, so quality shows up as numbers instead of demos. Previously AI/ML Intern at Mphasis. Open to GenAI / AI engineering roles.

📫 [Email](mailto:vedikagirap5@gmail.com) · [LinkedIn](https://www.linkedin.com/in/vedika-girap-896388382/)

---

## 🚧 Currently building: Grounded
**A reusable, multi-tenant hybrid RAG core with automated evaluation, built as an async API.** Apps like an HR policy bot sit on top of it, and an agent harness with MCP connects it to external tools.

| Piece | Why it matters |
|---|---|
| **Hybrid retrieval** (vector + keyword) | Goes beyond a "FAISS + LLM" demo |
| **Multi-tenancy** | Isolated data per tenant, as real SaaS requires |
| **Async ingestion** (Celery + Redis) | Heavy document work runs in the background |
| **Automated eval** (Ragas) | Retrieval and answer quality reported as metrics |
| **Reusable core** | Clean API that other apps plug into |
| **Agent harness + MCP** | Tool-use layer connecting to external apps |

**Stack:** FastAPI · Celery · Redis · PostgreSQL + pgvector · async SQLAlchemy · Alembic · Ragas · uv

**Status:** 🟡 In progress → [repo](https://github.com/vedika-girap/Grounded)

### What I'm learning from it
- **Hybrid search tuning:** how vector and keyword scores combine, and when each one wins
- **Multi-tenant isolation:** keeping tenant data separate at the database level
- **Async job pipelines:** queues, retries and idempotency for document ingestion
- **RAG evaluation:** faithfulness, context precision/recall and answer relevancy with Ragas
- **MCP and agent tool-use:** exposing the core as tools an agent can call
- **Schema migrations:** evolving a Postgres schema safely with Alembic

---

## ✅ Shipped work
| Project | What it does | Results |
|---|---|---|
| [Guarded Multi-Agent Analytics](https://github.com/vedika-girap/Guarded-Multi-Agents-Data-Analytics) | LangGraph agents route questions between SQL execution and hybrid RAG | 100% Hits@3 on a custom test set, 11 ms p50 / 28 ms p95 retrieval, 4/4 unsafe SQL queries blocked |
| [Smart Document RAG](https://github.com/vedika-girap/Smart-Document-RAG) | Grounded Q&A over documents with source tracing | FastAPI + FAISS + Groq, covered by pytest eval suites |
| [Ziya](https://github.com/vedika-girap/Indoor-Navigation-Face-Recognition-and-Object-Detection-Application-) | Voice-first indoor navigation for visually impaired users | YOLO11n + A* pathfinding in GPS-denied spaces |

## 🛠 Tech stack
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?logo=amazonwebservices&logoColor=white)

**GenAI:** LangGraph · LangChain · MCP · A2A · RAG · Ragas · pgvector · FAISS · ChromaDB
