# Python + AI Portfolio

I'm Mateus Miranda, a senior Dynamics 365 / Dataverse engineer with 22 years in tech, now focused on AI for business applications. This repository is the index of my Python work: agents, retrieval-augmented generation, MCP servers and machine learning — built to solve real business problems, with the same engineering discipline I apply to enterprise systems.

## Projects

| Project | What it shows | Stack | Link |
| --- | --- | --- | --- |
| crm-rag-agent | A RAG agent that answers questions over CRM data with cited sources, an offline mode for local development, and an evaluation harness to measure answer quality. | Python, FastAPI, Azure OpenAI | [repo](https://github.com/mateusmirandaia/crm-rag-agent) |
| dataverse-mcp-server | An MCP server that gives AI agents safe, controlled access to Dataverse: read-only by default, with explicit opt-in for writes. | Python, MCP, Dataverse Web API | [repo](https://github.com/mateusmirandaia/dataverse-mcp-server) |

Both projects are under active development.

## Coming next

These are planned and not yet published:

- **Multi-agent workflows** — orchestrating specialized agents for business processes.
- **Machine learning projects** — applied ML with pandas and scikit-learn, building on my HarvardX CS109xa coursework.
- **Data automation** — Python pipelines that remove manual, repetitive data work.
- **"Python + AI" free course code** — the companion code for a free introductory course I'm preparing.

## How I build

- **Tests first-class** — unit tests for core logic and evaluation sets for anything LLM-driven.
- **CI on every push** — linting, type checks and tests run in GitHub Actions.
- **Security by default** — no secrets in code; configuration comes from environment variables, and agents get least-privilege access.
- **Reproducible** — pinned dependencies and offline or mock modes so anyone can run the project locally.
- **Documented** — every repo explains what it does, how to run it and the design trade-offs.

## More

- Profile: [github.com/mateusmirandaia](https://github.com/mateusmirandaia)
- Dynamics 365 / Dataverse + AI projects: [dataverse-ai-portfolio](https://github.com/mateusmirandaia/dataverse-ai-portfolio)
