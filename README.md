### Hi, I'm Antonio López Muzás 👋

Software engineer since 2007, based in Spain. I build business software for regulated sectors (vehicle inspection, healthcare, agrifood) and, lately, the plumbing that lets AI agents work with that software safely. I'm also doing a PhD on federated learning over data spaces.

🇪🇸 *Ingeniero de software. Construyo software de negocio y la infraestructura para que los agentes de IA trabajen con él de forma segura.*

---

#### What I work on

- **AI that touches real data, with guardrails.** MCP servers in every app I ship, natural-language-to-SQL where the model only *writes* SQL (validated with `sqlglot`, run read-only on DuckDB/Parquet), and voice and document agents that can only act through the business rules.
- **Vehicle inspection (ITV) software.** Station management, online and phone booking (voice agents), licence-plate and document reading (CNN + OCR, multimodal LLMs), rule-based checks of vehicle modification files, integration with brake-test benches, inspection analytics.
- **Data spaces.** Ocean Protocol nodes and Compute-to-Data algorithms, a marketplace rewritten with DDD, data sharing between inspection stations and in agrifood.

#### Side projects

What I build in my spare time, on the same standards:

- **App templates.** Python and PHP templates with multi-tenant PostgreSQL (row-level security), passkeys, MCP, observability and one `make` interface (`up`, `check`, `pr`, `deploy`, `rollback`).
- **AI services.** Document RAG with file-and-page citations measured against question sets, and an AI gateway that defaults to a local model.
- **Running it myself.** A small fleet of VPS with a common provisioning, backup and recovery standard, monitored through Prometheus, Loki and Grafana, and operable by agents over MCP.

#### Research

PhD candidate working on **federated learning over sovereign data spaces** (Ocean Protocol, Gaia-X/Pontus-X, Compute-to-Data): what multi-round training really costs when each step is an isolated, paid job, and verifiable one-pass model evaluation with differential privacy and conformal prediction on European clinical data.

Before that: MSc in Human-Computer Interaction (Universitat de Lleida and DERI Galway), on interacting with the Semantic Web, and a contributor to [Rhizomer](https://github.com/rhizomik/rhizomer).
- *Interacting with Linked Data through an Automatic Information Architecture*
- *Publishing and Interacting with Linked Data*

#### Stack

**Daily:** Python (FastAPI, SQLAlchemy, pydantic) · PHP (Laravel) · TypeScript (React, Vite) · PostgreSQL + pgvector · Docker · Make · GitHub Actions

**AI / ML:** MCP · Claude, OpenAI, Gemini, Ollama · RAG (Qdrant, pgvector, hybrid search, reranking) · NL2SQL · PyTorch, TensorFlow/Keras, OpenCV · federated learning · voice agents

**Data & ops:** DuckDB · MariaDB · Qdrant · nginx · Prometheus · Loki · OpenTelemetry · restic

**Ways of working:** DDD and hexagonal architecture · ADRs · spec-driven development · Conventional Commits · `make check` green before anything ships

<p>
  <img src="https://skillicons.dev/icons?i=python,fastapi,php,laravel,ts,react,vite,postgres,docker,githubactions,nginx,pytorch,tensorflow,prometheus,grafana,linux&perline=8" alt="Technologies" />
</p>

#### Experience

| | |
|---|---|
| **2020 → now** | Software engineer at [Ibatec](https://www.ibatec.es): end-to-end products for vehicle-inspection (ITV) stations (quality, training, HR, supplier integrations) and their AI layer. |
| **2015 → 2020** | Software engineer at [Optretina](https://www.optretina.com): retinal screening platform reviewing 1,000+ patients a day, connecting them with retina specialists; worked with partners such as Zeiss, Sanitas and Clínica Baviera. |
| **2014 → 2015** | Freelance full-stack developer: cloud web solutions for small companies. |
| **2011 → 2014** | Backend developer at Ondango (Berlin): e-commerce on Facebook that grew into a fashion marketplace. |
| **2007 → 2011** | Web developer at a consultancy: PHP and Java for SMEs. |

📄 Full CV: [lopezmuzas.github.io/resume](https://lopezmuzas.github.io/resume/)

<sub>Most of my work lives in private organisation repositories. Happy to talk about it.</sub>
