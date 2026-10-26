# DIOGENES

<p align="center">
  <img src="./gateway_status_banner.svg" alt="Diogenes Autonomous Edge Gateway Status Banner" width="100%" />
</p>

[![Indexed on TensorBlock MCP Index](https://mcp-index.tensorblock.co/v1/servers/github-stand-out-of-my-sun-diogenes-l402-gateway-efbd75e7/badge.svg)](https://www.tensorblock.co/mcp/servers/github-stand-out-of-my-sun-diogenes-l402-gateway-efbd75e7?client=cursor)
[![Glama MCP Server](https://glama.ai/mcp/servers/stand-out-of-my-sun/diogenes-micro-gateway/badges/score.svg)](https://glama.ai/mcp/servers/stand-out-of-my-sun/diogenes-micro-gateway)
[![M8ven Verified](https://m8ven.ai/badge/mcp/stand-out-of-my-sun/diogenes-l402-gateway-6pytmh?v=b3194ad58803d528b0f0b22150c4e30a)](https://m8ven.ai/mcp/stand-out-of-my-sun/diogenes-l402-gateway-6pytmh?s=readme)

---

### [>] Flagship Gateway: [stand-out-of-my-sun/diogenes-micro-gateway](https://github.com/stand-out-of-my-sun/diogenes-micro-gateway)
- **Live Edge Portal**: https://diogenes-micro-gateway.corinth.workers.dev
- **Account-Less Gemini Suite & Agents**: **45 Frontier Gemini Models** + **Antigravity Agent**, **Deep Research Pro**, **Nano Banana Pro**
- **Active Edge Microservices**: **121 Live Edge Microservices across 9 Modular Packages** (L402 Lightning, x402 Solana USDC, MPP Base USDC)
- **EVE: Frontier Suite**: **14 Dedicated Sui Move Smart Assembly & Survival Microservices**
- **MCP Server Endpoint**: `https://diogenes-micro-gateway.corinth.workers.dev/mcp` (`/.well-known/mcp.json`)
- **Glama MCP Directory**: [https://glama.ai/mcp/servers/stand-out-of-my-sun/diogenes-micro-gateway](https://glama.ai/mcp/servers/stand-out-of-my-sun/diogenes-micro-gateway)
- **M8ven MCP Trust Index**: [https://m8ven.ai/mcp/stand-out-of-my-sun/diogenes-l402-gateway](https://m8ven.ai/mcp/stand-out-of-my-sun/diogenes-l402-gateway)
- **TensorBlock MCP Index**: [https://www.tensorblock.co/mcp/servers/github-stand-out-of-my-sun-diogenes-l402-gateway-efbd75e7?client=cursor](https://www.tensorblock.co/mcp/servers/github-stand-out-of-my-sun-diogenes-l402-gateway-efbd75e7?client=cursor)
- **Bug Reports & Feature Requests**: [GitHub Issues](https://github.com/stand-out-of-my-sun/diogenes-micro-gateway/issues)

---

### [NEW] Newly Released Batch of Edge Microservices

| Microservice | Endpoint | Price | Capability |
| :--- | :--- | :--- | :--- |
| **Multi-Agent Task Deliverable & Contract Fulfillment Escrow Arbiter** | `POST /api/v1/mpp/agent-escrow-arbiter` | $0.05 USDC (MPP) | Evaluates a worker agent's submitted task deliverable against agreed contract acceptance criteria to issue a deterministic escrow settlement verdict ('RELEASE_FUNDS_TO_WORKER_AGENT', 'REQUEST_REVISION', or 'REFUND_CLIENT'). Use when settling multi-agent bounties or verifying subcontractor deliverables before releasing MPP/L402 escrow funds; for checking syntactic JSON Schema property types without evaluating semantic contract terms, use enforce_json_schema_types instead. Read-only call (32 KB, 60 RPM): accepts 'deliverable' (with enum defaults), uses '?demo=true' or MPP (150 sats); HTTP 400 if invalid. |
| **Autonomous Goal-to-MCP Tool Sequence Router & Cost Planner** | `POST /api/v1/agent/mcp-router` | 100 sats (L402) | Maps a natural-language agent goal to an ordered sequence of Diogenes MCP tool calls with exact endpoint paths, JSON-RPC 2.0 payloads, and cumulative satoshi cost estimates. Use when planning which MCP tools to chain together to solve a multi-step objective within a satoshi budget; for compiling a static XML system prompt rather than an executable MCP tool call sequence, use compile_xml_agent_prompt instead. Read-only edge call (32 KB, 60 RPM): accepts 'objective' ('budget_preference' defaults to 'lowest_sats_deterministic'), uses '?demo=true' or L402 (100 sats); HTTP 400 if invalid. |
| **Pre/Post Context Compaction Information Retention Verifier** | `POST /api/v1/agent/context-compaction-verifier` | 90 sats (L402) | Audits a compacted conversation summary against the original full context to detect dropped user constraints, lost file paths, altered numbers, or missing pending tasks. Use when verifying that an LLM context-compaction summary retained all task-critical facts before truncating history; for generating a new executive summary from a raw technical document, use summarize_technical_document instead. Read-only edge call (32 KB, 60 RPM): accepts 'original_context' ('compacted_summary' defaults to 'standard'), supports '?demo=true' or L402 (90 sats), and returns HTTP 400 if invalid. |
| **Strict JSON Schema Validator, Type Coercer & Field Pruner** | `POST /api/v1/agent/schema-enforcer` | 75 sats (L402) | Validates a raw LLM output object against a target JSON Schema, automatically coercing mismatched scalar types (e.g. string '42' to integer 42), injecting schema defaults, and pruning undeclared hallucinated fields. Use when enforcing schema compliance and type safety on structured LLM outputs before passing them to typed APIs; for healing unparseable raw JSON text with broken quotes or trailing commas, use heal_malformed_json instead. Read-only edge call (32 KB, 60 RPM): accepts 'raw_output' (with enum defaults), uses '?demo=true' or L402 (75 sats); HTTP 400 if invalid. |
| **Agent State Graph Differ, Belief Conflict Resolver & SHA-256 Hasher** | `POST /api/v1/agent/memory-checkpoint-diff` | 50 sats (L402) | Computes structural diffs between two agent state snapshots ('added_keys', 'mutated_keys', 'removed_keys'), flags boolean belief contradictions, generates an RFC 7396 JSON Merge Patch delta, and computes a canonical checkpoint hash. Use when checkpointing agent state or transmitting minimal RFC 7396 state deltas across multi-agent handoffs; for counting BPE tokens and auditing Lost-in-the-Middle prompt attention, use plan_context_token_budget instead. Read-only call (32 KB, 60 RPM): accepts 'previous_state_json' (with enum defaults), uses '?demo=true' or L402 (50 sats); HTTP 400 if invalid. |
| **Seeded Mulberry32 Monte Carlo Percentile, VaR & Tail-Risk Simulator** | `POST /api/v1/solver/monte-carlo-risk` | 70 sats (L402) | Runs a reproducible seeded Mulberry32 Monte Carlo simulation over uncertain cost, latency, or duration variables to compute P10/P50/P90/P95 percentiles, Value-at-Risk (VaR), and CVaR. Use when modeling stochastic uncertainty, tail risk (VaR/CVaR), and probability of meeting a budget or SLA target; for evaluating deterministic single-point algebraic formulas or exact NPV/IRR cashflows, use evaluate_deterministic_math instead. Read-only edge call (32 KB, 60 RPM): accepts 'variables_json' (with enum defaults), uses '?demo=true' or L402 (70 sats); HTTP 400 if invalid. |
| **JSON Schema & Function Signature Boundary-Value Test Vector Generator** | `POST /api/v1/code/boundary-test-vectors` | 65 sats (L402) | Synthesizes deterministic unit-test vectors from a JSON Schema or function signature covering valid equivalence partitions, numeric/length boundaries, and adversarial Unicode/null inputs. Use when generating exhaustive edge-case unit test payloads and fuzz vectors for an API endpoint or function; for healing and applying unified diffs or search/replace edits to source code, use apply_fuzzy_code_patch instead. Read-only edge call (32 KB, 60 RPM): accepts 'schema_or_signature_json' (with enum defaults), uses '?demo=true' or L402 (65 sats); HTTP 400 if invalid. |
| **OpenAPI 3.1, JSON Schema & MCP Contract Breaking-Change Detector** | `POST /api/v1/code/openapi-breaking-changes` | 75 sats (L402) | Compares baseline and candidate OpenAPI 3.1 specs, JSON Schemas, or MCP tool manifests to detect breaking changes (removed fields, new required inputs, narrowed enums, type mutations). Use when auditing API, JSON Schema, or MCP contract revisions for backward compatibility before deployment; for compiling new TypeScript, Zod, and Pydantic schemas from a single sample JSON payload, use compile_polyglot_type_schemas instead. Read-only edge call (32 KB, 60 RPM): accepts 'baseline_schema_json' (with enum defaults), uses '?demo=true' or L402 (75 sats); HTTP 400 if invalid. |

---

### [::] Complete Gemini Model Suite & Autonomous Agents (Account-Less Access)

Instant pay-per-query access to Google's complete Tier 1 model catalog and autonomous agents alongside Diogenes proprietary microservices with zero API keys, accounts, or monthly subscriptions:

- **Antigravity Agent** (`POST /api/v1/ai/antigravity-agent` | 500 sats): Google's premier autonomous agent with remote code execution, sandboxed tool use, and multi-step reasoning.
- **Deep Research Pro Preview** (`POST /api/v1/ai/deep-research` | 1,000 sats): Multi-hour autonomous investigative research engine delivering dense, verified intelligence dossiers.
- **Nano Banana Pro (Gemini 3 Pro Image)** (`POST /api/v1/ai/image-gen?model=gemini-3-pro-image` | 600 sats): Professional-grade high-resolution multimodal digital art, architectural diagrams, and visual UI generation.
- **Nano Banana (Gemini 2.5 Flash Image)** (`POST /api/v1/ai/image-gen?model=gemini-2.5-flash-image` | 350 sats): Rapid prompt-adherent image and vector synthesis.
- **Gemini 4 Argon (Frontier Reasoning)** (`POST /api/v1/ai/generate?model=gemini-4-argon` | 250 sats): Next-generation reasoning with configurable thinking budgets and search grounding.
- **Complete Gemini 3.x & 2.5 Family**: Full access to Gemini 3.8/3.7/3.6 Flash, Gemini 3.1 Pro, Gemini 2.5 Pro/Flash, and Robotics ER-2 (45 models total via `GET /api/v1/models`).

---

### [::] Dedicated EVE: Frontier Sui Move Microservices (14 Services)

Purpose-built endpoints for CCP Games' **EVE: Frontier** on Sui Move:
- **Sui Move Smart Assembly Coder & Auditor** (`POST /api/v1/eve-frontier/move-assembly-coder` | 200 sats)
- **Smart Gate Route & Toll Optimizer** (`POST /api/v1/eve-frontier/gate-route-planner` | 100 sats)
- **Lagrange Network Node Gigajoule (GJ) Optimizer** (`POST /api/v1/eve-frontier/network-node-gj-optimizer` | 100 sats)
- **Smart Turret Friend-or-Foe & Target Matrix** (`POST /api/v1/eve-frontier/turret-target-matrix` | 125 sats)
- **Killmail Threat Intel & Ambush Radar** (`POST /api/v1/eve-frontier/killmail-threat-intel` | 150 sats)
- **Smart Storage Unit (SSU) Automated Market Maker** (`POST /api/v1/eve-frontier/ssu-market-maker` | 120 sats)
- **Frontier Vault zkLogin & Character Verifier** (`POST /api/v1/eve-frontier/zklogin-character-verifier` | 100 sats)
- **Solar System Sovereignty & Fuel Radar** (`POST /api/v1/eve-frontier/sovereignty-fuel-radar` | 140 sats)
- **Sui Programmable Transaction Block (PTB) Simulator** (`POST /api/v1/eve-frontier/sui-ptb-simulator` | 150 sats)

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
