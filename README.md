# Mohannad Shafik

**Junior Full-Stack Developer — AI & Automation** · Turnhout, Belgium

I build end-to-end systems in Python and TypeScript: API, database, dashboard and AI integration through the Claude API. I'm looking for a first role as a junior developer where I can contribute quickly and keep growing.

[msportfolio.be](https://msportfolio.be/en/) · [LinkedIn](https://www.linkedin.com/in/mohannad-shafik/) · [mohannadshafik@msportfolio.be](mailto:mohannadshafik@msportfolio.be)

---

## Projects

| Project | What it solves | Tech | Demo |
|---|---|---|---|
| [ms-webhook-api](https://github.com/Ms-8888/ms-webhook-api) | Delivers events to customer endpoints reliably: signed requests, automatic retries, delivery tracking | FastAPI · PostgreSQL · Redis · Docker | [Live API](https://ms-webhook-api.onrender.com/health) |
| [ms-webhook-api-dotnet](https://github.com/Ms-8888/ms-webhook-api-dotnet) | The same webhook API ported to C# / ASP.NET Core 8: same routes and JSON, 70 automated tests, dashboard checked against it | ASP.NET Core 8 · EF Core · PostgreSQL · Redis · Docker | [Screenshot](https://github.com/Ms-8888/ms-webhook-api-dotnet/blob/main/docs/dashboard-events.png) |
| [ms-webhook-ui](https://github.com/Ms-8888/ms-webhook-ui) | Dashboard to see deliveries, failures and retries as they happen; works offline in mock mode | React 19 · TypeScript · TanStack Query · Tailwind | [Live demo](https://ms-8888.github.io/ms-webhook-ui/) |
| [ms-knowledge-assistant](https://github.com/Ms-8888/ms-knowledge-assistant) | Answers questions about company documents with cited sources, and says "I don't know" when the answer isn't in them | FastAPI · PostgreSQL + pgvector · local embeddings · React · Docker | [Case study](https://msportfolio.be/en/projects/knowledge-assistant/) |
| [ms-data-quality](https://github.com/Ms-8888/ms-data-quality) | Finds invalid emails, duplicate rows and company-name variants in CSV and Excel files and applies only what you approve | Python · openpyxl · optional language model | [Case study](https://msportfolio.be/en/projects/data-quality/) |
| [ms-ai-review](https://github.com/Ms-8888/ms-ai-review) | Reviews a Python file with the Claude API; findings stream in one by one, each with a suggested fix and line number | Python · Claude API · streaming · tool use · prompt caching | [Sample output](https://github.com/Ms-8888/ms-ai-review/blob/master/examples/sample_review.md) |
| [ms-agent](https://github.com/Ms-8888/ms-agent) | Agent that explores a codebase with a few tools, answers a question with file references, then reviews its own answer | Python · Claude API · ReAct loop · tool use | [Sample run](https://github.com/Ms-8888/ms-agent/blob/master/examples/sample_run.md) |

The webhook API is hosted on a free tier, so the first request after a pause can take about 30 seconds. Each project's README and case study says what was measured and what has not been tested yet.

## Private work

- **Telegram signal platform:** a prototype that distributes signals to multiple Telegram bots, with a queue, a React dashboard and a subscription model. Private, not in production, no tests.
- **AI task orchestrator:** a personal tool that plans and runs development tasks with Claude Code. Private.

## Stack

Python · TypeScript · C# / .NET 8 (one project) · FastAPI · React · PostgreSQL · Redis · Docker · Git · Claude API
