# Firecrawl MCP for Zed

This extension provides a Model Context Server for Firecrawl, for use with the Zed AI Agent.


## Installation

This extension can be installed from the Zed extensions.


## Zed Configuration

To configure Firecrawl MCP in Zed:

1. Open Zed `settings.json` then add the following configuration:

```json
{
  "context_servers": {
  "mcp-server-firecrawl": {
    "settings": {
      "firecrawl_api_key": "YOUR-API-KEY"
    }
  },
}
```

Replace `YOUR-API-KEY` with your Firecrawl API key. If you don't have one yet, create an account at [firecrawl.dev](https://www.firecrawl.dev/app/api-keys).

## Agent Mode Configuration

If you're using Zed's agent mode, you need to enable this context server for your assistant:

1. Open Zed's assistant settings
2. Enable the firecrawl mpc server. If you see that the status of the tool is a red dot, make sure you added your exa api key in settings
3. Enable the firecrawl mpc server in the active assistant profile. In the chat section, click on the `Write | Ask` button, then click on `tools`, then enable the firecrawl mpc server.
