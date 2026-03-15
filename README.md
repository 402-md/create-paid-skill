# Create Paid Skill

AI agent skill for creating monetized APIs and skills using the [SKILL.md Specification v2.0](https://github.com/402-md/skillmd/blob/main/SPEC.md) and the [x402 payment protocol](https://www.x402.org/).

## Install

```bash
npx skills add 402-md/create-paid-skill
```

## What it does

When installed, your AI agent learns how to:

- Create a complete `SKILL.md` file from scratch
- Configure x402 payments (Stellar, Base) with per-request pricing in USDC
- Define API endpoints with JSON Schema input/output
- Write agent-ready documentation that teaches other agents to use the API
- Validate against the full SKILL.md spec
- Convert to MCP tools, A2A Agent Cards, and OpenAPI
- Set up the right directory structure for publishing

## Skill profiles supported

| Profile | Description |
|---------|-------------|
| **Paid API** | REST endpoints with per-call pricing via x402 |
| **Agent Skill** | Pure instructions for AI agents (Claude Code compatible) |
| **Hybrid** | Paid API + agent workflow instructions |

## Example triggers

> "create a paid skill", "monetize my API", "create a SKILL.md",
> "set up x402 payments", "make a paid API for agents",
> "convert OpenAPI to SKILL.md", "build a skill for skills.sh"

## Links

- [SKILL.md Specification v2.0](https://github.com/402-md/skillmd/blob/main/SPEC.md)
- [Reference Implementation (`@402md/skillmd`)](https://github.com/402-md/skillmd)
- [x402 Protocol](https://www.x402.org/)
- [skills.sh](https://skills.sh)
