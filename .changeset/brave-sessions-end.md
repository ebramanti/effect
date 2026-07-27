---
"effect": patch
---

Add injectable MCP session storage and Streamable HTTP DELETE session termination. Provide a custom `McpServer.SessionStore` with `Layer.provide`; an in-memory store is used when none is provided.
