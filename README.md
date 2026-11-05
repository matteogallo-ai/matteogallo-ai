# Matteo Gallo

I build software end to end and measure it before I call it done.

I decide what gets built and how it is judged: the specs, the architecture and its trade-offs, the evaluation protocol, the cost caps. Coding agents write most of the code, independent agents review it, and I own the result.

**Three systems, each with its evaluation published next to the code:**

- **[Verity](https://github.com/matteogallo-ai/verity)** — a full-stack RAG application over contracts (Python API, Postgres/pgvector, Next.js interface, Docker). It cites the exact clause or refuses. Its judge agrees with my blind annotations at κ = 0.71 overall (0.48 on real claims alone, also published) and catches 16 of 20 planted false claims; warm p95 latency 8.9 s against a 15 s target.
- **[PromptLang](https://github.com/matteogallo-ai/promptlang)** — a typed language for LLM prompts, with its own lexer, parser and compiler to TypeScript and Python. Published on npm with tokenless OIDC publishing and SLSA provenance; 96 % mutation score on its core. Its AI linter measured 30 % precision in a pre-registered human review, so it ships as a reviewer's aid, not a gate.
- **[Praxis](https://github.com/matteogallo-ai/praxis)** — a multi-agent pipeline that turns a business question into a sourced briefing (Markdown, PDF, DOCX) and flags itself when the sourcing falls short. Six live briefings published, $3.29–4.75 each, failures included.

**How I work:** **[how-i-build](https://github.com/matteogallo-ai/how-i-build)** — every rule I follow, the real incident that produced it, and the link to the fix.

French and Italian (native), English · Lausanne, Switzerland · open to roles in Switzerland
matteogallo.office@gmail.com · [LinkedIn](https://www.linkedin.com/in/matteogallo-ai)
