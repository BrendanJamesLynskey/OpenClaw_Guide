# OpenClaw — A Deep Dive 🦞

**UID:** `BrendanJamesLynskey/OpenClaw_guide`

A comprehensive, interactive guide to **OpenClaw** — the self-hosted, open-source gateway that connects AI coding agents to any messaging platform. Architecture, configuration, skills, memory, security, and multi-agent routing explained in full.

**[View the live guide →](https://brendanjameslynskey.github.io/OpenClaw_Guide/)**

## Overview

This single-page interactive reference covers the OpenClaw platform end-to-end, from first-principles architecture to production configuration. It is designed as an educational resource for developers looking to deploy their own always-on AI agent infrastructure.

## Topics Covered

- **What Is OpenClaw?** — The problems it solves: always-on availability, channel normalisation, session isolation, persistent memory, skill injection, and security policy
- **Architecture** — The Gateway daemon, Control UI, mobile nodes, and plugin architecture, with an annotated system diagram
- **Channels** — WhatsApp, Telegram, Discord, iMessage, Slack/Signal, and plugin channels; auth methods, group chat controls, and the allowFrom config
- **Agents & Skills** — The agent workspace (AGENTS.md, SOUL.md, USER.md, MEMORY.md), the skill system, SKILL.md frontmatter format, and the ClawHub community registry
- **Memory & Sessions** — The 4-layer memory architecture (context window → JSONL transcripts → durable MEMORY.md → static identity files), context window compaction, and session isolation
- **Security** — The 5-level tool policy chain, allowlists, lane queues, and approval gates
- **Multi-Agent Routing** — Multi-persona routing vs collaborative orchestration; per-agent isolation; enabling agent-to-agent communication via skills
- **Configuration Reference** — Key sections of `openclaw.json`, context pruning config, and the hot-reload model
- **Quick Start** — Step-by-step install, daemon setup, channel pairing, skill installation, and useful CLI commands

## Tech Stack

The guide is a self-contained HTML page with inline CSS and JavaScript — no build step or dependencies required.

## Usage

Clone the repo and open `index.html` in a browser, or visit the [GitHub Pages deployment](https://brendanjameslynskey.github.io/OpenClaw_guide/).

```bash
git clone https://github.com/BrendanJamesLynskey/OpenClaw_guide.git
cd OpenClaw_guide
open index.html
```

## Related Resources

- [OpenClaw Official Docs](https://docs.openclaw.ai/)
- [openclaw/openclaw on GitHub](https://github.com/openclaw/openclaw)
- [awesome-openclaw-skills](https://github.com/VoltAgent/awesome-openclaw-skills) — 5,400+ curated community skills

## Built With

This guide was built with the assistance of **Claude** (Anthropic).

## Author

**Brendan Lynskey** — [GitHub](https://github.com/BrendanJamesLynskey)

## Licence

This project is open source. See the repository for details.
