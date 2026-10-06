# Awesome Personal Agents [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of always-on personal AI agents and the memory layers, runtimes, and messaging bridges they are built from.

A personal agent remembers you, keeps running when you are not looking, and acts for you across chat, files, and tools. This list covers self-hosted and hosted agents and the parts you need to build or run one: memory, runtimes and sandboxes, bridges to the chat apps people already use, and front ends. Entries are alphabetical within each section. Tools that only run on a Mac are marked macOS.

## Contents

- [Personal agents](#personal-agents)
- [Hosted personal agents](#hosted-personal-agents)
- [Memory layers](#memory-layers)
- [Runtimes and sandboxes](#runtimes-and-sandboxes)
- [Messaging bridges](#messaging-bridges)
- [Clients and launchers](#clients-and-launchers)
- [Tools and integrations](#tools-and-integrations)
- [Reading](#reading)
- [Related lists](#related-lists)

## Personal agents

Agents you install and run yourself, on your own machine or server.

- [Agent Zero](https://github.com/agent0ai/agent-zero) - Agent framework that gives its agent a full Dockerized Linux desktop, a browser, projects, skills, and a bridge back to your host machine. Open source (MIT).
- [Hermes Agent](https://github.com/NousResearch/hermes-agent) - Nous Research's self-improving agent that writes skills from experience, curates its own memory, and answers on Telegram, Discord, Slack, WhatsApp, Signal, or email from one gateway. Open source (MIT).
- [IronClaw](https://github.com/nearai/ironclaw) - NEAR AI's personal assistant, built as an agent operating system focused on privacy, security, and extensibility. Open source (Apache-2.0).
- [Khoj](https://github.com/khoj-ai/khoj) - Self-hostable second brain that answers from the web and your documents and lets you create agents with their own knowledge, persona, and tools. Open source (AGPL-3.0).
- [Leon](https://github.com/leon-ai/leon) - Long-running open-source personal assistant project, currently focused on a 2.0 developer preview. Open source (MIT).
- [Letta](https://github.com/letta-ai/letta-code) - Stateful agents, formerly MemGPT, that keep long-term memory and improve over time, with a terminal UI, a self-hostable app server, and chat channels. Open source (Apache-2.0).
- [LobsterAI](https://github.com/netease-youdao/LobsterAI) - NetEase Youdao's desktop agent for office work that operates on your local files and apps. Open source (MIT).
- [Moltis](https://github.com/moltis-org/moltis) - Persistent personal agent server written in Rust and shipped as one sandboxed binary. Open source (MIT).
- [nanobot](https://github.com/HKUDS/nanobot) - Lightweight Python framework for a self-hosted personal agent with web, terminal, and chat-app front ends and long-term memory. Open source (MIT).
- [NanoClaw](https://github.com/nanocoai/nanoclaw) - Small, readable alternative to OpenClaw that runs each agent in its own container. Open source (MIT).
- [NullClaw](https://github.com/nullclaw/nullclaw) - Assistant runtime compiled to a static Zig binary under 1 MB that runs on very small boards. Open source (MIT).
- [Octop](https://github.com/TencentCloud/Octop) - Tencent Cloud's self-hosted, multi-user assistant built on agents that work in parallel. Open source (MIT).
- [OpenClaw](https://github.com/openclaw/openclaw) - Self-hosted personal agent that meets you on WhatsApp, Telegram, Slack, iMessage, and 20+ other channels, with a local gateway and native apps for macOS, iOS, and Android. Open source (MIT).
- [OpenWorker](https://github.com/andrewyng/openworker) - Desktop AI coworker, in open beta, that carries everyday tasks through to finished work. Open source (MIT).
- [PicoClaw](https://github.com/sipeed/picoclaw) - Sipeed's Go assistant designed to run on $10 hardware with about 10 MB of RAM. Open source (MIT).
- [QwenPaw](https://github.com/agentscope-ai/QwenPaw) - Personal assistant from the AgentScope team with layered memory, skills, and channels including DingTalk, Lark, WeChat, Discord, Telegram, and iMessage. Open source (Apache-2.0).
- [Rakazo](https://github.com/elie222/rakazo) - Platform for persistent AI teammates on the web, desktop, and mobile, with your choice of model and computer provider. Open source (Apache-2.0).
- [Rowboat](https://github.com/rowboatlabs/rowboat) - Personal assistant that indexes your work into a knowledge graph and includes docs, a whiteboard, and email. Open source (Apache-2.0).
- [ZeroClaw](https://github.com/zeroclaw-labs/zeroclaw) - Single Rust binary that connects about 20 model providers to 30+ channels such as Discord, Telegram, Matrix, and email. Open source (Apache-2.0).

## Hosted personal agents

Always-on assistants that their makers run for you.

- [ChatGPT dots](https://learn.chatgpt.com/docs/dots) - OpenAI's always-on agent in ChatGPT that takes assigned and recurring tasks, works on a cloud computer or yours, and asks when a decision needs you. Proprietary.
- [Claude Cowork](https://claude.com/product/cowork) - Anthropic's agent for longer tasks that produces documents, decks, and spreadsheets, runs on a schedule, and can be checked from your phone. Proprietary.
- [Gemini Spark](https://gemini.google/overview/agent/spark/) - Google's 24/7 personal agent in Gemini that takes actions on your behalf under your direction. Proprietary.
- [Grok Bot](https://x.ai/news/introducing-grok-bot) - Team of always-on agents from SpaceXAI, the maker of Grok, each with its own computer, that work inside your tools and apps around the clock. Proprietary.
- [Lindy](https://www.lindy.ai) - Assistant that connects to a team's tools and company knowledge to take on routine work. Proprietary.
- [Manus](https://manus.im) - General-purpose agent that carries out tasks and automates workflows end to end. Proprietary.
- [Poke](https://poke.com) - Proactive assistant you text through Apple Messages, WhatsApp, or Telegram, connected to your accounts and services. Proprietary.

## Memory layers

Libraries and services that let an agent remember people, facts, and past work.

- [Basic Memory](https://github.com/basicmachines-co/basic-memory) - Local knowledge base that keeps what you and your assistant learn as Markdown files and serves it over MCP. Open source (AGPL-3.0).
- [Cognee](https://github.com/topoteretes/cognee) - Memory platform that turns documents, code, and conversations into persistent, graph-backed memory for agents. Open source (Apache-2.0).
- [Graphiti](https://github.com/getzep/graphiti) - Zep's framework for temporal knowledge graphs that track how facts about people and things change over time. Open source (Apache-2.0).
- [Honcho](https://github.com/plastic-labs/honcho) - Plastic Labs' memory infrastructure for agents that model how people, groups, and projects change. Open source (AGPL-3.0).
- [LangMem](https://github.com/langchain-ai/langmem) - LangChain's library for extracting facts from conversations, refining prompts, and keeping long-term agent memory. Open source (MIT).
- [Mem0](https://github.com/mem0ai/mem0) - Drop-in memory layer that stores and retrieves user and agent memories for AI applications. Open source (Apache-2.0).
- [MemOS](https://github.com/MemTensor/MemOS) - Memory operating system that gives agents persistent memory with automatic recall and background capture. Open source (Apache-2.0).
- [memU](https://github.com/NevaMind-AI/memU) - Personal memory kept as a wiki that follows you across sessions, agents, and devices. Open source (Apache-2.0).
- [Supermemory](https://github.com/supermemoryai/supermemory) - Memory and context engine with an API and a consumer app, available hosted or self-hosted. Open source (MIT).

## Runtimes and sandboxes

Places for a long-running agent to live and limits on what it can touch.

- [Cloudflare Agents](https://github.com/cloudflare/agents) - SDK for persistent, stateful agents on Durable Objects, each with its own storage, scheduling, and real-time connections. Open source (MIT).
- [NemoClaw](https://github.com/NVIDIA/NemoClaw) - NVIDIA's reference stack for running OpenClaw, Hermes Agent, and other agents in sandboxes on OpenShell. Open source (Apache-2.0).
- [Ollama](https://github.com/ollama/ollama) - Runs open-weight models locally behind a simple API, a common back end for private personal agents. Open source (MIT).
- [OpenShell](https://github.com/NVIDIA/OpenShell) - NVIDIA's isolated runtime for autonomous agents, with sandboxing primitives and an extension surface. Open source (Apache-2.0).

## Messaging bridges

Libraries and bridges that put an agent where your conversations already are.

- [Baileys](https://github.com/WhiskeySockets/Baileys) - TypeScript library that speaks the WhatsApp Web protocol over a socket to send and receive WhatsApp messages. Open source (MIT).
- [BlueBubbles Server](https://github.com/BlueBubblesApp/bluebubbles-server) - Mac server that forwards iMessages to other devices and exposes them through an API. macOS. Open source (Apache-2.0).
- [Chat SDK](https://github.com/vercel/chat) - Vercel's TypeScript SDK for writing one bot that runs on Slack, Microsoft Teams, Google Chat, Discord, Telegram, WhatsApp, and more. Open source (MIT).
- [Claude Code Channels](https://code.claude.com/docs/en/channels) - Pushes chat messages, alerts, and webhooks from an MCP server into a running Claude Code session. Proprietary.
- [grammY](https://github.com/grammyjs/grammY) - TypeScript framework for Telegram bots. Open source (MIT).
- [imsg](https://github.com/openclaw/imsg) - Command-line interface to Apple's Messages app that lets an agent send and receive iMessages. macOS. Open source (MIT).
- [mautrix-whatsapp](https://github.com/mautrix/whatsapp) - Matrix puppeting bridge for WhatsApp, part of the mautrix family of bridges for Signal, Telegram, and other networks. Open source (AGPL-3.0).
- [signal-cli](https://github.com/AsamK/signal-cli) - Unofficial command-line and JSON-RPC interface for Signal. Open source (GPL-3.0).
- [whatsapp-web.js](https://github.com/wwebjs/whatsapp-web.js) - Node.js WhatsApp client that drives WhatsApp Web in a headless browser. Open source (Apache-2.0).

## Clients and launchers

Desktop and web front ends for running or talking to agents.

- [Agentastic](https://www.agentastic.dev/agents/openclaw) - Native multi-agent IDE whose built-in agents include OpenClaw's local terminal UI and Hermes Agent, so they can run next to coding agents in isolated worktrees. macOS. Proprietary.
- [AnythingLLM](https://github.com/Mintplex-Labs/anything-llm) - Desktop and self-hosted app for chatting with your documents, running agents, and using local or hosted models. Open source (MIT).
- [ClawX](https://github.com/ValueCell-ai/ClawX) - Desktop interface for OpenClaw that turns its command-line setup into a graphical app. Open source (MIT).
- [Jan](https://github.com/janhq/jan) - Desktop assistant that runs models offline on your computer, with optional cloud models and MCP tools. Open source (Apache-2.0).
- [LibreChat](https://github.com/LibreChat-AI/LibreChat) - Self-hosted chat interface with agents, MCP, skills, and many model providers. Open source (MIT).
- [LobeHub](https://github.com/lobehub/lobehub) - Workspace that keeps a team of agents running around the clock, scheduling their work and reporting on it. Source-available (LobeHub Community License).
- [Open WebUI](https://github.com/open-webui/open-webui) - Self-hosted AI platform for local Ollama models and any OpenAI-compatible API, extensible with plugins. Source-available (Open WebUI License).

## Tools and integrations

Ways to give an agent access to the rest of your accounts and apps.

- [Composio](https://github.com/ComposioHQ/composio) - Toolkit platform that connects agents to 1,000+ apps with managed authentication and tool search. Open source (MIT).
- [MCP reference servers](https://github.com/modelcontextprotocol/servers) - Reference Model Context Protocol servers for files, Git, fetching, memory, and more. Open source (MIT and Apache-2.0).
- [Model Context Protocol](https://modelcontextprotocol.io) - Open protocol for connecting assistants to tools and data sources. Open specification.

## Reading

Background on memory, security, and how personal agents work.

- [Agent Memory: How to Build Agents That Learn and Remember](https://www.letta.com/blog/agent-memory/) - Letta's overview of in-context and external memory for agents.
- [Effective context engineering for AI agents](https://www.anthropic.com/engineering/effective-context-engineering-for-ai-agents) - Anthropic on curating what goes into an agent's context during long-running work, including notes and memory.
- [Generative Agents: Interactive Simulacra of Human Behavior](https://arxiv.org/abs/2304.03442) - Paper on agents that record, reflect on, and retrieve memories to plan their behavior.
- [MemGPT: Towards LLMs as Operating Systems](https://arxiv.org/abs/2310.08560) - The paper behind Letta, which manages an agent's memory the way an operating system pages data between tiers.
- [OpenClaw security](https://docs.openclaw.ai/gateway/security) - OpenClaw's trust model, safe defaults, and hardening guide for a personal agent with access to your accounts.
- [The lethal trifecta for AI agents](https://simonwillison.net/2025/Jun/16/the-lethal-trifecta/) - Simon Willison on why an agent with private data, untrusted input, and a way to send messages out is open to prompt-injection theft.

## Related lists

- [Awesome Agentic IDEs](https://github.com/ahmadyan/awesome-agentic-ides) - Agentic IDEs, multi-agent development environments, agent terminals, and remote-control apps.
- [Awesome Coding Agents](https://github.com/ahmadyan/awesome-coding-agents) - Command-line coding agents and harnesses, with makers, licenses, and install commands.
- [Awesome Software Factory](https://github.com/ahmadyan/awesome-software-factory) - Tools, patterns, and essays for taking work from issue to merged pull request with coding agents.

## Contributing

Contributions are welcome. Read the [contribution guidelines](CONTRIBUTING.md) first.

---

Maintained by [Adel Ahmadyan](https://github.com/ahmadyan), who builds [Agentastic.dev](https://www.agentastic.dev).
