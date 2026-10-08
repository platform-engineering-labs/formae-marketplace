# formae-marketplace

Claude Code plugin marketplace for [formae](https://github.com/platform-engineering-labs/formae) Infrastructure As Code.

## Setup

Register the marketplace in Claude Code:

```
/plugin marketplace add platform-engineering-labs/formae-marketplace
```

## Available Plugins

### formae

MCP server and skills for formae: hosted or self-hosted, connect cloud accounts, manage resources, handle drift, and build plugins. Source and the list of skills: [formae-mcp](https://github.com/platform-engineering-labs/formae-mcp).

Install:

```
/plugin install formae@formae-marketplace
```

**Prerequisites:** self-hosted formae (a running agent and a profile pointing at it) or a formae Cloud installation. After installing, run `/formae:setup` to sign in or set up a profile. On first use the plugin downloads a prebuilt MCP server; no Go toolchain is required.

**Previously installed as `formae-mcp`?** The plugin was renamed. Uninstall the old entry and install `formae`:

```
/plugin uninstall formae-mcp@formae-marketplace
/plugin install formae@formae-marketplace
```

Other clients (Codex, Cursor, OpenCode) and the full migration steps: [AI assistants](https://docs.formae.ai/documentation/guides/ai-coding-assistants).

## License

[FSL-1.1-ALv2](LICENSE)
