# Usama Akram

**AI Engineer · AI Automation · Senior Full-Stack Engineer**

I build AI systems that run in production, not demos. Eight years shipping software for fintech, cybersecurity and enterprise SaaS teams.

---

## What I build

**Agentic systems**
Multi-step LLM workflows with tool calling, error recovery and state that survives long-running runs, built on LangGraph and the Claude API. The hard part is rarely the model. It is deciding what to automate, where a human stays in the loop, and how the system fails safely.

**RAG pipelines**
Document ingestion, chunking, embedding and vector retrieval on Supabase pgvector and Pinecone, served through FastAPI with streaming responses and source citation.

**Automation pipelines**
Scraping, enrichment and LLM-driven generation running end to end, with rate limiting, deduplication and retry logic across thousands of records.

**Production systems**
Python, FastAPI, Redis, PostgreSQL, Node.js, microservice architecture, plus the interface, so features ship from data model to deployed UI without a handoff.

---

## Stack

**AI** Python · FastAPI · LangGraph · LangChain · Claude API · OpenAI API · RAG · pgvector · Pinecone · Playwright

**Web** TypeScript · Next.js · React · Angular · Node.js · RxJS · Tailwind

**Data** PostgreSQL · Supabase · Redis · SQLAlchemy

**Infra** Docker · Vercel · GitHub Actions

---

## Featured projects

**[AI research agent](https://github.com/uusammmaa/ai-research-agent)**
Agentic research workflow with 18 mock evals, including citation accuracy and groundedness, OpenTelemetry tracing and cost tracked per run. 105 tests.

**[RAG API on pgvector and Pinecone](https://github.com/uusammmaa/rag-api-pgvector-pinecone)**
Retrieval API with an eval harness comparing 3 chunking strategies, reaching recall@5 0.798 and MRR 0.577 in mock mode. 116 tests.

**[AI engineer portfolio](https://github.com/uusammmaa/ai-engineer-portfolio)**
Live demos of the projects above.

---

## Selected work

Most client work sits in private repositories. A sample of what I have shipped:

- Multi-agent orchestration layer coordinating specialised LLM agents across business workflows, with shared state, tool calling against internal systems and recovery on long runs
- AI analytics engine that turns a natural language prompt plus filters into reports generated from raw product data
- Standalone AI chat microservice with Redis-backed sessions, SSE token streaming and a two-layer context system dispatching dynamic tool calls against analytics data
- RAG-backed internal assistant answering from a knowledge base, with a cited source on every answer
