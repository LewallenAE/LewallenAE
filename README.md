  ---
  # Anthony Lewallen

  **Full-Stack Software Engineer** — Applied ML · Security Engineering · Software Systems

  [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/anthony-lewallen)
  [![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:anthonylewallen.dev@gmail.com)

  I build things end-to-end — ML inference engines in Go, RLHF data pipelines, security tooling, game engines from scratch. I don't stop at the model.

  ---

  ## Recently

  Praetorian reached out. I found their ML Binaries challenge while going through the site and decided to beat it before applying. Took two days.

  Then I ported the entire sklearn inference pipeline to Go — no Python runtime, no ML dependencies. Weights exported to a compact binary format, loaded at startup via `go:embed`,
  running in-process on AWS EC2 with a React/TypeScript live dashboard streaming predictions in real time.

  **500 consecutive correct. 0 wrong. Solved 11 times in a row.**

  ---

  ## Featured Projects

  | Project | What It Does | Stack |
  |---------|--------------|-------|
  | [**Binary Architecture Classifier**](https://github.com/LewallenAE/go-binary-classifier) | In-process Go inference engine classifying PE binaries by CPU architecture. Beats the
  Praetorian ML challenge — 500 consecutive correct, 0 wrong, 11 solves in a row. Live on EC2. | Go, React, TypeScript, AWS |
  | [**RLHF Eval**](https://github.com/LewallenAE/rlhf-eval) | Data quality pipeline for RLHF training data. Seven detectors flagged 12,693 problematic preference pairs (7.9%) in
  Anthropic's HH-RLHF dataset. Trained competing reward models on clean vs. unfiltered data. | Python, PyTorch, FastAPI, PostgreSQL, Docker |
  | [**ScratchLM**](https://github.com/LewallenAE/ScratchLM) | GPT-2 (124M) built from scratch — custom LayerNorm, GELU, causal multi-head self-attention, transformer blocks with
  pre-norm residual connections. No high-level abstractions. | Python, PyTorch |
  | [**Crypto Microstructure Research**](https://github.com/LewallenAE/crypto_microstructure_research) | Statistical arbitrage research on crypto markets. ADF cointegration tests
  identified tradeable pairs (LINK-ADA, OP-PEPE) with 20–60 hour mean-reversion half-lives. Z-score signal generation and backtesting. | Python, pandas, statsmodels |
  | [**Crystal Hollows**](https://github.com/lewallenAE/crystal-hollows-demo) | Full 2D action-RPG demo built from scratch with zero imported assets. All rendering is programmatic via
  Godot's `_draw()` API — procedural maps, multi-phase boss AI, custom dialogue system. | Godot 4, GDScript |
  | [**Java HFT Engine**](https://github.com/LewallenAE/JavaHFT) | High-frequency trading platform — order books, matching engines, low-latency systems design. | Java |

  ---

  ## Open Source

  | Project | Description | Link |
  |---------|-------------|------|
  | **NLWeb** (Microsoft) | Identified a CI/CD gap and implemented the pipeline — Ruff linting, mypy checks, pytest matrix, Docker validation, Dependabot automation. | [PR
  #397](https://github.com/nlweb-ai/NLWeb/pull/397) |

  ---

  ## Background

  3 years as an RLHF contractor. Selected into Alignerr's elite tier after standout evaluation performance. Built rubrics, graded models, and watched exactly how preference data breaks
  — then built systems to catch those problems automatically.

  B.S. Mathematics — Operations Research, Summa Cum Laude, 2024.
  Pursuing dual master's degrees at Penn (MAS-CS AI + MSE-AI).

  ---

  ## Stack

  | | |
  |--|--|
  | **Languages** | Go, Python, TypeScript, Java, GDScript, SQL |
  | **ML** | PyTorch, scikit-learn, sentence-transformers, Hugging Face |
  | **Backend** | FastAPI, REST, PostgreSQL, SQLite |
  | **Frontend** | React, Vite, Tailwind CSS |
  | **Infra** | AWS EC2, Docker, GitHub Actions, Linux |

  ---

  I don't do tutorials. I ship.

  I use AI as a force multiplier — scaffolding, boilerplate, rubber ducking — but the architecture, the decisions, and the hard parts are mine. The goal is to become the best human
  programmer I can be.

  ---

  **Open to:** Full-Stack Engineering · ML Systems · Security Engineering · Applied Research

  **Email:** anthonylewallen.dev@gmail.com
