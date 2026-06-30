<h1 align="center">Sai Jawalkar</h1>
<h3 align="center">AI Engineer · Agentic AI · LangGraph · LLMs · RAG</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/sai-jawalkar-974901321/">LinkedIn</a> ·
  <a href="mailto:saijawalkar787@gmail.com">Email</a> ·
  Pune, India
</p>

---

### What I build

I build autonomous AI systems — pipelines where an LLM doesn't just answer a question, it **takes action**: cloning repos, generating code patches, running tests, and pushing PRs without a human in the loop.

---

### Shipped projects

| Project | What it does | Stack |
|---|---|---|
| [AI Issue Solver](https://github.com/SaiJ45/Ai-issue-solver) | Reads a GitHub issue → generates a code fix → opens a PR. Zero manual steps. | LangGraph · Groq · FAISS · GitHub API |
| [AI QA Agent](https://github.com/SaiJ45/Ai-QA-agent) | Reviews PRs → runs pytest → posts approve/reject on GitHub. Deterministic decision, no LLM in the verdict. | LangGraph · LLaMA 3.3 70B · Pydantic · GitHub API |
| [Multi-Agent System](https://github.com/SaiJ45/Multi-Agent-System) | Combined pipeline: Issue Solver + QA Agent running end-to-end as one orchestrated workflow. | LangGraph · Groq · FAISS |

---

### How I think about systems

- **Retrieval over memorization** — hybrid AST chunking + FAISS + keyword scoring beats pure semantic search on code
- **Deterministic decisions** — QA pass/fail uses zero LLM; rule-based logic is auditable and reproducible
- **Safety first** — file allowlists, syntax validation, scope verification, and retry caps before any code touches disk
- **ReAct before acting** — Thought → Action → Observation loop forces the model to reason before generating patches

---

### Tech I work with daily
Agentic AI   │ LangGraph · LangChain · ReAct · Multi-agent pipelines
LLMs         │ LLaMA 3 · Groq · OpenAI API · Prompt Engineering
Retrieval    │ FAISS · Sentence Transformers · RAG · AST Parsing
Infra        │ Python · FastAPI · GitHub API · pytest · Git · AWS
ML           │ Hugging Face · Scikit-learn · Pandas · NumPy

---

## Open Source Contribution

| Project | Stars | PR | What I did |
|---|---|---|---|
| [santifer/career-ops](https://github.com/santifer/career-ops) | ⭐ 55k | [#1182](https://github.com/santifer/career-ops/pull/1182) ✅ Merged | Added `--skip-pdf` flag, reducing API token cost in batch processing |
| [santifer/career-ops](https://github.com/santifer/career-ops) | ⭐ 55k | [#1211](https://github.com/santifer/career-ops/pull/1211) ✅ Merged | Added Antigravity CLI free-tier onboarding guidance + docs |

### Experience

- AI Engineer Mentee @ **Persistent Systems** (Feb 2026 – May 2026) — shipping agentic AI tools for developer workflows
- Previously @ **Rikaian Technology** — built emotion-aware multilingual translation pipeline (LangChain + Hugging Face, rated above expectations by COO)
- Open to **AI Engineer / Agentic AI / Generative AI** roles




