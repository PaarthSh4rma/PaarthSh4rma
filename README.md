<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/engineering-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/engineering-light.svg">
  <img src="assets/engineering-light.svg" alt="A geometric PS monogram connected to a small system of nodes." width="960">
</picture>

# Paarth Sharma

**Software engineer · Melbourne**<br>
Backend systems, full-stack products, cloud infrastructure and applied AI.

I like following a problem all the way through: the data model, the API, the interface, and what happens when a dependency fails. I’m a **Software Engineering (Honours) graduate from Monash University**, with experience at **Origin Energy** and teaching engineering at **Monash**.

My projects tend to start with something I care about—Formula 1, cricket, or making everyday tools a little more useful—and turn into questions about how systems should behave.

[Portfolio](https://paarth-sharma.com/) · [LinkedIn](https://www.linkedin.com/in/paarthsharma16/) · [Email](mailto:paarth.sharma.3110@gmail.com)

## Featured engineering projects

Six public repositories, with the design decisions visible in the code.

### 01 / RaceBrain

**Historical modelling + simulation** · Python / FastAPI / React / TypeScript

An F1 workbench that reconstructs race state at a chosen observation cutoff, then estimates representative pace and tyre-age trends. Provider data becomes a canonical domain model; missing evidence produces explicit unavailable results. A separate seeded Monte Carlo lab compares candidate strategies.

*Historical estimates are descriptive. The V2 strategy/decision engine is still planned.*

[Source](https://github.com/PaarthSh4rma/racebrain) · [Open workbench](https://racebrain-mauve.vercel.app/)

### 02 / JARVIS

**Local assistant + execution controls** · Python / FastAPI / Next.js / Ollama / SQLite

A personal developer command centre with streamed local-model responses, bounded tool execution, cancellable runs, and explicit memory controls. The backend validates tool requests and keeps execution authority separate from model output. Tests exercise cancellation races, timeouts, and project-access boundaries.

*Local development project; mission and approval records do not imply autonomous task execution.*

[Source](https://github.com/PaarthSh4rma/jarvis)

### 03 / Trackline

**Authenticated full-stack product** · React / JavaScript / Supabase / PostgreSQL

A job-search workspace for applications, follow-ups, pipeline views and analytics. One shared collection keeps the views consistent; owner-only database policies enforce access through Supabase PostgREST. Date-only handling avoids timezone drift in follow-ups.

*Formerly JobTracker. Analytics describe current status, rather than historical stage transitions.*

[Source](https://github.com/PaarthSh4rma/trackline) · [Open application](https://job-tracker-eosin-one.vercel.app/)

### 04 / ClientOps Copilot

**Document retrieval + failure recovery** · FastAPI / React / SQLite / Pinecone

A document Q&A prototype with source citations. SQLite owns text and metadata; Pinecone stores vectors. Retrieval is scoped to the selected document, insufficient evidence stops the LLM call, and failed ingestion attempts compensating cleanup across storage systems.

*Single-workspace prototype; authentication and tenant isolation are not implemented.*

[Source](https://github.com/PaarthSh4rma/clientops-copilot)

### 05 / CITYHQ Melbourne

**Data provenance + applied ML** · Next.js / FastAPI / SQLite / scikit-learn / MapLibre

A city-signal dashboard combining provider adapters, persisted observations, map views and time-series analysis. Live, stale, demo and predicted data are distinguished explicitly. The temperature experiment uses chronological evaluation against a persistence baseline.

*Local project. Published forecast results use synthetic data; the activity score is a heuristic.*

[Source](https://github.com/PaarthSh4rma/cityhq-melbourne)

### 06 / Outside Edge

**Backend workflows + persistence** · FastAPI / PostgreSQL / SQLAlchemy / React

A cricket briefing application that ingests RSS coverage, normalizes article URLs, and builds a persisted issue archive. Route, service and repository boundaries support reusable jobs. Newsletter delivery includes dry-runs, subscriber lifecycle handling and duplicate-send checks.

*No live deployment claimed. Match scores use mock data; email defaults to dry-run.*

[Source](https://github.com/PaarthSh4rma/outside-edge)

## Engineering experience

**Origin Energy · Customer Insights Intern**<br>
Python and SQL analytics, forecasting workflows, and credit-risk modelling with XGBoost and SHAP in an operational energy context.

**Monash University · Teaching Associate, Engineering Smart Systems**<br>
Teaching Python, Arduino and embedded systems through practical labs, integration debugging and explaining technical trade-offs.

## Technical toolbox

| Area | Tools demonstrated in my work |
| --- | --- |
| Languages | Python, TypeScript, JavaScript, SQL |
| Backend | FastAPI, Pydantic, SQLAlchemy, REST APIs |
| Frontend | React, Next.js, Vite, Tailwind CSS |
| Data & ML | PostgreSQL, SQLite, Pandas, NumPy, scikit-learn, XGBoost, Pinecone, Ollama |
| Cloud & infrastructure | AWS Lambda, API Gateway, S3, IAM; Supabase, Docker, Vercel, Render |
| Development & quality | Git, GitHub Actions, pytest, Vitest, Playwright, Alembic |

## Engineering philosophy

- **Put boundaries in code.** Validate inputs, enforce ownership at the data layer, and keep model output separate from permission to act.
- **Test what breaks.** Cancellation, partial writes, unavailable providers and stale data deserve explicit behaviour.
- **Make results inspectable.** Preserve provenance, state assumptions, and distinguish a useful experiment from a validated model.
- **Keep the system understandable.** Prefer clear modules and reproducible setup before adding infrastructure.

## Currently building

<!-- Update the date and these two entries together. Describe implemented work; label next steps as planned. -->
*October 2026*

- **[JARVIS](https://github.com/PaarthSh4rma/jarvis)** — developing the local command centre around bounded runs, explicit approvals and controlled memory.
- **[CITYHQ](https://github.com/PaarthSh4rma/cityhq-melbourne)** — developing city-data views, provenance-aware history and reproducible forecasting experiments.

## Additional projects

**Applied AI & research**

- [AI Meeting Copilot](https://github.com/PaarthSh4rma/ai-meeting-copilot) — audio transcription with faster-whisper, Gemini summaries and transcript Q&A; file-based prototype.
- [Quant Dev Backtester](https://github.com/PaarthSh4rma/quant-dev-backtester) — modular SMA strategies, parameter sweeps and risk metrics; in-sample research without transaction costs or slippage.

**Small tools & infrastructure experiments**

- [GhostCheck](https://github.com/PaarthSh4rma/ghostcheck) — browser-side comparison of Instagram data exports.
- [Diff2Delight](https://github.com/PaarthSh4rma/diff2delight) — Git diffs to draft release material using Streamlit and local Ollama.
- [Instagram–Matrix bridge](https://github.com/PaarthSh4rma/ig-matrix-local) — Docker Compose setup integrating Synapse and mautrix-meta; a self-hosting experiment.

**Private & unpublished work**

BirdTag is a private university team project; my public portfolio describes my Lambda, API Gateway and S3 integration work. BLACKFILE and Baat Karni Hai have private repositories. Atlas and ExoHunter are local projects. These are kept separate from the publicly inspectable work above.

## Connect

[Portfolio](https://paarth-sharma.com/) · [GitHub](https://github.com/PaarthSh4rma) · [LinkedIn](https://www.linkedin.com/in/paarthsharma16/) · [Email](mailto:paarth.sharma.3110@gmail.com)
