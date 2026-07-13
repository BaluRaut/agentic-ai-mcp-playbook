# Agentic AI &amp; MCP Pro Playbook

**60 battle-tested topics** — from a single tool call to a production agent wired to MCP servers. Each with real code, a plain-English analogy, and the gotcha that bites at 2am. Grounded in the **MCP 2026-07-28 spec** (stateless core, Streamable HTTP, elicitation, OAuth 2.1).

🔗 **Live:** https://baluraut.github.io/agentic-ai-mcp-playbook/

## What's inside

**Part I — LLM Foundations (01–12):** tokens &amp; the context window, temperature &amp; sampling, messages &amp; roles, structured output, tool/function calling, streaming, embeddings, prompt engineering, few-shot, determinism, cost &amp; latency, model routing.

**Part II — The Agent Loop (13–24):** what makes an agent (autonomy levels), the agent loop, ReAct, tool use in depth, planning, reflection, memory, RAG, termination, error recovery, evaluator-optimizer, human-in-the-loop.

**Part III — MCP Deep Dive (25–46):** why MCP (M×N → M+N), host/client/server, the three server primitives (tools/resources/prompts), client capabilities (sampling/roots/elicitation), transports, the stateless core, JSON-RPC, capability negotiation, designing tools, resources, prompts, sampling, elicitation &amp; Multi-Round-Trip Requests, roots, building a server, building a client, the Inspector, OAuth 2.1, security (tool poisoning &amp; the trust model), MCP Apps &amp; Tasks, local vs remote, publishing &amp; the registry.

**Part IV — Orchestration, Evals &amp; Production (47–60):** multi-agent, routing &amp; handoffs, context engineering, guardrails, prompt injection, the lethal trifecta, evals, observability &amp; tracing, prompt caching, rate limits, cost control, testing agents, deployment — ending in a **capstone: a production agent + MCP server, end to end.**

Includes a **round-based quiz** (5 questions per round, 40 total) that **saves your progress in the browser** — come back anytime and continue.

## View locally

Open `index.html` in a browser — single self-contained file, no build step.

## Publish (GitHub Pages)

Push to a repo named `agentic-ai-mcp-playbook`, then **Settings → Pages → Source: `main` / root**.

---

Part of the [Backend Engineer's Field Library](https://baluraut.github.io/field-library/).
