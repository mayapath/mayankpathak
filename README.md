<div align="center">

# MAYANK PATHAK

### Agentic AI · Forward Deployed Engineering · Enterprise AI Systems

**I build AI systems that route, retrieve, reason, call tools, and operate across governed enterprise data.**

[Portfolio](https://mayapath.github.io/mayankpathak/) · [LinkedIn](https://www.linkedin.com/in/mayankp07)

</div>

---

## My Enterprise Agent Mesh

I build **agentic AI as a system**, not as a single assistant.

The pattern is a hub-and-spoke architecture: one orchestration layer routes work to a fleet of specialist agents, each equipped with focused tools, enterprise data access, and narrowly scoped permissions.

```text
                          USER / TEAM EXPERIENCE
                                   │
                                   ▼
                     ┌──────────────────────────┐
                     │ ORCHESTRATION + ROUTING  │
                     │ intent · policy · tasks  │
                     └─────────────┬────────────┘
                                   │
      ┌────────────┬───────────────┼───────────────┬────────────┐
      ▼            ▼               ▼               ▼            ▼
 Document AI   Vision AI     Knowledge AI    Learning AI    Domain AI
      │            │               │               │            │
      └────────────┴───────────────┼───────────────┴────────────┘
                                   ▼
                         MCP / TOOL FABRIC
                    Python · APIs · Cloud Functions
                                   │
                                   ▼
                       ENTERPRISE DATA + SYSTEMS
                                   │
                                   ▼
             Identity · Safety · RBAC · OAuth · Telemetry
```

### Specialist fleet

- **Document Intelligence** — grounded retrieval, structured document workflows, controlled generation
- **Vision Intelligence** — multimodal reasoning with screening and safety gates
- **Enterprise Knowledge** — read-focused search across knowledge and work-management platforms
- **Learning Intelligence** — user-scoped experiences with delegated identity
- **Domain Intelligence** — specialist logic backed by governed scenario stores and deterministic tools
- **Workflow Intelligence** — async, queue-backed generation, validation, and automation pipelines

---

## Selected Work

These are **sanitized architecture/use-case summaries**. They describe engineering patterns I have implemented without publishing employer source code, internal system names, customer data, endpoints, credentials, or proprietary configurations.

- **Enterprise Document Intelligence** — broad read-focused MCP tool surface for search, retrieval and discovery, with a narrowly controlled generation path and incremental content indexing.
- **Multimodal Vision Intelligence** — read-only image reasoning with screening before response and no image persistence in the tool layer.
- **Enterprise Knowledge Retrieval** — constrained search/retrieval across knowledge and work-management systems, intentionally avoiding unnecessary mutation privileges.
- **Identity-Aware Learning Intelligence** — delegated OAuth so results follow the real signed-in user's permissions instead of a shared service identity.
- **Domain Scenario Intelligence** — structured, read-only scenario retrieval backed by Cosmos DB and RBAC rather than free-form model memory.
- **Asynchronous AI Workflow Pipeline** — queue-backed, multi-stage extraction, validation and synthesis for work that does not fit a synchronous tool call.
- **Standalone AI Training Assistant** — React + Python API application integrating repository tooling, managed secrets and generative AI outside the MCP mesh.

**[Explore the architecture and case studies →](https://mayapath.github.io/mayankpathak/#work)**

---

## Engineering Patterns

| Pattern | How I use it |
|---|---|
| **Hub-and-spoke agents** | Central orchestration with focused specialist agents |
| **Model Context Protocol** | Reusable tool contracts instead of one-off integrations |
| **Serverless AI tools** | Python services deployed as independently scalable cloud functions |
| **Managed Identity / OAuth** | Prefer identity-based or delegated access over embedded secrets |
| **Grounding-first execution** | Retrieve and validate before composing domain-specific answers |
| **Safety boundaries** | Screening, controlled writes, least privilege, and explicit policy boundaries |
| **Async execution** | Queue-backed workflows for longer-running AI jobs |
| **Observability** | Prompt, tool, failure, and usage telemetry with OpenTelemetry |

---

## AI Engineering Stack

**Claude Code** is a major part of my day-to-day engineering workflow for implementation, refactoring, debugging, repo-level reasoning, and accelerating delivery.

`Claude Code` · `Python` · `Model Context Protocol (MCP)` · `Microsoft Copilot Studio` · `Azure Functions` · `Azure OpenAI` · `Cosmos DB` · `Azure Blob Storage` · `Managed Identity` · `OAuth` · `REST APIs` · `React` · `JavaScript` · `GitLab CI/CD` · `Docker` · `Kubernetes` · `OpenTelemetry` · `Application Insights` · `RAG` · `Vector Search`

---

## R&D — Memory for Multi-Agent Systems

> **Architecture in progress — not live**

I am exploring a separate memory plane that deliberately separates three capabilities:

1. **Shared corrections** — curated, verified facts that specialists can check before composing similar answers again.
2. **User context** — scoped preferences and recurring context only where governance, privacy, and retention policies permit it.
3. **Usage intelligence** — aggregate signals across tool calls, topics, fallbacks, failures, and outcomes.

The goal is not to bolt “memory” onto an assistant. It is to design a governed memory layer that improves reliability without blurring identity, privacy, or system boundaries.

---

## Current Focus

- Enterprise multi-agent orchestration
- MCP tool design and reusable connectors
- Forward-deployed AI engineering
- Grounding reliability and anti-hallucination patterns
- Secure identity propagation across agent tools
- AI observability and evaluation
- Agent memory architecture
- Converting complex business workflows into working AI systems

---

<div align="center">

### Build AI that knows when to reason, when to retrieve, when to use a tool — and when not to guess.

</div>
