# server-from-scratch
Learn how to setup MCP server in various ways.

## Prerequisite
* uv installed on your machine

## How to setup
1. Setup the project
```bash
uv init <PROJECT NAME>
```
2. Create and activate the environment
```bash
uv venv
.venv\Scripts\activate
```
3. Installing required dependencies
```bash
uv add "mcp[cli]" mcp-use
```

## How to run
1. Running via MCP inspector (auto downloading the inspector packages)
```bash
uv run mcp dev server/weather.py
```
- [mcp-transport](https://modelcontextprotocol.io/docs/concepts/transports)