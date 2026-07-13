# Tyler Szakacs

I build AI products and the infrastructure that makes agents useful: MCP servers, agent-first CLIs, and iOS apps. Based in Philadelphia.

Most of my active work lives in private repos. The public slice below covers the tooling I ship around agent workflows, local Apple integrations, and developer automation.

## Products

**[Vero](https://askvero.app)** is a personal finance app for iOS. Connect your accounts through Plaid and ask questions about your money the way you'd ask a person. Swift/SwiftUI, with a frontier LLM handling the reasoning. Live on the App Store.

**[Preflight](https://github.com/tszaks/Preflight)** is an open-source App Store review scanner for iOS projects. Install the CLI from npm with `npm install -g preflightlaunch` or view the package at [npmjs.com/package/preflightlaunch](https://www.npmjs.com/package/preflightlaunch).

## Public Work

### Agent infrastructure

- [pallium](https://github.com/tszaks/pallium) is a local-first control plane for coding agents: deterministic workflows, bounded loops, persistent agent teams, repo intelligence, and session recall, all outside the model context. Go.
- [agent-pdf](https://github.com/tszaks/agent-pdf) generates clean PDFs from templates so agents make zero design decisions.
- [pulse](https://github.com/tszaks/pulse) is self-hosted web analytics with an API built for agents to query directly.
- [pixel](https://github.com/tszaks/pixel) does image cutouts, transparent PNGs, recoloring, and Topaz-backed upscaling for agents.
- [vero-agent-connect](https://github.com/tszaks/vero-agent-connect) is the public connector for the Vero Agent Access API.

### MCP servers

- [ghub](https://github.com/tszaks/ghub) for multi-account Gmail with built-in OAuth onboarding
- [outlook-mcp](https://github.com/tszaks/outlook-mcp) for Microsoft Outlook via the Graph API
- [safari-mcp](https://github.com/tszaks/safari-mcp) for local Safari control, page extraction, and WebDriver screenshots
- [imessage-mcp](https://github.com/tszaks/imessage-mcp) for iMessage access, conversation search, and attachments
- [apple-notes-mcp](https://github.com/tszaks/apple-notes-mcp) for local Apple Notes management
- [reminders-mcp](https://github.com/tszaks/reminders-mcp) for Apple Reminders and list management
- [icloud-calendar-mcp](https://github.com/tszaks/icloud-calendar-mcp) for iCloud Calendar event CRUD
- [keynote-mcp](https://github.com/tszaks/keynote-mcp) for reading and redesigning Keynote presentations
- [app-store-connect-mcp](https://github.com/tszaks/app-store-connect-mcp) for App Store Connect APIs and release automation

### Developer tooling

- [codex-sessions](https://github.com/tszaks/codex-sessions) shows which Codex sessions are live on your machine. Go.
- [spotify-cli](https://github.com/tszaks/spotify-cli) controls Spotify from the terminal via the Web API.
- [sourcekit-lsp-marketplace](https://github.com/tszaks/sourcekit-lsp-marketplace) adds Swift and Objective-C support to Claude Code via SourceKit-LSP.
- [server-ai-phone-number](https://github.com/tszaks/server-ai-phone-number) bridges Linux AI agents to iMessage over Mac SSH.

## Stack

Swift, SwiftUI, TypeScript, Go, Python, SQL, Claude, Supabase, Vercel, Xcode

## Contact

[tylerszakacs.com](https://tylerszakacs.com) · [szakacsmedia.com](https://szakacsmedia.com) · tyler@szakacsmedia.com
