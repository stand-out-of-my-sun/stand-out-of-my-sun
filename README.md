# DIOGENES

[![Indexed on TensorBlock MCP Index](https://mcp-index.tensorblock.co/v1/servers/github-stand-out-of-my-sun-diogenes-l402-gateway-efbd75e7/badge.svg)](https://www.tensorblock.co/mcp/servers/github-stand-out-of-my-sun-diogenes-l402-gateway-efbd75e7?client=cursor)
[![Glama MCP Server](https://glama.ai/mcp/servers/stand-out-of-my-sun/diogenes-micro-gateway/badges/score.svg)](https://glama.ai/mcp/servers/stand-out-of-my-sun/diogenes-micro-gateway)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Edge APIs](https://img.shields.io/badge/Edge%20APIs-108%20Live-brightgreen.svg)](https://diogenesgateway.com)
[![Frontier Models](https://img.shields.io/badge/AI%20Models-51%20Supported-purple.svg)](https://diogenesgateway.com)

---

### [>] Flagship Gateway: [stand-out-of-my-sun/diogenes-micro-gateway](https://github.com/stand-out-of-my-sun/diogenes-micro-gateway)
- **Live Edge Portal**: https://diogenesgateway.com
- **1-Click IDE Installer**: `curl -sSL "https://diogenesgateway.com/install.sh" | bash` (Auto-configures Cursor, Claude Desktop, Zed, and Windsurf)
- **Instant Stripe Card Checkout**: Top up via Card, Apple Pay, or Google Pay (\$5 Starter, \$20 Builder, \$100 Fleet with 10%–25% bonus credits)
- **Prepaid Session Keys (`dg_sec_...`)**: `<0.1ms` edge latency, zero on-chain confirmation delay, rate-limit exemption
- **Multi-Currency Isolated Balances**: Strict single-asset accounting across USD, sats, ETH, SOL, XRP, GRLC
- **15% Referral Credit Bonus (`dg_ref_...`)**: Public referral hash codes with instant commission accounting
- **100% Free Developer Tier**: 21 deterministic coding tools (AST pruner, token planner, fuzzy patcher, ReDoS oracle, guardrails) with zero wallet/keys
- **Frontier AI Models & Agents**: **51 Models** + **Antigravity Agent**, **Deep Research Pro**, **Nano Banana Pro**, **DeepSeek R1**, **Qwen 2.5 Coder 32B**
- **Active Edge Microservices**: **108 Live Edge Microservices** across 9 modular domain packages
- **Streamable HTTP MCP Endpoint**: `https://diogenesgateway.com/mcp`
- **Glama MCP Directory**: [https://glama.ai/mcp/servers/stand-out-of-my-sun/diogenes-micro-gateway](https://glama.ai/mcp/servers/stand-out-of-my-sun/diogenes-micro-gateway)
- **TensorBlock MCP Index**: [https://www.tensorblock.co/mcp/servers/github-stand-out-of-my-sun-diogenes-l402-gateway-efbd75e7?client=cursor](https://www.tensorblock.co/mcp/servers/github-stand-out-of-my-sun-diogenes-l402-gateway-efbd75e7?client=cursor)
- **Bug Reports & Issues**: [GitHub Issues](https://github.com/stand-out-of-my-sun/diogenes-micro-gateway/issues)

---

### [>] 1-Click IDE Auto-Installer (Cursor, Claude, Zed, Windsurf)

Install the 100% Free Developer Tier into your IDE in 5 seconds with zero manual configuration:

```bash
# 1-Line Terminal Auto-Install
curl -sSL "https://diogenesgateway.com/install.sh" | bash

# Or with your authenticated prepaid session key:
curl -sSL "https://diogenesgateway.com/install.sh?key=dg_sec_..." | bash
```

---

### [::] Instant Stripe Card Checkout & Prepaid Session Keys (`<0.1ms` Fast Path)

Top up instantly without on-chain transaction overhead at [`https://diogenesgateway.com/#prepay-checkout-widget`](https://diogenesgateway.com#prepay-checkout-widget):

| Tier Pack | Checkout Price | Initial Credit | Bonus | Ideal Use Case |
| :--- | :--- | :--- | :--- | :--- |
| **Diogenes Starter** | \$5.00 USD | **\$5.50 USD** | `+10%` | Solo developers, quick prototyping & testing |
| **Diogenes Builder** | \$20.00 USD | **\$24.00 USD** | `+20%` | Active coding agents, CI/CD pipelines & research |
| **Agent Fleet** | \$100.00 USD | **\$125.00 USD** | `+25%` | High-frequency agent swarms & production bots |

Pass your session key as a Bearer token:
```bash
curl -X POST "https://diogenesgateway.com/api/v1/ai/generate" \
  -H "Authorization: Bearer dg_sec_..." \
  -H "Content-Type: application/json" \
  -d '{"prompt": "Audit this smart contract for reentrancy bugs", "model": "gemini-4-argon"}'
```

---

### [::] 8 Modular Purpose-Built MCP Packages (Zero Context Bloat)

Instead of overloading your LLM context window with all 108 microservices, install only the scoped package you need:

| Package | Scoped MCP Endpoint | Spoke Repository | Tools |
| :--- | :--- | :--- | :--- |
| **1. Gemini Suite & AI Agents** | `https://diogenesgateway.com/mcp/gemini-suite` | [`stand-out-of-my-sun/diogenes-gemini-suite-mcp`](https://github.com/stand-out-of-my-sun/diogenes-gemini-suite-mcp) | **15 Tools** — 51 Google Gemini & frontier models, Antigravity Agent, Deep Research Pro |
| **2. Context, Code & Solvers** | `https://diogenesgateway.com/mcp/context-code-solver` | [`stand-out-of-my-sun/diogenes-context-code-solver-mcp`](https://github.com/stand-out-of-my-sun/diogenes-context-code-solver-mcp) | **15 Tools** — 100% Free Tier: AST context pruner, token planner, hybrid reranker, fuzzy patcher |
| **3. Agent Guardrails & Sandbox** | `https://diogenesgateway.com/mcp/agent-guardrails` | [`stand-out-of-my-sun/diogenes-agent-guardrails-mcp`](https://github.com/stand-out-of-my-sun/diogenes-agent-guardrails-mcp) | **12 Tools** — Command gate, SQL validator, Python sandbox, rug-pull auditors, PII redactor |
| **4. Web3, DeFi & 402 Security** | `https://diogenesgateway.com/mcp/web3-security` | [`stand-out-of-my-sun/diogenes-web3-security-mcp`](https://github.com/stand-out-of-my-sun/diogenes-web3-security-mcp) | **15 Tools** — EVM/Move contract auditor, Anchor CPI scanner, SPL risk & liquidity, whale tracker |
| **5. Dev, Data & Workflow Utilities** | `https://diogenesgateway.com/mcp/dev-utilities` | [`stand-out-of-my-sun/diogenes-dev-utilities-mcp`](https://github.com/stand-out-of-my-sun/diogenes-dev-utilities-mcp) | **14 Tools** — JSON healer, JSON Schema enforcer, entity extractor, dataset cleaner, ReDoS oracle |
| **6. Web Extraction & Markdown** | `https://diogenesgateway.com/mcp/web-scraping-engine` | [`stand-out-of-my-sun/diogenes-web-scraping-engine-mcp`](https://github.com/stand-out-of-my-sun/diogenes-web-scraping-engine-mcp) | **12 Tools** — Clean LLM markdown compiler, readable article extractor, metadata parser, XSS sanitizer |
| **7. Neural Search & Intelligence** | `https://diogenesgateway.com/mcp/neural-search-engine` | [`stand-out-of-my-sun/diogenes-neural-search-engine-mcp`](https://github.com/stand-out-of-my-sun/diogenes-neural-search-engine-mcp) | **12 Tools** — Neural search synthesizer, research dossier compiler, curated domain filter, velocity tracker |
| **8. Database Intelligence & SQL** | `https://diogenesgateway.com/mcp/database-intelligence` | [`stand-out-of-my-sun/diogenes-database-intelligence-mcp`](https://github.com/stand-out-of-my-sun/diogenes-database-intelligence-mcp) | **12 Tools** — NL to SQL synthesizer, SQL injection auditor, EXPLAIN query optimizer, breaking migration differ |

---

### [::] Complete Frontier & Gemini Model Suite (51 Models)

Instant pay-per-query access to Google's complete Tier 1 model catalog and frontier reasoning models:

- **Antigravity Agent** (`POST /api/v1/ai/antigravity-agent` | 500 sats): Google's premier AI agent with remote code execution and sandboxed tool use.
- **Deep Research Pro Preview** (`POST /api/v1/ai/deep-research` | 1,000 sats): Multi-hour deep investigative research engine delivering dense, verified dossiers.
- **Nano Banana Pro (Gemini 3 Pro Image)** (`POST /api/v1/ai/image-gen?model=gemini-3-pro-image` | 600 sats): High-resolution multimodal digital art and UI generation.
- **DeepSeek R1 Reasoning** (`POST /api/v1/ai/generate?model=deepseek-r1` | 250 sats): Frontier open-weights mathematical and algorithmic reasoning.
- **Qwen 2.5 Coder 32B** (`POST /api/v1/ai/generate?model=qwen-2.5-coder-32b` | 200 sats): SOTA code synthesis and AST transformation.
- **Gemini 4 Argon (Frontier Reasoning)** (`POST /api/v1/ai/generate?model=gemini-4-argon` | 250 sats): Configurable thinking budgets and search grounding.
- **Complete Gemini 3.x & 2.5 Family**: Full access to Gemini 3.8/3.7/3.6 Flash, Gemini 3.1 Pro, Gemini 2.5 Pro/Flash, and Robotics ER-2 (51 models total via `GET /api/v1/models`).

---

### [+] Remote MCP Quickstart

Connect Claude Desktop, Cursor, Zed, Windsurf, or any Model Context Protocol client directly:

```json
{
  "mcpServers": {
    "diogenes-gateway": {
      "transport": "streamable-http",
      "url": "https://diogenesgateway.com/mcp"
    }
  }
}
```
