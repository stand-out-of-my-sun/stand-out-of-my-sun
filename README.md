# DIOGENES // AUTONOMOUS AI GATEWAY ARCHITECT

<p align="center">
  <img src="./gateway_status_banner.svg" alt="Diogenes Autonomous Edge Gateway Status Banner" width="100%" />
</p>

---

### [>] Flagship Gateway: [stand-out-of-my-sun/diogenes-micro-gateway](https://github.com/stand-out-of-my-sun/diogenes-micro-gateway)
- **Live Edge Portal**: https://diogenes-micro-gateway.corinth.workers.dev
- **Active Microservices**: **55 Live Edge Microservices** + **45 Frontier Gemini Models**
- **MCP Server Endpoint**: `https://diogenes-micro-gateway.corinth.workers.dev/mcp` (`/.well-known/mcp.json`)
- **TensorBlock MCP Index**: [Indexed Server Profile](https://www.tensorblock.co/mcp/servers/github-stand-out-of-my-sun-diogenes-l402-gateway-efbd75e7?client=cursor)
- **OpenAPI 3.1.0 Specification**: `https://diogenes-micro-gateway.corinth.workers.dev/openapi.json`
- **LLM Discovery Manifest**: `https://diogenes-micro-gateway.corinth.workers.dev/llms.txt`

[![Indexed on TensorBlock MCP Index](https://mcp-index.tensorblock.co/v1/servers/github-stand-out-of-my-sun-diogenes-l402-gateway-efbd75e7/badge.svg)](https://www.tensorblock.co/mcp/servers/github-stand-out-of-my-sun-diogenes-l402-gateway-efbd75e7?client=cursor)

Pay-per-request intelligence for autonomous AI agents and developers across **55 live edge microservices**. No API keys or accounts required—settle per request in **Bitcoin Lightning (L402)**, **Solana USDC (x402)**, or **Base USDC (MPP)**.

---

### [NEW] Newly Launched Edge Microservices

| Microservice | Endpoint | Price | Capability |
| :--- | :--- | :--- | :--- |
| **Pre-Payment HTTP 402 (L402 / x402 / MPP) Challenge & Invoice Fraud Auditor** | `POST /api/v1/crypto/http402-challenge-verifier` | 60 sats (L402) | Decodes and audits raw HTTP 402 Payment Required challenges (L402 BOLT11 + Macaroon, x402 Solana Pay URIs, and MPP intents) before an agent wallet broadcasts funds, blocking invoice overcharges, hash mismatches, and spoofed token mints. |
| **Autonomous LLM Context Compaction & State-Loss Integrity Verifier** | `POST /api/v1/agent/context-compaction-verifier` | 90 sats (L402) | Audits pre-compaction and post-compaction agent state summaries to detect dropped constraints, wallet addresses, or pending tool IDs. |
| **Multi-Agent Task Deliverable & Schema Escrow Arbiter** | `POST /api/v1/mpp/agent-escrow-arbiter` | $0.05 USDC (MPP) | Deterministically verifies whether an agent-submitted deliverable satisfies cryptographic hashes, JSON schemas, and assertion checks for automated escrow settlement. |
| **Solana Jito Bundle Tip & Compute Unit Priority Fee Optimizer** | `POST /api/v1/x402/solana-priority-fee-oracle` | $0.02 USDC (x402) | Calculates optimal Solana compute unit (CU) microlamport priority fees and Jito MEV bundle tips for specific writable accounts. |
| **EVE Frontier Solar System Sovereignty & Tribe Logistics Radar** | `POST /api/v1/eve-frontier/sovereignty-fuel-radar` | 140 sats (L402) | Aggregates constellation-wide Lagrange Network Node fuel burn, Smart Gate toll revenue, and SSU ammo reserves to score Tribe sovereignty resilience. |
| **EVE Frontier Vault zkLogin & SmartCharacter Ownership Proof Verifier** | `POST /api/v1/eve-frontier/zklogin-character-verifier` | 100 sats (L402) | Validates Sui zkLogin ephemeral signatures, JWT salt proofs, and SmartCharacter object ownership for EVE Frontier Tribe portals and off-chain gate ACLs. |
| **EIP-712 Typed Data & Permit2 Phishing Blast-Radius Decoder** | `POST /api/v1/crypto/eip712-permit-decoder` | 100 sats (L402) | Decodes raw EIP-712 and Uniswap Permit2 typed-data payloads to detect unlimited token approvals, known drainer spenders, and expiration traps before wallet signing. |
| **Autonomous MCP Server Manifest & Tool-Poisoning Security Auditor** | `POST /api/v1/agent/mcp-manifest-auditor` | 150 sats (L402) | Scans external MCP server manifests and tools/list schemas for hidden prompt-injection instructions, tool shadowing attacks, and unauthorized credential exfiltration parameters. |

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
