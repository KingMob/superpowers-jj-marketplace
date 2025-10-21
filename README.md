# Superpowers Marketplace

Curated Claude Code plugins for skills, workflows, and productivity tools.

## Differences

This is a fork of obra's superpowers marketplace. Almost all credit should go to them.

The only difference is, I replaced the use of git in the superpowers plugin with Jujutsu (jj).

## Installation

Add this marketplace to Claude Code:

```bash
/plugin marketplace add KingMob/superpowers-jj-marketplace
```

## Available Plugins

### Superpowers (Core)

**Description:** Core skills library with TDD, debugging, collaboration patterns, and proven techniques

**Categories:** Testing, Debugging, Collaboration, Meta

**Install:**
```bash
/plugin install superpowers@superpowers-jj-marketplace
```

**What you get:**
- 20+ battle-tested skills
- `/brainstorm`, `/write-plan`, `/execute-plan` commands
- Skills-search tool for discovery
- SessionStart context injection

**Repository:** https://github.com/KingMob/superpowers

---

### Elements of Style

**Description:** Writing guidance based on William Strunk Jr.'s The Elements of Style (1918)

**Categories:** Writing, Documentation, Reference

**Install:**
```bash
/plugin install elements-of-style@superpowers-marketplace
```

**What you get:**
- `writing-clearly-and-concisely` skill
- Complete 1918 reference text (~12k tokens)
- All 18 rules for clear, concise writing
- Grammar, punctuation, and composition guidance

**Repository:** https://github.com/obra/the-elements-of-style

---

## Marketplace Structure

```
superpowers-jj-marketplace/
├── .claude-plugin/
│   └── marketplace.json       # Plugin catalog
└── README.md                  # This file
```

## Support

- **Issues**: https://github.com/KingMob/superpowers-jj-marketplace/issues
- **Core Plugin**: https://github.com/KingMob/superpowers

## License

Marketplace metadata: MIT License

Individual plugins: See respective plugin licenses
