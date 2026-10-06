# Joel Jo

I build AI systems that companies actually run: agents that work on real data, take actions only
with a person's approval, and are measured with evals, not demos.

At **AMII**, a dental implant company, I build and run **Noah**, the company's AI assistant and
ordering platform: the website where dental practices order, the staff tools behind it, a Windows
app for staff computers, and **Noah Studio**, a CBCT imaging product for doctors. The code is
private; the repos below rebuild the core ideas from scratch on made-up data, so you can run them.

Before that, I was a data scientist and strategic data analyst for the **LG Twins** in the KBO, the
first league to call every pitch with ABS.

| Repo | What it shows |
|---|---|
| [**kbo-abs-assist**](https://github.com/joeljo2347-bit/kbo-abs-assist) | Baseball R&D: collects ABS pitch data, calls every pitch by the KBO's zone rules, and turns it into strategy: pitch selection by count, next-pitch prediction, live pitcher tracking, an AI coach for staff |
| [**langgraph-order-agent**](https://github.com/joeljo2347-bit/langgraph-order-agent) | A LangGraph agent for order staff: tool calling, human approval before any change (`interrupt()` + checkpoints), an isolated sub-agent, answer checks, an HTTP API, scenario evals on local models |
| [**rag-evals**](https://github.com/joeljo2347-bit/rag-evals) | Retrieval-augmented answers with citations or "I don't know", and an eval harness: BM25 vs dense vs hybrid, fact accuracy, citation accuracy, refusals, blind grading |
| [**sheetsense**](https://github.com/joeljo2347-bit/sheetsense) | Plain-English questions over messy spreadsheets with exact answers: the model writes SQL, SQLite does the math; CLI, web app, Docker |
| [**noah-studio**](https://github.com/joeljo2347-bit/noah-studio) | Noah Studio, AMII's CBCT review and implant-planning product for doctors: what it does and how it's built (source private) |

**Stack:** Python, FastAPI, LangGraph, LangChain, self-hosted open-weight models, MCP, C# and ASP.NET Core, SQLite and Postgres, Docker, GitHub Actions, Linux servers.

**Languages:** English, Korean, Mandarin.
