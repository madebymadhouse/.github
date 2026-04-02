# Contributing to WokSpec

WokSpec is an independent build house. We ship focused tools and runtimes, mostly open source.

---

## What We're Building

| Project | What it is |
|---------|------------|
| **[nqita-cli](https://github.com/wokspec/nqita-cli)** | Agent-agnostic companion runtime for developer AI tools |
| **[LiDock](https://github.com/wokspec/lidock)** | Dock runtime for websites and apps |
| **[token-tengu](https://github.com/wokspec/token-tengu)** | Local context prep layer for the Claude CLI |
| **[Chopsticks](https://github.com/wokspec/chopsticks)** | Self-hostable Discord bot |

---

## How to Get Involved

1. **Look at open issues** — `good first issue` and `help wanted` are the entry points
2. **Propose something** — open an issue before submitting a PR for anything non-trivial
3. **Reach out** — [hello@wokspec.org](mailto:hello@wokspec.org)

---

## Commit Style

We use [Conventional Commits](https://www.conventionalcommits.org/):

```
feat:     new feature
fix:      bug fix
docs:     documentation only
style:    formatting, no logic change
refactor: no feature/fix, just structure
perf:     performance
test:     tests only
chore:    tooling, CI, deps
```

---

## Pull Request Workflow

1. Fork or branch (if you have write access)
2. Install deps (`npm ci` or `pnpm install`)
3. Type-check must pass
4. Linting must pass
5. Commit with conventional commits
6. Open a focused PR — one concern per PR
7. CI must be green before merge

---

## Code of Conduct

See [CODE_OF_CONDUCT.md](./CODE_OF_CONDUCT.md).

---

## AI Agents

Repos include a `CLAUDE.md` with constraints and context for AI-assisted development. If you're using Claude Code or similar — read it before making changes.
