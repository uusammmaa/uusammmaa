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

## Currently building

**RAG evaluation harness**
Retrieval precision and recall, faithfulness scoring, and a measured comparison of chunking strategies. Knowing whether retrieval is good is the part most projects skip.

**Traced multi-agent workflow**
LangGraph with real tool calls, retry and fallback logic, tracing wired in, and token cost tracked per run.

**Production LLM service**
FastAPI with streaming, caching, rate limiting, structured output validation, containerised and deployed.

---

## Selected work

Most client work sits in private repositories. A sample of what I have shipped:

- Multi-agent orchestration layer coordinating specialised LLM agents across ERP workflows, with shared state, tool calling against internal systems and recovery on long runs
- AI analytics engine that turns a natural language prompt plus filters into engagement reports generated from raw product data, inside a social media management platform used by enterprise customers
- Standalone AI chat microservice with Redis-backed sessions, SSE token streaming and a two-layer context system dispatching dynamic tool calls against analytics data
- RAG-backed Slack assistant answering from an internal knowledge base, with a cited source on every answer
- Tender scraping to CMS publishing pipeline: Playwright scraping, LLM rewriting into Dutch vacancy posts, HTML output for review
- Lead enrichment and outreach automation processing thousands of records with per-lead LLM personalisation
