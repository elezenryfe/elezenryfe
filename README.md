# Hi, I'm Farhaan

**Data Scientist** I take messy data, find the pattern in it, build a model on top, and then ship the thing so people can actually use it.

Most of my work starts with data nobody has cleaned and ends with something running in production. Some of that is classical machine learning, some of it is LLMs and retrieval, and a fair amount is just building the application around it.

Data Scientist at **BMW Financial Services**, working on complaint handling, contract analysis and the pipelines behind them.

📍 UK · ✉️ [farhaanzaki@gmail.com](mailto:farhaanzaki@gmail.com) · 💼 [LinkedIn](https://linkedin.com/in/mohammed-farhaan-a-06007a100)

---

## What I work on

**Understanding data** — exploratory analysis, cleaning and normalisation, feature engineering, and advanced SQL against warehouse-scale data. A lot of my job is turning inconsistent source data into a schema I can trust, and knowing which patterns in it are real.

**Machine learning** — classical models in scikit-learn for prediction, classification and detection, plus evaluation and validation that actually holds up. The part I care about most is getting model output into the decision pipeline rather than leaving it in a notebook.

**LLMs & RAG** — retrieval over large corpora, embeddings and vector search, re-ranking, fine-tuning, and schema-constrained extraction. Also the unglamorous half: evaluating output, and knowing when retrieval genuinely helps versus when it just adds noise.

**Building the applications** — FastAPI services, React front ends, automation workflows, browser extensions, desktop apps. A model nobody can reach isn't finished.

---

## Selected work (Personal)

**Ilmify** — RAG question answering over the full hadith corpus: 40,943 passages across nine collections, normalised from nine inconsistent source schemas into one. Multilingual embeddings, FAISS with exact cosine similarity, then re-ranked by collection authority so a more authoritative source wins a tie. Answers are grounded strictly in retrieved passages, with the source named. *Python, sentence-transformers, FAISS, FastAPI*

**Equity Valuation from LLM-Extracted Guidance** — reads SEC filings and earnings-call transcripts, extracts management's forward EPS and revenue guidance, and values the share from it. Built treating hallucination as the primary failure mode: extraction is schema-constrained, outputs are checked against quoted source spans and plausibility bands, and anything that fails is discarded rather than surfaced. *FastAPI, Celery, PostgreSQL, ChromaDB, Playwright*

**JobTailor** — parses a CV and a job description, scores the fit, and generates a tailored CV and cover letter as typeset PDFs. Also a study in cost: token usage cut by ~94% across the LLM calls by moving keyword extraction to local TF-IDF and adding caching. *FastAPI, React, Playwright, Chrome extension*

**Ryfe** — an always-on-top desktop assistant that answers questions about your local git repos and GitHub PRs. Built around one rule: nothing acts on its own. State-mutating actions render a card describing what they'd do and wait for approval, and the git layer has no free-form commands at all. *Rust, Tauri, TypeScript*

**UK FIRE Planner** — personal financial-independence planner: expense logging, savings-rate tracking, projections and UK ISA/pension rules. *TypeScript, Express, SQLite, React*

**The Obsidian Cat** — a five-act interactive mystery written in ink, with a real state machine behind the prose: a three-step clock gating locations, clue flags, per-suspect trust, and emitted tags so a host app can react without parsing the writing. *ink*

### Also built

- **Cover letter generator** — Flask + LangChain API, Chrome extension, retrieves the top-3 CV sections per job description instead of pasting the whole thing
- **Finance app** — FastAPI + React finance tracker with Google OAuth, market-hours-aware polling and a Postgres migration
- **Transcriber** — minimal Whisper wrapper with a Next.js upload UI
- **Novel reader** — Next.js chapter reader where chapters and titles derive from a contents file at build time
- **Pygame platformers** — data-driven chapters, zones, enemies and bosses defined as data, with fallback chains so a missing sprite never crashes it
- **Open source** — contributed a DeepSeek chat provider to [coucou](https://github.com/Louis-CFM/coucou), a cross-platform agent companion, wiring a provider capability model through the Rust and TypeScript layers

---

## Toolbox

| | |
|---|---|
| **Languages** | Python, SQL, JavaScript, C — working knowledge of TypeScript, Rust, and Java |
| **Data & ML** | pandas, NumPy, scikit-learn, PyTorch, Hugging Face, sentence-transformers |
| **LLM** | RAG, embeddings, FAISS, vector search, fine-tuning, prompt engineering, evaluation, hallucination mitigation |
| **Backend** | FastAPI, Flask, Node.js, Celery, Redis, PostgreSQL |
| **Cloud & ops** | AWS (Bedrock, SageMaker, Athena, S3, Lambda), Docker, Git, CI/CD, pytest, Prometheus/Grafana |
| **Frontend & apps** | React, Next.js, Tailwind, Tauri, Streamlit, Gradio, n8n |

---

## Background

- **MSc, Data Analysis for Business Intelligence** — University of Leicester
- **B.Tech, Computer Science and Engineering** — Hyderabad, India
- English · Urdu (native) · Hindi · Arabic (conversational)

I like owning a problem end to end — from the raw data, through the model, to the thing someone actually opens — and I'm good at explaining the technical part to people who don't work in it.
