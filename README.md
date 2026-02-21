<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B0D0F,100:0F7C7A&height=230&section=header&text=HAJA&fontSize=60&fontColor=F5E6C8&fontAlignY=35&desc=Cloud%20AI%20Infrastructure%20Engineer&descSize=16&descAlignY=60&animation=fadeIn&stroke=D4AF37&strokeWidth=2" alt="Header" width="100%" />

<h1>Backend-First</h1>


<p>
	<a href="https://www.linkedin.com/in/nurhajjariahk/">
		<img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-nurhajjariahk-0F7C7A?style=for-the-badge&logo=linkedin&logoColor=F5E6C8&labelColor=0B0D0F" />
	</a>
	<a href="mailto:nurhajjariahk@gmail.com">
		<img alt="Email" src="https://img.shields.io/badge/Email-nurhajjariahk%40gmail.com-7A1E2C?style=for-the-badge&logo=gmail&logoColor=F5E6C8&labelColor=0B0D0F" />
	</a>
</p>

<p>
	<img alt="Focus" src="https://img.shields.io/badge/Focus-Retrieval%20%2F%20RAG-0F7C7A?style=for-the-badge&labelColor=D4AF37" />
	<img alt="Focus" src="https://img.shields.io/badge/Focus-Evaluation%20%26%20Quality%20Gates-7A1E2C?style=for-the-badge&labelColor=D4AF37" />
	<img alt="Focus" src="https://img.shields.io/badge/Focus-Performance%20%26%20Security-0B0D0F?style=for-the-badge&labelColor=D4AF37" />
	<img alt="Focus" src="https://img.shields.io/badge/Focus-Reliable%20Cloud%20Deployments-0F7C7A?style=for-the-badge&labelColor=D4AF37" />
</p>

</div>

I build and operate AI systems that ship: retrieval pipelines, evaluation + quality gates, and production infrastructure for LLM-backed products.

## What I do

| Area | Typical work |
|---|---|
| Retrieval infrastructure | Hybrid retrieval (graph + vector + structured filters), indexing, ranking, tuning |
| Production readiness | Load tests, latency/concurrency modeling, rollout checks, operational guardrails |
| Security automation | Repeatable OWASP ZAP scans and baseline security workflows |
| Reliability | Routing, TLS hardening, incident-ready logging/metrics, active-active patterns |

## Toolbox

| Category | Stack |
|---|---|
| Languages | Python · TypeScript/JavaScript · Bash |
| AI/Retrieval | LangChain · embeddings pipelines · hybrid ranking · evaluation workflows |
| Data/Stores | Neo4j · PostgreSQL/pgVector · TiDB · MySQL |
| Infra/Delivery | Docker · Nginx · Linux |
| Testing/Quality | k6 · Locust · Playwright · OWASP ZAP |

## Public deployments

Most production code I work with is confidential (state government use cases). These deployed products are publicly accessible:

| Product | Link |
|---|---|
| Dayang chatbot (Sarawak services portal) | https://service.sarawak.gov.my/web/ |
| Court-related project (public article reference) | https://ekss-portal.kehakiman.gov.my/portals/web/home/article_view/0/5/1 |
| Malaysia public library chatbot (button-based) | https://www.u-library.gov.my/portal/web/guest |

## Selected public repos

These repos mirror the way I build systems end-to-end (pipeline → retrieval → validation), even when production code isn’t public.

| Area | Repository | What it shows |
|---|---|---|
| Local multi-agent AI app | **agentic-video-analyst** | offline inference · multi-agent orchestration · desktop app engineering |
| Graph ingestion + retrieval | **neo4j-document-pipeline** | graph modeling · retrieval API patterns for LLM workflows |
| Vector + hybrid experiments | **tidb-vector-llm-testbed** | relevance/scoring experiments · indexing tradeoffs |
| Embedding pipeline | **mysql-to-pgvector-embeddings** | extraction → embeddings → pgVector semantic layer |
| Structured retrieval | **faq-retrieval-system** | structured query layer for grounded answers |
| Performance testing | **playwright-dayang**, **k6-for-custom-dify** | UX + API load testing approaches for assistants |
| Security automation | **zap-security-api** | ZAP baseline/quick/full scan exposed via API |
| Experiments | **playwright-study**, **besu-ibft2.0** | targeted learning repos (testing + distributed systems) |

## Principles

- Measured improvements (eval + monitoring) over demo-only features
- Quality, latency, and security as release criteria
- Operable systems: clear failure modes, logs/metrics, and runbook-friendly workflows

