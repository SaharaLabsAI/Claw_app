# ClawApp - OpenClaw Universal Hub Desktop

ClawApp is an open-source desktop application by Sahara AI that makes it easier to install, configure, and operate OpenClaw agents locally—without relying on scripts, complex CLI setups, or external orchestration services. 

If you like OpenClaw's execution model but want a safer, more approachable way to run agents day-to-day, ClawApp exists for you.

## What ClawApp Is (and Isn't)

**ClawApp is:**
* A local-first desktop interface for running OpenClaw agents.
* A coordination layer for agent setup, skills, permissions, and execution.
* A practical way to operate agents without writing glue code or scripts.

**ClawApp is not:**
* A fork of OpenClaw.
* A hosted agent platform.
* A replacement for OpenClaw's execution model.

ClawApp does not extend or modify OpenClaw itself. It focuses on making OpenClaw easier to run, easier to manage, and harder to misconfigure.

## Platform Support
* macOS (Apple Silicon & Intel) - **Supported**
* Windows - **Planned**

## Quick Start
1. Download the macOS installer from 👉 [https://clawapp.saharaai.com](https://clawapp.saharaai.com)
2. Launch the app and sign in using your preferred credentials (Google Login supported).
3. Start interacting with your local OpenClaw agent through the built-in chat interface.

No external services, API keys, or manual configuration required.

## What you can do with ClawApp

With ClawApp, OpenClaw agents execute locally with access to explicitly enabled system resources, application integrations, and live crypto market data (through early native integration with HeySorin.AI). Agent behavior is driven by natural-language instructions and constrained by the tools and permissions configured at runtime.

### Currently Supported Workflows

**Local Automation**
* Run OpenClaw agents against local system resources.
* Execute any OpenClaw-compatible actions.
* Manage workflows that would otherwise require scripts or CLI configuration.

**Messaging-Based Agent Interaction**
Run agents inside supported messaging platforms to post updates, respond to messages, or trigger simple workflows.
* **Currently supported:** Moltbook, Telegram.
* **Planned:** Slack, Discord, WhatsApp, Reddit.

**Crypto Market Research & Analysis**
* Pull live crypto market data via early native integration with HeySorin.AI.
* Generate structured summaries and market overviews.
* Interpret price action and on-chain signals.

### Example Prompts
* "Summarize my last five unread emails and highlight action items."
* "Create a new note called 'Today's Tasks' and list my top three priorities."
* "Post an update on Moltbook that I'm online and open to collaboration."
* "Pull recent BTC charts and summarize recent price action."

## Design Principles

* **Built-in Execution and Billing:** No third-party API keys or separate pay-as-you-go accounts are required to get started.
* **Minimal Authentication Overhead:** One-click Google login establishes user identity and session state without manual account creation.
* **Sane Defaults, Not Constraints:** Ships with optional, pre-installed integrations (Apple Notes, Moltbook, crypto market data) to exercise the execution surface without limiting extensibility.
* **Low-Friction Interaction:** Preset prompts and one-click skill invocation provide a fast path from instruction to execution.

## Usage, Credits, and Agent Execution

ClawApp includes a simple usage-based model to cover the cost of running agents (e.g., model inference and execution).
* New users receive free credits on activation.
* Usage is transparent and tied to actual agent activity.
* Top-ups are handled directly in the app.

Internally, ClawApp uses **USD1** as a settlement rail to keep accounting consistent. This is fully abstracted so users do not need to manage wallets or tokens to get started. Over time, this foundation enables more advanced workflows such as agent-to-agent payments and paying for external tools using the **x402** standard. 

## Agent Identity & Payments (Optional)

ClawApp is designed to be compatible with emerging agent-native standards:

* **Agent Identity (ERC-8004):** Each agent is associated with a persistent Agent ID. This enables stable identity, attribution, and state across runs, treating agents as long-lived actors rather than disposable processes.
* **Agent-Native Payments (x402):** Enables agents to pay for data, compute, or services programmatically. This supports agent-to-agent and agent-to-service transactions, decoupling execution logic from user-managed payment flows.

## About Sahara AI
Sahara AI is the agentic AI company, dedicated to making AI more accessible and equitable to all. Our full-stack AI platform consists of a Data Services Platform for data labeling and refinement, an AI Developer Platform and Marketplace for agent creation, deployment, and monetization, and agentic protocols for value attribution and distribution.

Our solutions already power AI agents and high-quality data for consumers, Fortune 500 enterprises, and leading research labs, such as Microsoft, Amazon, MIT, Motherson, and Snap. For more information, visit [SaharaAI.com](https://SaharaAI.com).

## Links and Community
* **Website:** [https://clawapp.saharaai.com](https://clawapp.saharaai.com)
* **Discord:** [https://discord.gg/9KNneD5c](https://discord.gg/9KNneD5c)
* **Feedback:** Use the #feedback channel in Discord or open a GitHub issue.

---

We are open to any feedback and comments as we continue to evolve. ClawApp is under active development with new features being added regularly; we will keep this README updated with the latest supported functions and improvements.
