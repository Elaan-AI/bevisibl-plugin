# Bevisibl plugin

Official Bevisibl plugin for Claude Code, Codex, and Cursor: it connects your
agent to the Bevisibl MCP server and installs the Bevisibl SEO skills.

## Install

**Claude Code**

```
/plugin marketplace add Elaan-AI/bevisibl-plugin
/plugin install bevisibl@bevisibl
```

**Codex**

```
codex plugin marketplace add Elaan-AI/bevisibl-plugin
codex plugin add bevisibl@bevisibl
```

Sign in with your Bevisibl account when the MCP connection prompts you.
Docs: https://bevisibl.io/docs

## Contents

- `plugins/bevisibl/` — the plugin: MCP server config and `skills/*/SKILL.md`
- `.claude-plugin/`, `.codex-plugin/`, `.cursor-plugin/` — marketplace manifests

The plugin package is MIT licensed. Bevisibl itself is a hosted service —
see https://bevisibl.io/pricing.
