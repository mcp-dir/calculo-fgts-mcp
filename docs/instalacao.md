# Instalação detalhada

Cálculo de FGTS é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_calculo-fgts`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_calculo-fgts` | nenhuma (grátis) |
| Cursor | `https://api.mcp.ai/p_calculo-fgts` | nenhuma |
| VS Code (Copilot) | `https://api.mcp.ai/p_calculo-fgts` | nenhuma |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.calculofgts` (ou `servers.calculofgts` no VS Code) do config do cliente e reinicie.
