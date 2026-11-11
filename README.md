# Otovo for AI assistants

Use Otovo from ChatGPT, Claude, Cursor, Gemini, Grok, Perplexity, Le Chat, VS Code or any app that supports remote MCP servers.

**Server address:** `https://otovo.com/api/v1/mcp` (Streamable HTTP, OAuth 2.1 with dynamic client registration)

Without signing in, anyone with an Otovo scheduling code can see real inspection times and book. Otovo customers in the US and Europe can connect their account to see their sites and production and to book, move or cancel visits. Every change is previewed first and happens only when you approve it.

Setup steps for each app, the tools and permissions: <https://otovo.com/connect>

## Install

- **Cursor:** [Add to Cursor](https://cursor.com/link/mcp/install?name=otovo&config=eyJ1cmwiOiJodHRwczovL290b3ZvLmNvbS9hcGkvdjEvbWNwIn0%3D), or add `mcp.json` from this repository.
- **Gemini CLI:** `gemini extensions install https://github.com/otovo/otovo-mcp`
- **VS Code:** `code --add-mcp '{"name":"otovo","type":"http","url":"https://otovo.com/api/v1/mcp"}'`
- **Any other app:** add a custom connector with the server address above and sign in to Otovo when asked.

Disconnect at any time at <https://otovo.com/oauth/customer/connections>. Privacy: <https://otovo.com/privacy-policy>. Support: support@otovo.com.

This repository holds only the listing files; the server is run by Otovo.
