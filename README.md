<div align="center">

# Manobhi Sriram

**Generative AI & Agentic Systems Engineer**

*Building production-grade LLM systems, autonomous AI agents, and scalable AI infrastructure — from prototype to deployment.*

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat-square&logo=vercel&logoColor=white)](https://manobhi-sriram-portfolio.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/manobhi-sriram)
[![GitHub](https://img.shields.io/badge/GitHub-171515?style=flat-square&logo=github&logoColor=white)](https://github.com/manobhisriram)

</div>

---

## 👤 About

I design and ship end-to-end AI systems that go beyond demos. My work spans **multi-agent orchestration**, **RAG pipelines at scale**, **LLM-powered microservices**, and **agentic workflows** that run reliably in production.

I operate at the intersection of applied research and engineering — translating state-of-the-art LLM capabilities into systems that are **observable**, **maintainable**, and **actually useful**.

---

## ⚙️ Core Stack

**LLM & Agent Frameworks**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LlamaIndex](https://img.shields.io/badge/LlamaIndex-8A2BE2?style=flat-square&logoColor=white)
![AutoGen](https://img.shields.io/badge/AutoGen-0078D4?style=flat-square&logoColor=white)
![CrewAI](https://img.shields.io/badge/CrewAI-FF4B4B?style=flat-square&logoColor=white)

**Models & APIs**

![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic_Claude-CC785C?style=flat-square&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Gemini-4285F4?style=flat-square&logo=google&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logoColor=white)

**Vector & Retrieval**

![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=flat-square&logoColor=white)
![Weaviate](https://img.shields.io/badge/Weaviate-FF6D00?style=flat-square&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B35?style=flat-square&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-336791?style=flat-square&logo=postgresql&logoColor=white)

**Infrastructure & Cloud**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![AWS](https://img.shields.io/badge/AWS_Bedrock-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![GCP](https://img.shields.io/badge/Vertex_AI-4285F4?style=flat-square&logo=googlecloud&logoColor=white)

**Observability & Evals**

![LangSmith](https://img.shields.io/badge/LangSmith-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![W&B](https://img.shields.io/badge/Weights_&_Biases-FFBE00?style=flat-square&logo=weightsandbiases&logoColor=black)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)

---

## 🏗️ Architecture Mindset

When building AI systems, I focus on:

- **Reliability over capability** — A system that fails gracefully is more valuable than one with impressive demos
- **Evaluation-first development** — If you can't measure it, you can't improve it; evals are built before deployment
- **Composable agent design** — Agents as modular, testable units with explicit state machines and handoff contracts
- **Latency & cost awareness** — Every LLM call has a price; caching, routing, and model selection are engineering decisions
- **Human-in-the-loop by default** — Autonomous agents need well-defined escalation boundaries

---

## 🔷 Featured Projects

### Multi-Agent Research & Synthesis Pipeline
> Autonomous research system using LangGraph that orchestrates specialized subagents for web search, document retrieval, fact-checking, and structured report generation. Includes streaming output, checkpointing, and retry logic for production resilience.

`LangGraph` · `OpenAI GPT-4o` · `Tavily` · `FastAPI` · `Redis`

---

### Enterprise RAG System with Hybrid Retrieval
> Production RAG pipeline supporting 10K+ document corpus with hybrid BM25 + dense retrieval, query decomposition, reranking, and contextual compression. Full observability via LangSmith.

`LlamaIndex` · `Pinecone` · `Cohere Rerank` · `FastAPI` · `LangSmith`

---

### Agentic Code Review Assistant
> LLM-powered agent that performs automated PR reviews — analyzes diffs, checks codebase standards, and posts structured feedback. Integrated directly into GitHub Actions CI pipeline.

`LangChain` · `Claude API` · `GitHub Actions` · `Docker`

---

### Conversational SQL Agent
> Natural language to SQL with schema-aware retrieval, query validation, sandboxed execution, and clarification loops for ambiguous multi-table queries.

`LangGraph` · `GPT-4o` · `PostgreSQL` · `FastAPI` · `Pydantic`

---

### LLM Evaluation Framework
> Custom eval harness for benchmarking RAG quality, agent tool-use accuracy, and hallucination rates. Supports automated regression testing for LLM features in CI/CD pipelines.

`Python` · `Pytest` · `LangSmith` · `Arize Phoenix` · `Pandas`

---

## 🚀 Currently Working On

- Designing **long-horizon agentic workflows** with persistent memory and planning loops using LangGraph
- Exploring **structured generation and function-calling** patterns for reliable agent tool use
- Building **eval pipelines** that catch regression before it reaches production
- Contributing to open-source tooling for **LLM observability and tracing**

---

## 📊 AI Specialization

```
Multi-Agent Systems          ████████████████████  Expert
RAG Architecture & Retrieval ████████████████████  Expert
LLM Prompt Engineering       ██████████████████░░  Advanced
LLM Evaluation & Testing     ████████████████░░░░  Advanced
AI Infrastructure & Serving  ██████████████░░░░░░  Proficient
Fine-tuning & Alignment      ████████████░░░░░░░░  Developing
```

---

## 🌐 Open Source Interests

- Agent orchestration frameworks and state management patterns
- Retrieval-augmented generation tooling and evaluation
- LLM observability, tracing, and cost optimization
- Developer tooling for AI-native applications

---

## 📈 GitHub Stats

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=manobhisriram&show_icons=true&theme=github_dark&hide_border=true&count_private=true&include_all_commits=true" />
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=manobhisriram&layout=compact&theme=github_dark&hide_border=true&langs_count=6" />

</div>

---

## 💬 What I'm Looking For

Open to conversations about:

- 🔹 **Senior / Staff AI Engineer** roles at AI-native startups and product companies
- 🔹 **Founding Engineer** opportunities where I can shape the AI stack from the ground up
- 🔹 **Remote-first** applied AI and GenAI platform engineering roles
- 🔹 **Consulting** on LLM architecture, RAG system design, and agent frameworks

---

<div align="center">

*I build AI systems that work in the real world — not just in notebooks.*

</div>
