# Instalação detalhada

Receita Federal NFS-e: Notas Emitida (Detalhes) é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_receita_federal_nfse_emit_det`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_receita_federal_nfse_emit_det` | OAuth 2.1 ou agent-auth |
| Cursor | `https://api.mcp.ai/p_receita_federal_nfse_emit_det` | OAuth 2.1 ou agent-auth |
| VS Code (Copilot) | `https://api.mcp.ai/p_receita_federal_nfse_emit_det` | OAuth 2.1 ou agent-auth |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.receita_federal_nfse_emit_det` (ou `servers.receita_federal_nfse_emit_det` no VS Code) do config do cliente e reinicie.
