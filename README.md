# Shivam Namdeo 🚀
Senior AI Engineer — Building "Kavach" — an AI Agent Ecosystem

[![Profile views](https://komarev.com/ghpvc/?username=shivamnamdeo0101&color=0e75b6)](https://github.com/shivamnamdeo0101)
[![GitHub followers](https://img.shields.io/github/followers/shivamnamdeo0101?label=Follow&style=social)](https://github.com/shivamnamdeo0101)
[![Kavach MCP Middleware](https://img.shields.io/badge/Project-kavach--mcp--middleware-blue?logo=github)](https://github.com/shivamnamdeo0101/kavach-mcp-middleware)

Hi — I'm Shivam. I design and build agent-first AI systems and the infra that lets them operate safely, reliably, and at scale. Currently focused on Kavach — a modular AI Agent Ecosystem that brings orchestration, memory, tool-use, resilience, and governance together as composable packages.

Quick links
- 🔭 Current: Building Kavach — AI Agent Ecosystem (kavach-*)
- 📁 Featured repo: kavach-mcp-middleware — https://github.com/shivamnamdeo0101/kavach-mcp-middleware
- 💬 Ask me about agent orchestration, tool integrations, memory systems, and production ML infra.

Tech & competencies
(If you'd like, tell me which of these to keep or swap — I can add exact badges.)
- Languages & runtimes: TypeScript, Python, Go
- Infra & tooling: Docker, Kubernetes, Redis, PostgreSQL, Terraform
- AI & models: OpenAI, Claude / Anthropic, Hugging Face
- Patterns: Multi-agent orchestration, tool-use, memory-augmented retrieval, idempotency, schema-validated outputs

Badges (quick examples — I can tailor these to exact languages & services you want)
![TypeScript](https://img.shields.io/badge/TypeScript-000?logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=white)

Why Kavach — AI Agent Ecosystem
- Modular packages so each capability is testable and replaceable.
- Focus on safety, idempotency, observability, and human-in-the-loop control.
- Designed for production workloads: rate limiting, parallel execution, and cost-aware routing built-in.

Core architecture patterns (pattern → package → purpose → example)

| Pattern | Package | Purpose | Example |
|---|---|---|---|
| ReAct Loop | kavach-workflow-engine | Thought → Action → Observation → Reflection cycle | Agent researches topic, calls API, reads result, decides next step |
| Chain of Thought | kavach-agent-runtime | Break complex problem into sequential steps | "First, search for data → Then analyze → Then summarize" |
| Tool Use / Function Calling | kavach-connector-* | Agent calls external APIs/tools | create_calendar_event(), query_database() |
| Multi-Agent Orchestration | kavach-workflow-engine | Multiple agents collaborate on single task | Agent A researches, Agent B writes, Agent C reviews |
| Hierarchical Planning | kavach-workflow-engine | Break goal into subtasks with DAG | Goal: "Build a report" → [Collect data, Analyze, Format] |
| Memory-Augmented Retrieval | kavach-state-memory | Use stored context to inform decisions | Agent recalls previous customer interactions |
| Reflection & Self-Correction | kavach-agent-runtime | Agent reviews its output and fixes errors | Agent checks math, corrects if wrong, retries |
| Fallback & Resilience | kavach-resilience | Retry with different model/strategy if first fails | Claude fails → Try GPT-4; API timeout → Use cache |
| Rate Limiting & Backpressure | kavach-throttle | Control flow of requests through agent | Max 100 concurrent agents, queue excess |
| Human-in-the-Loop | kavach-hitl-manager | Pause execution for human approval | High-risk decision → Ask user → Resume |
| Event-Driven Reactivity | kavach-event-hub | Agent triggered by events (not polling) | "New Slack message" event → Trigger agent |
| Cost-Aware Routing | kavach-billing-meter | Choose cheaper model if latency allows | Fast question → GPT-3.5 ($0.001); Complex → Claude ($0.01) |
| Context Window Management | kavach-state-memory | Manage token budget; summarize old context | Truncate old messages when hitting token limit |
| Tool Availability Gating | kavach-agent-runtime | Only expose relevant tools to agent | Customer agent can't access admin tools |
| Parallel Tool Execution | kavach-worker-pool | Call multiple tools concurrently | Get weather + forecast + historical data in parallel |
| Idempotent Execution | kavach-idempotency | Same request → Same response (no duplicate LLM calls) | Slack resend of same message → Return cached result |
| Semantic Caching | kavach-state-memory | Cache responses by meaning not just text | Similar questions → Use cached answer |
| Output Validation | kavach-schema-bridge | Ensure agent output matches expected schema | Check JSON matches OpenAPI spec |
| Guardrails & Content Filtering | kavach-shield | Prevent unsafe/unethical outputs | Block hate speech, PII leakage, hallucinations |
| Streaming Responses | kavach-worker-pool | Return partial results as they're generated | Send tokens to user as LLM generates them |

Featured project
- kavach-mcp-middleware — A central middleware layer for Kavach. (https://github.com/shivamnamdeo0101/kavach-mcp-middleware)
  - Role: orchestration glue, connector routing, model selection policies, and telemetry hooks.

How to use this profile README
- Copy this file into a repo named `shivamnamdeo0101` (exactly your GitHub username) to make it your profile README.
- Tell me which exact tech badges you want (I’ll generate the shields.io links), and whether to add links to other repos or your email/socials.
- If you want, I can push this directly to your GitHub profile repo — confirm the repo name and grant permission.

Contact
- GitHub: https://github.com/shivamnamdeo0101
- If you'd like, provide an email or LinkedIn and I will add contact buttons.

---
Design notes
- Minimal, senior, and actionable: clear headline, one-line summary, featured project, and a compact architecture table.
- Emojis and badges to increase scannability; links for quick access.
- Everything is easy to update — tell me which tech badges to include and I’ll update the README and commit it.
