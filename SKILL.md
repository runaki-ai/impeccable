---
name: Impeccable
description: |
  Design guidance for AI coding agents. Provides 23 specialized design commands,
  59 deterministic anti-pattern detection rules, and live browser iteration
  for AI-generated frontend design. Helps prevent repetitive SaaS templates
  and improves design quality with unified design vocabulary.
license: Apache-2.0
metadata:
  version: "3.5.0"
  author: pbakaus
---

# Impeccable — Design Guidance for AI Coding Agents

**1 skill, 23 commands, live browser iteration, and 59 deterministic detector rules** for AI-generated frontend design.

## Why Impeccable?

Every model trained on the same SaaS templates. Skip the guidance and you get the same handful of tells on every project: Inter for everything, purple-to-blue gradients, cards nested in cards, gray text on colored backgrounds, the rounded-square icon tile above every heading.

Impeccable adds:
- **One setup flow.** `/impeccable init` writes `PRODUCT.md` and offers `DESIGN.md`, so later commands know the audience, brand/product lane, voice, anti-references, colors, type, and components.
- **23 commands.** A shared design vocabulary with your AI: `polish`, `audit`, `critique`, `distill`, `animate`, `bolder`, `quieter`, and more.
- **59 deterministic detector rules** plus LLM-only critique checks. The CLI and browser extension run the deterministic rules with no LLM and no API key.

## Installation

From your project root:
```bash
npx impeccable install
```

Then run `/impeccable init` inside your AI coding tool.

Full docs: [impeccable.style](https://impeccable.style)

## Supported Tools

- Claude Code
- Cursor
- GitHub Copilot
- Codex CLI
- Grok Build
- Gemini CLI
- OpenCode
- Pi
- Kiro
- Trae
- Rovo Dev
- Qoder
- Mistral Vibe

## License

Apache 2.0
