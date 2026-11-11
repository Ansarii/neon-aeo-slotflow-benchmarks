# 2026-2027 Agentic Web & GEO Protocol Endpoints (neoninnovationlab.com)

1. **Cloudflare-Spec Markdown for Agents (`Accept: text/markdown`)** - Next.js 16 `proxy.ts` negotiates `Accept: text/markdown` and serves stripped Markdown with `Content-Signal: ai-train=yes, search=yes, ai-input=yes`, `Vary: Accept`, and `x-markdown-tokens`.
2. **Microsoft NLWeb (`POST /ask` & `GET /ask`)** - Returns Schema.org `SoftwareApplication`, `WebAPI`, and `Service` JSON entities plus verified facts.
3. **Linux Foundation A2A (`/.well-known/agent-card.json`)** - Cryptographically signed with ES256 JWS verified via `/.well-known/jwks.json` (`100/100 Grade A+` on `a2a-audit`).
4. **Official MCP Registry (`com.neoninnovationlab/enterprise-mcp-gateway`)** - Verified Streamable HTTP MCP endpoint.