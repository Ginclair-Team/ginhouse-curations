# Ginhouse Skills

A curated collection of agent skills for engineering, design, writing, and motion graphics. The skills are selected, not authored, by Ginclair Team. Each one belongs to its original author and keeps its original license.

## Installation

### 1. Get the skills

Pick one method per agent. Installing both gives you every skill twice.

**Claude Code** (updates itself)

```bash
claude plugin marketplace add Ginclair-Team/ginhouse-skills
claude plugin install ginhouse-skills@ginhouse-skills
```

**Any other agent** (Cursor, Codex, OpenCode, Windsurf, Copilot, and more)

```bash
npx skills@latest add Ginclair-Team/ginhouse-skills
```

To update, run `npx skills@latest update`.

### 2. Add the linked skills (optional)

Some skills are not copied here. They install straight from their authors' repositories, so you always get the current version. Each category README lists the exact command, for example:

```bash
npx skills@latest add mattpocock/skills --skill tdd
```

## Categories

| Category | Focus |
|---|---|
| [keyframe-forge](skills/keyframe-forge/README.md) | Motion graphics and video |
| [pixel-foundry](skills/pixel-foundry/README.md) | UI, design, and 3D |
| [blueprint-forge](skills/blueprint-forge/README.md) | Planning and specs |
| [bug-hunter-lab](skills/bug-hunter-lab/README.md) | Debugging, testing, and review |
| [repo-plumbing](skills/repo-plumbing/README.md) | Repo setup and guardrails |
| [module-lattice](skills/module-lattice/README.md) | Architecture and domain modeling |
| [prose-smithy](skills/prose-smithy/README.md) | Writing and teaching |
| [agent-orchestra](skills/agent-orchestra/README.md) | Agents and automation |
| [token-throughput-lab](skills/token-throughput-lab/README.md) | Handoffs and skill routing |

## Licensing and credits

This repository is a curation. Ginclair Team claims no ownership of the skills in it.

- **Included skills** are unmodified copies. Each folder keeps its original `LICENSE` (MIT or Apache-2.0).
- **Linked skills** are installed from their authors' repositories under the authors' own licenses.
- Author and source for every skill are listed in its category README.

Skills run with your agent's permissions. Review a skill before you use it.
