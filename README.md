# ADD Framework Skills

**The universal skills for the Assess-Decide-Do (ADD) cognitive framework.**

These skills are the single source of truth for ADD methodology, designed to be embedded in any Claude environment (Claude Code, Cowork, API, etc.).

## What is ADD?

The Assess-Decide-Do framework maps human cognitive patterns into three distinct realms:

- **🔴 ASSESS** — Explore, evaluate, dream without commitment
- **🟠 DECIDE** — Prioritize, allocate resources, commit
- **🟢 DO** — Execute, complete, create livelines

When AI understands *where you are* in your thinking process, collaboration transforms from transactional to relational.

**[Full framework documentation →](https://github.com/dragosroua/claude-assess-decide-do-mega-prompt)**

## Skills Included

| Skill | Purpose |
|-------|---------|
| `add-core` | Unified overview of ADD framework (entry point) |
| `add-assess` | Deep support for Assess realm |
| `add-decide` | Deep support for Decide realm |
| `add-do` | Deep support for Do realm |
| `add-imbalance` | Detect and support stuck patterns |
| `add-realm-detection` | Centralized detection patterns |

## Usage

### For Claude Code

Add as a git subtree to your project:

```bash
git subtree add --prefix=.claude/skills/add \
  https://github.com/dragosroua/add-framework-skills.git main --squash
```

To update later:

```bash
git subtree pull --prefix=.claude/skills/add \
  https://github.com/dragosroua/add-framework-skills.git main --squash
```

### For Claude Cowork Plugins

Add as a git subtree to your plugin:

```bash
git subtree add --prefix=skills/add \
  https://github.com/dragosroua/add-framework-skills.git main --squash
```

### For Other Environments

Copy the `skills/` directory into your skill/prompt location.

## Directory Structure

```
add-framework-skills/
├── skills/
│   ├── add-core/
│   │   └── SKILL.md         # Unified overview (start here)
│   ├── add-assess/
│   │   └── SKILL.md         # Assess realm support
│   ├── add-decide/
│   │   └── SKILL.md         # Decide realm support
│   ├── add-do/
│   │   └── SKILL.md         # Do realm support
│   ├── add-imbalance/
│   │   └── SKILL.md         # Imbalance detection
│   └── add-realm-detection/
│       └── SKILL.md         # Detection patterns
├── README.md
├── LICENSE
└── CHANGELOG.md
```

## Environment-Specific Extensions

These skills are **environment-agnostic**. Consumers add their own layers:

### Claude Code adds:
- `add-flow-check.md` — Auto-update `.add-status` file
- `add-status.md` — User-invocable status display
- `add-reflect.md` — Subagent-powered session reflection
- Statusline integration

### Claude Cowork adds:
- `/assess`, `/decide`, `/do` commands
- `/status`, `/balance` commands
- Plugin marketplace integration

## Philosophy

- **Livelines, not deadlines** — Completions open new possibilities
- **Decisions are creative acts** — Each choice shapes reality
- **Fractal operation** — ADD works at all scales simultaneously
- **Cascade principle** — Poor Assess → Poor Decide → Poor Do

## Related Projects

- **[claude-assess-decide-do-mega-prompt](https://github.com/dragosroua/claude-assess-decide-do-mega-prompt)** — Full Claude Code integration
- **[add-framework-cowork-plugin](https://github.com/dragosroua/add-framework-cowork-plugin)** — Claude Cowork plugin
- **[addTaskManager](https://itunes.apple.com/app/apple-store/id1492487688?mt=8)** — iOS/macOS app implementing ADD
- **[Assess - Decide - Do hubpage on dragosroua.com](https://addtaskmanager.com)** — all related framework posts from 2009 to 2026

## License

MIT License — See [LICENSE](LICENSE)

## Author

Created by [Dragos Roua](https://dragosroua.com)

---

*"When AI understands where you are in your thinking, collaboration transforms from transactional to relational."*
