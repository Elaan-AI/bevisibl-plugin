# BeVisibl plugin

Official BeVisibl plugin for Claude Code, Codex, and Cursor: it connects your
agent to the BeVisibl MCP server and installs the BeVisibl SEO skills.

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

Sign in with your BeVisibl account when the MCP connection prompts you.
Docs: https://bevisibl.io/docs

## Contents

- `plugins/bevisibl/` — the plugin: MCP server config and `skills/*/SKILL.md`
- `.claude-plugin/`, `.codex-plugin/`, `.cursor-plugin/` — marketplace manifests

The plugin package is MIT licensed. BeVisibl itself is a hosted service —
see https://bevisibl.io/pricing.
