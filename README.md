# claude-skill-wp-php8-migration

PHP 8.x migration skill for WordPress covering named arguments, union types, match expressions, enums, readonly properties, constructor promotion, and backward compatibility strategies.

## Installation

### Claude Code Plugin Marketplace

```bash
/plugin install https://github.com/xonack/claude-skill-wp-php8-migration
```

### Manual Installation

Copy the skill file to your Claude Code skills directory:

```bash
mkdir -p ~/.claude/skills/wp-php8-migration
cp skills/wp-php8-migration/SKILL.md ~/.claude/skills/wp-php8-migration/SKILL.md
```

## Usage

Once installed, the skill activates automatically when working on relevant WordPress tasks. You can also invoke it directly:

```
/wp-php8-migration
```

## Structure

```
claude-skill-wp-php8-migration/
├── README.md
├── LICENSE
├── .claude-plugin/
│   └── plugin.json
└── skills/
    └── wp-php8-migration/
        └── SKILL.md
```

## Contributing

PRs welcome. Please follow the [Agent Skills specification](https://agentskills.io/specification) for SKILL.md format.

## License

MIT
