<h1 align="center">gridhra</h1>

<p align="center">
  IT Engineer / Scholar / Swimmer &nbsp;·&nbsp; Saitama, Japan
</p>

<p align="center">
  <a href="https://gridhra.com">gridhra.com</a>
  &nbsp;·&nbsp;
  <a href="https://scrapbox.io/aquila">Cosense</a>
  &nbsp;·&nbsp;
  <a href="https://buymeacoffee.com/gridhra">Buy Me a Coffee</a>
</p>

<p align="center">
  <img alt="Rust" src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white">
  <img alt="Go" src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white">
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white">
  <img alt="PHP" src="https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white">
  <img alt="Dart" src="https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white">
  <img alt="Cloudflare Workers" src="https://img.shields.io/badge/Cloudflare_Workers-F38020?style=flat-square&logo=cloudflare&logoColor=white">
  <img alt="MCP" src="https://img.shields.io/badge/Model_Context_Protocol-111111?style=flat-square">
</p>

I build small, deterministic tools that make AI coding agents useful in practice:
MCP servers, Claude Code environments, and the local infrastructure agents need
to run side by side.

AIエージェントを実務で使うための小さな道具を作っています。MCPサーバー、Claude Code向けの環境、並列で動くエージェントのためのローカル基盤など。

## MCP servers

| | |
|---|---|
| **[atx-mcp](https://github.com/gridhra/atx-mcp)** &nbsp;`Rust` | Deterministic, non-generative image transform server for AI agents. Straighten, crop, mask, layer, and encode as reproducible recipes over immutable originals. Listed in [awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers). |
| **[port-keeper-mcp](https://github.com/gridhra/port-keeper-mcp)** &nbsp;`Go` | A local ledger for development ports, served over MCP. Gives every parallel coding agent its own ports so each one can run the whole stack at the same time. No daemon, no listener, no secrets. |
| **[kkj-mcp](https://github.com/gridhra/kkj-mcp)** &nbsp;`TypeScript` | MCP server for Japan's public procurement portal API（官公需情報ポータルサイト）. Runs over stdio, HTTP, or Cloudflare Workers. |

## Claude Code environments

| | |
|---|---|
| **[claude-samruk](https://github.com/gridhra/claude-samruk)** | A resident research studio for Claude Code. Orchestrator and worker agents are split so raw data never enters the orchestrator's context, and findings accumulate in a two-layer knowledge base with intelligence-analysis discipline (BLUF, source grading, explicit confidence). |
| **[claude-dbd](https://github.com/gridhra/claude-dbd)** &nbsp;`TypeScript` | Daily task management for the Claude Code CLI. Local-first, git-tracked, driven by slash commands. |

## Other projects

- **[mnemorize](https://github.com/gridhra/mnemorize)** `TypeScript` — Opinionated, local-first spaced repetition with offline Whisper, for Japanese.
- **[simple-prompt-holder-in-chrome](https://github.com/gridhra/simple-prompt-holder-in-chrome)** `TypeScript` — A Chrome extension that keeps frequently used prompts one click away.
- **[php-oasv](https://github.com/gridhra/php-oasv)** `PHP` — A thin wrapper around openapi-psr7-validator for request/response testing.
- **[actions](https://github.com/gridhra/actions)** — Composite GitHub Actions I reuse across repositories.

## Elsewhere

- Writing and notes: [gridhra.com](https://gridhra.com) · [Cosense](https://scrapbox.io/aquila)
- The web planetarium [Asterarium](https://gridhra.com) lives on my site.

<sub>Profile icon: portrait drawn by <a href="https://x.com/misumaru11">@misumaru11</a>.</sub>
