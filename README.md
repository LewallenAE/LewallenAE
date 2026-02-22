# Anthony Lewallen

**AI Research Engineer** — Python • Systems • EvalOps/RLHF Tooling

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/anthony-lewallen)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:anthonylewallen.dev@gmail.com)

I build RLHF evaluation systems, multi-agent orchestration workflows, and production-minded tooling for LLM post-training.

---

## My Typical Weekend

**Friday:** "I should learn RLHF infrastructure"

**Sunday night:**
- ✅ 6 data quality detectors running on 160K preference pairs
- ✅ PostgreSQL pipeline storing every signal
- ✅ Trained two reward models (clean vs unfiltered data)
- ✅ Orchestrated 6 LLM agents in parallel to build an RLHF data-quality pipeline
- ✅ Started a GPT implementation from scratch

I don't do tutorials. I ship.

---

## Featured Projects

| Project | What It Does | Stack |
|---------|--------------|-------|
| [**RLHF Data Quality System**](https://github.com/LewallenAE/rlhf-eval) | Detects problematic preference pairs in RLHF training data. Found 12,693 flagged examples (7.9%) in Anthropic's HH-RLHF dataset. | PyTorch, PostgreSQL, sentence-transformers |
| [**GPT From Scratch**](https://github.com/LewallenAE/generatively_pretrained_transformer) | Transformer implementation from bigram → attention → CUDA kernels. Training on War and Peace, not TinyShakespeare. | PyTorch, CUDA |
| [**Multi-Agent Orchestration**](https://github.com/LewallenAE/agentic_swarm) | **First iteration:** A multi-agent coding system using two Claude agents plus Gemini and Codex to build production code in parallel with shared contracts and coordination protocols. I designed the orchestration and approval loop. | Claude, Gemini, Codex API, Python |

---

## Open Source Contributions

| Project | Description | Link |
|---------|-------------|------|
| **NLWeb** (Microsoft Open Source) | Identified an explicitly documented CI/CD gap in NLWeb and implemented the pipeline (Ruff linting, mypy checks, pytest matrix, Docker validation, Dependabot automation). | [PR #397](https://github.com/nlweb-ai/NLWeb/pull/397) |

---

## Background

3 years as an RLHF contractor. Selected into Alignerr’s elite “Alignerrd” group of top-tier programmers after standout evaluation performance. I’ve created rubrics, graded models, and seen exactly how preference data breaks.

Now I build systems to catch those problems automatically.

---

## Tech Stack

| Category | Tools |
|----------|-------|
| **Languages** | Python, TypeScript/JavaScript, Java, SQL |
| **ML/LLM** | PyTorch, Hugging Face, sentence-transformers |
| **Backend** | FastAPI, REST APIs, PostgreSQL, SQLite |
| **Infra** | Docker, GitHub Actions, Google Colab |

---

## How I Build

- Ship first, polish later
- Interfaces + invariants before implementation
- Tests that prove behavior
- Logging/metrics as first-class citizens
- If it takes more than a weekend, break it down

---

## Open To

Research Engineer • Applied Evals • EvalOps • Data Quality Engineering • ML Systems

---

**Email:** anthonylewallen.dev@gmail.com
