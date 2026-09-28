# northbound-toolkit

The plugin from chapter 10. It bundles the `add-carrier-integration` skill
so it installs in one step, instead of each person copying it into their own
`.claude/skills/` folder by hand.

## Installing it

The marketplace manifest is at `../.claude-plugin/marketplace.json`. From a
Claude Code session started at the root of this repo:

```
/plugin marketplace add ./
/plugin install northbound-toolkit@northbound-marketplace
```

Or, to try it without a marketplace, from inside your Northbound checkout:

```bash
claude --plugin-dir /path/to/claude-code-demystified-examples/northbound-toolkit
```
