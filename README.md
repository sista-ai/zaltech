# ⚡ Zaltech

Zaltech is a full-stack framework for building **AI-native, cross-provider applications** that run across **ChatGPT, OpenAI, Gemini, Claude, and future MCP-compatible platforms**. It standardizes how you build tools, UI, and integrations on top of the **[Model Context Protocol (MCP)](https://modelcontextprotocol.io/)** and **[ChatGPT Apps SDK](https://developers.openai.com/apps-sdk) / [Apps SDK UI](https://openai.github.io/apps-sdk-ui/)**—so you stop rewriting the same glue code for every provider and every app.

**🚀 Coming Soon (early 2026):** Zaltech framework will be publicly available in 2026.

---

## Why Zaltech Exists

Today, building real AI applications means dealing with:

* Fragmented provider SDKs
* Custom MCP servers per project
* One-off UI bridges for every platform
* No standard way to ship interactive AI apps
* Rewriting the same transport, auth, and rendering logic

Zaltech unifies all of that into **one consistent, standards-aligned developer surface**.

---

## What Zaltech Gives You

### Core Platform Capabilities

| Category                          | What You Get                                                                                                                                     |
| --------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| **MCP-First Architecture**        | Native implementation of MCP primitives: tools, resources, prompts, and structured output using [FastMCP](https://modelcontextprotocol.github.io/python-sdk/) from the [official Python SDK](https://github.com/modelcontextprotocol/python-sdk).                                         |
| **Cross-Provider Runtime**        | One app runs across hosts; **OpenAI is fully supported today**. Gemini, Claude, and others follow as their MCP support stabilizes.               |
| **Native AI UI System**           | Production-grade widgets that look native inside ChatGPT and other AI hosts. Prebuilt layouts, themes, and UI primitives with zero design setup. |
| **Interactive UI over MCP**       | Embeddable widgets rendered via MCP resources using [React](https://react.dev/), Remote DOM, and iframe strategies.                                                    |
| **Feature-Based Architecture**    | Every capability is a vertical slice (tool + logic + UI). Clean domain-driven separation, no fragile layer coupling.                             |
| **Streaming-First Transport**     | Built around Streamable HTTP and [SSE](https://developer.mozilla.org/en-US/docs/Web/API/Server-sent_events) with stateless scaling and JSON output by default.                                                          |
| **Authentication Out of the Box** | OAuth-ready, token-based auth, secure MCP auth flows, one-command setup.                                                                         |
| **Observability Built In**        | Structured logs, request tracing, progress notifications, and production-safe error visibility.                                                  |
| **MCP Inspector (First-Class)**   | Visual testing of tools, prompts, resources, logs, execution flow, and capability negotiation using [MCP Inspector](https://modelcontextprotocol.io/inspector).                                                   |
| **Local Visual UI Testing**       | [Storybook](https://storybook.js.org/)-style isolated environment for building widgets without live LLM calls.                                                                |
| **Web + Native Embedding**        | Same AI UI runs inside chat clients, dashboards, and native/hybrid apps.                                                                         |
| **One-Command DX & Deploy**       | One command to run locally. One command to deploy. No manual infra orchestration.                                                                |

---

## Provider Support

| Status       | Provider        | Notes                                        |
| ------------ | --------------- | -------------------------------------------- |
| ✅ **Active** | **OpenAI**      | Full production support today.               |
| 🟡 **Next**  | Gemini          | Planned via MCP abstraction.                 |
| 🟡 **Next**  | Claude          | Planned via MCP abstraction.                 |
| 🟡 **Next**  | Other MCP Hosts | Any MCP-speaking platform becomes pluggable. |

---

## What You Build With Zaltech

* ChatGPT Apps
* Gemini Extensions
* Claude MCP Tools
* All kinds of AI Native Apps

All from the same codebase. Build once deploy everywhere.

---

## What Makes It Different

Zaltech **targets the emerging category of AI-native applications**—apps that are triggered, controlled, and rendered directly inside LLM platforms via **[MCP](https://modelcontextprotocol.io/)** and embedded UI systems.

---

## Architecture & Feature Model

Zaltech is **feature-first across the entire stack**.
Each feature is a vertical slice with:

* **MCP layer** – tools, schemas, UI resources
* **App layer** – business logic, provider routing, AI calls
* **UI layer** – embedded widgets for AI hosts

Features are:

* Self-contained
* Reusable
* Enable/disable per deployment
* Provider-agnostic
* Domain-driven by design

---

## Vision

Zaltech’s goal is simple:

> Make building AI-native applications as standard as building web apps.

The web had [React](https://react.dev/).
AI apps will have [Zaltech](https://github.com/sista-ai/zaltech).

---

## Community

**💬 Join the Community:** [Join our Discord](https://www.sista.ai/support.html?to=discord) to stay updated and get notified when new updates are released.

---

Built by [Mahmoud Zalt](https://zalt.me/) at [Sista AI](https://www.sista.ai/about.html).
