# Gabriel Cruz

Software / AI engineer at [Clio](https://www.clio.com), on the Learned Hand team: AI for judges and courts.
I build the parts that make LLM output trustworthy: citation verification, evals, and document pipelines.
São Paulo, Brazil.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gabrielccruz20/)
[![Email](https://img.shields.io/badge/Email-coelhoc.gabriel%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:coelhoc.gabriel@gmail.com)

## What I work on

The code is private. In short:

- **Citation integrity.** Every legal authority the model writes must resolve to its real source and render as a working link, in chat, drafted documents, and Word and PDF export.
- **LLM evals.** Harnesses that replay frozen outputs through the real production pipeline and report an unscorable trial as unresolved, never as a pass.
- **Agent reliability.** Long-running drafting agents that recover from model fallbacks, truncated tool arguments, and cancelled turns.
- **Production safety.** Fail-closed database migrations with fleet rollback, and a prompt-boundary guard against prompt injection.

**Stack:** Python · FastAPI · Temporal · PostgreSQL + pgvector · React · TypeScript · AWS · Azure OpenAI · Amazon Bedrock

## Projects

- [**BS Detector**](https://github.com/GabrielCoelhoCruz/lh-ai-fs) — a seven-stage pipeline that checks a legal brief against its cited authorities and the case record. Deterministic orchestrator, typed handoffs, LLMs judge only inside stages. 98.3% recall, 80.5% precision, 0% ungrounded evidence over 5 live runs.
- [**seshat-vault**](https://github.com/GabrielCoelhoCruz/seshat-vault) — local semantic retrieval for Markdown vaults: hybrid lexical and multilingual embedding search, served to agents over MCP, with an eval suite in CI.
- [**jev-scanr**](https://github.com/GabrielCoelhoCruz/jev-scanr) — a refactoring queue for TypeScript and JavaScript projects, ranked by a small judgment model.
- [**spotilyze**](https://github.com/GabrielCoelhoCruz/spotilyze) — self-hosted Spotify analytics: OAuth PKCE, encrypted tokens, background sync, Docker.

---

The best way to reach me is [LinkedIn](https://www.linkedin.com/in/gabrielccruz20/).
