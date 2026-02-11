# formae-marketplace

Claude Code plugin marketplace for [formae](https://formae.io) infrastructure-as-code.

## Setup

Register the marketplace in Claude Code:

```
/plugin marketplace add platform-engineering-labs/formae-marketplace
```

## Available Plugins

### formae-mcp

MCP server and skills for managing cloud infrastructure through formae. Provides 15 MCP tools and 12 skills for deploying, querying, and managing infrastructure.

Install:

```
/plugin install formae-mcp@formae-marketplace
```

**Prerequisites:** Go 1.25+ and a running formae agent (`formae agent start`). The MCP server binary is built automatically on first use.

## License

FSL-1.1-ALv2
