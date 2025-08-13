# @jinu99/mcp-calculator
[![smithery badge](https://smithery.ai/badge/@jinu99/mcp-calculator)](https://smithery.ai/server/@jinu99/mcp-calculator)
⚠️ This MCP server is incomplete and should not be used for production purposes. Only dependencies are committed to this repo.

My First MCP App: A calculator server for Claude tasks. It's not yet polished or optimized, but it demonstrates some basic concepts.

## Protocol

See [https://github.com/prototypicalpro/mcp](https://github.com/prototypicalpro/mcp)

## Use

Install dependencies:

```shell
npm install
```

Run the server, using a transport mechanism recognized by a Model Context Protocol client:

```shell
node index.js
```

## Features

* `tools/stats` - sum, mean, and deviation using the `simple-statistics` library
* `tools/echo` - echo any input

### Installing via Smithery

To install mcp-calculator for Claude Desktop automatically via [Smithery](https://smithery.ai/server/@jinu99/mcp-calculator):

```bash
npx -y @smithery/cli install @jinu99/mcp-calculator --client claude
```
