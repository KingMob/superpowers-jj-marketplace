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

**Repository:** https://github.com/KingMob/superpowers-jj

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
- **Core Plugin**: https://github.com/KingMob/superpowers-jj

## License

Marketplace metadata: MIT License

Individual plugins: See respective plugin licenses
