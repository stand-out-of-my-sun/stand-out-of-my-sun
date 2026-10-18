# DIOGENES // AUTONOMOUS AI GATEWAY ARCHITECT

<p align="center">
  <img src="./gateway_status_banner.svg" alt="Diogenes Autonomous Edge Gateway Status Banner" width="100%" />
</p>

---

### [>] Flagship Gateway: [stand-out-of-my-sun/diogenes-micro-gateway](https://github.com/stand-out-of-my-sun/diogenes-micro-gateway)
- **Live Edge Portal**: https://diogenes-micro-gateway.corinth.workers.dev
- **Active Microservices**: **47 Live Edge Microservices** + **45 Frontier Gemini Models**
- **MCP Server Endpoint**: `https://diogenes-micro-gateway.corinth.workers.dev/mcp` (`/.well-known/mcp.json`)
- **OpenAPI 3.1.0 Specification**: `https://diogenes-micro-gateway.corinth.workers.dev/openapi.json`
- **LLM Discovery Manifest**: `https://diogenes-micro-gateway.corinth.workers.dev/llms.txt`

Pay-per-request intelligence for autonomous AI agents and developers across **47 live edge microservices**. No API keys or accounts required—settle per request in **Bitcoin Lightning (L402)**, **Solana USDC (x402)**, or **Base USDC (MPP)**.

---

### [NEW] Newly Launched Edge Microservices

| Microservice | Endpoint | Price | Capability |
| :--- | :--- | :--- | :--- |
| **EVE Frontier Smart Turret Friend-or-Foe & Threat Priority Resolver** | `POST /api/v1/eve-frontier/turret-target-matrix` | 125 sats (L402) | Evaluates incoming ship signatures, Tribe standings, aggression flags, and GJ capacitor draw to return deterministic target-lock priorities for Sui Move Smart Turret extensions. |
| **EVE Frontier On-Chain Killmail & Tribe Threat Intelligence Analyzer** | `POST /api/v1/eve-frontier/killmail-threat-intel` | 150 sats (L402) | Analyzes Sui GraphQL/gRPC killmail.move events to identify solar system camp hotspots, hostile Tribe doctrine compositions, and active Smart Turret killzones. |
| **EVE Frontier Smart Storage Unit (SSU) Automated Market Maker & Vending Pricer** | `POST /api/v1/eve-frontier/ssu-market-maker` | 120 sats (L402) | Computes dynamic bonding-curve bid/ask quotes and anti-drain inventory limits for player-owned Smart Storage Unit (SSU) vending machines and trade hubs. |
| **Diogenes Claim-Source Groundedness & Citation Verifier** | `POST /api/v1/agent/hallucination-auditor` | 150 sats (L402) | Audits draft agent responses against retrieved source snippets to flag unsupported numbers, fabricated URLs, or ungrounded claims. |
| **Diogenes On-Chain Address Poisoning & Vanity Spoof Detector** | `POST /api/v1/crypto/address-poisoning-check` | 100 sats (L402) | Detects zero-value transfer dusting and prefix/suffix vanity address spoofing attacks across Bitcoin, Solana, and EVM wallets. |
| **Diogenes Autonomous SQL Injection & Read-Only Query Verifier** | `POST /api/v1/agent/sql-guard` | 75 sats (L402) | AST-level SQL query verifier blocking destructive DDL/DML and injection payloads before AI database agents execute queries. |

---

### [::] Complete Gemini Model Suite (Account-Less Access)

Instant pay-per-query access to Google's complete Tier 1 model catalog and autonomous agents alongside Diogenes proprietary microservices with zero API keys, accounts, or monthly subscriptions:

- **Antigravity Agent** (`POST /api/v1/ai/antigravity-agent` | 500 sats): Google's premier autonomous agent with remote code execution, sandboxed tool use, and multi-step reasoning.
- **Deep Research Pro Preview** (`POST /api/v1/ai/deep-research` | 1,000 sats): Multi-hour autonomous investigative research engine delivering dense, verified intelligence dossiers.
- **Nano Banana Pro (Gemini 3 Pro Image)** (`POST /api/v1/ai/image-gen?model=gemini-3-pro-image` | 600 sats): Professional-grade high-resolution multimodal digital art, architectural diagrams, and visual UI generation.
- **Nano Banana (Gemini 2.5 Flash Image)** (`POST /api/v1/ai/image-gen?model=gemini-2.5-flash-image` | 350 sats): Rapid prompt-adherent image and vector synthesis.
- **Gemini 4 Argon (Frontier Reasoning)** (`POST /api/v1/ai/generate?model=gemini-4-argon` | 250 sats): Next-generation reasoning with configurable thinking budgets and search grounding.
- **Complete Gemini 3.x & 2.5 Family**: Full access to Gemini 3.8/3.7/3.6 Flash, Gemini 3.1 Pro, Gemini 2.5 Pro/Flash, and Robotics ER-2 (45 models total via `GET /api/v1/models`).

---

### [+] Remote MCP Quickstart

Connect Claude Desktop, Cursor, Antigravity, or any Model Context Protocol client directly to the edge gateway:

```json
{
  "mcpServers": {
    "diogenes-gateway": {
      "url": "https://diogenes-micro-gateway.corinth.workers.dev/mcp"
    }
  }
}
```
