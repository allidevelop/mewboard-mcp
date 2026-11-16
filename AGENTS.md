# mewboard-mcp

Public documentation repository for the hosted Mewboard MCP server (https://app.mewboard.com/mcp). It holds no application code: the
app lives in the private repository `allidevelop/mewboard` (local folder `DEV/mylinear`).

- Keep `README.md` in step with the app: tool names (`src/mcp-tools.js`), connect steps (`web/docs/connector.html`), prices (`src/billing.js`).
- `server.json` is a copy of `deploy/mcp-registry/server.json` in the app repository (official MCP Registry entry `com.mewboard/mewboard`); publish changes from there, then copy here.
- Images in `images/` come from the site screenshots (`site/shots/en/`) and the link preview (`site/og/en.png`).
- Everything here is public: no secrets, no customer data, no internal notes.
