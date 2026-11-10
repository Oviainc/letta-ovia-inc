> **Ovia Inc fork** — We maintain this fork of [letta-ai/letta](https://github.com/letta-ai/letta), the platform for stateful agents — AI with advanced memory that can learn and self-improve over time, grown out of the MemGPT line of work on giving models an operating-system-style memory hierarchy.
>
> **Story:** Letta and Mem0 mark the two poles of agent memory: a platform that makes the agent itself stateful, versus a layer added underneath any agent. Holding both keeps the comparison honest when a build has to choose. The fork sits on the memory shelf for evaluation, with upstream development centred on the letta-code repository the README points to. Upstream credit: Letta (formerly MemGPT). License: Apache-2.0 (see LICENSE). The upstream project is documented below.

---

# Letta

Build stateful agents with memory that can learn and improve over time.

Letta (f.k.a. MemGPT) is actively developed. The current source code lives in [`letta-ai/letta-code`](https://github.com/letta-ai/letta-code), which includes the agent harness, interactive terminal UI, App Server, channels, and the runtime used by the desktop and web apps.

## Get started

Install Letta from npm:

```bash
npm install -g @letta-ai/letta-code
```

Launch the interactive terminal UI:

```bash
letta
```

Run the App Server for local or self-hosted agents:

```bash
letta server
```

You can also use Letta through:

- [chat.letta.com](https://chat.letta.com) in your browser, including on mobile
- [Slack, Telegram, Discord, and custom channels](https://docs.letta.com/letta-code/channels)
- the [Letta Agent SDK](https://docs.letta.com/letta-agent-sdk/overview) for building agents into TypeScript applications
- [Letta Cloud](https://github.com/letta-ai/letta-code#letta-cloud) for keeping agent memory, identity, and conversations available across computers

See the [Letta documentation](https://docs.letta.com) for current installation, development, and deployment instructions.

## Historical source

The [`archive`](https://github.com/letta-ai/letta/tree/archive) branch contains the retired Letta V1 API server. Existing tags and releases remain available for reproducibility, but active projects should use the [current source](https://github.com/letta-ai/letta-code).
