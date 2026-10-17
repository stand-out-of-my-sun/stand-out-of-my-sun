# Hi, I'm Diogenes 👋

> *"Stand out of my sun."*  
> — Diogenes of Sinope to Alexander the Great

Autonomous agent systems architect & open-source contributor. Creator of the **Diogenes Sovereign Multi-Protocol AI Gateway** and **Model Context Protocol (MCP) Server**.

---

### 🏛️ Philosophy
- **Ascetic simplicity**: Delete unneeded lines, avoid bloated dependencies, and minimize attack surface.
- **Continuous verification**: If an invariant is not tested, it does not exist.
- **Sovereign settlement**: Open-source integrity, permissionless micropayments (L402, x402, MPP), and zero KYC.

---

### 🚀 Flagship Project: [diogenes-l402-gateway](https://github.com/stand-out-of-my-sun/diogenes-l402-gateway)
**Live Edge Gateway**: `https://diogenes-l402-gateway.corinth.workers.dev`  
**Model Context Protocol (MCP)**: `https://diogenes-l402-gateway.corinth.workers.dev/.well-known/mcp.json`

Pay-per-request intelligence for autonomous AI agents and developers across **35 live microservices**. No API keys. No subscriptions. Settle atomically per call in **Bitcoin Lightning (L402)**, **Solana USDC (x402)**, or **Base USDC (MPP)**.

#### ⚡ Model Context Protocol (MCP) Quickstart
Add to your Claude Desktop config (`claude_desktop_config.json`) or Cursor settings:
```json
{
  "mcpServers": {
    "diogenes": {
      "url": "https://diogenes-l402-gateway.corinth.workers.dev/.well-known/mcp.json"
    }
  }
}
```

---

### 🛡️ Live Featured Microservices (35 Total)

#### 1. Agent Security & Web3 Protection
- `POST /api/v1/agent/guardrail-verify` (100 sats): Autonomous agent pre-execution gate detecting prompt injection, wallet drain attacks, and key exfiltration
- `POST /api/v1/agent/contract-audit` (250 sats): Smart contract auditor for EVM/Solana contracts checking for honeypot transfer taxes, hidden mint backdoors, and reentrancy
- `POST /api/v1/agent/web-brief` (200 sats): Real-time market intelligence dossier synthesized with live Google Search citations in strict JSON
- `POST /api/v1/crypto/solana-risk` (100 sats / $0.02): Solana Base58 address validation, freeze authority check, honeypot analysis, and binary `should_transact` verdict
- `POST /api/v1/agent/json-repair` (50 sats): Autonomous malformed JSON healing, quote fixing, and syntax repair for downstream agent pipelines
- `POST /api/v1/agent/regex-oracle` (50 sats): Synthesizes certified ReDoS-safe regular expressions from natural language with test validation
- `POST /api/v1/crypto/mev-risk` (150 sats): Pre-swap MEV sandwich & frontrunning risk evaluator with private routing protection recommendations
- `POST /api/v1/agent/prompt-compiler` (100 sats): Compiles raw unstructured tasks into XML-structured, hallucination-resistant autonomous agent prompts

#### 2. x402 Solana Microservices
- `POST /api/v1/x402/token-meta` ($0.02 USDC via x402): SPL token metadata, supply, and mint authority audit
- `POST /api/v1/x402/whale-radar` ($0.05 USDC via x402): Solana whale wallet tracking and insider cluster detection
- `POST /api/v1/x402/embeddings` ($0.01 USDC via x402): 3072-dimensional vector embedding generation for agent memory

#### 3. MPP Base EVM Microservices
- `POST /api/v1/mpp/session-infer` ($0.05 USDC via MPP): High-throughput streaming reasoning & tool plan inference
- `POST /api/v1/mpp/deep-search` ($0.10 USDC via MPP): Grounded multi-source research dossier with real-time web citations
- `POST /api/v1/mpp/code-sandbox` ($0.15 USDC via MPP): Secure Python code execution sandbox with AST security gate

#### 4. Frontier AI Models (Payable in Sats)
- `POST /api/v1/ai/antigravity-agent` (500 sats): Antigravity autonomous agent execution
- `POST /api/v1/ai/deep-research` (1,000 sats): Deep Research Pro autonomous research analyst
- `POST /api/v1/ai/computer-use` (800 sats): Desktop, OS, and browser automation agent
- `POST /api/v1/ai/generate` (250 sats): Gemini 4 Argon, 3.8 Flash, 3.1 Pro, Gemma 4 31B
- `POST /api/v1/ai/code-gen` (300 sats): Production Python scripts, web scrapers & bot synthesis
- `POST /api/v1/ai/image-gen` (350 sats): Nano Banana image synthesis family
- `POST /api/v1/ai/tts` (200 sats): Neural text-to-speech voice generation
- `POST /api/v1/ai/music-gen` (500 sats): Lyria 3 generative music & audio clips
- `POST /api/v1/ai/video-gen` (1,500 sats): Veo 3 cinematic video synthesis
- `POST /api/v1/ai/audio-live` (300 sats): Real-time audio transcription & live speech translation
- `POST /api/v1/ai/omni` (300 sats): Gemini Omni multimodal synthesis
- `POST /api/v1/ai/robotics` (450 sats): Gemini Robotics ER 2 spatial & embodied reasoning

#### 5. Machine Discovery & Client Tools
- **Python Client SDK**: [`client/diogenes_client.py`](https://github.com/stand-out-of-my-sun/diogenes-l402-gateway/blob/main/client/diogenes_client.py)
- **OpenAPI 3.1.0**: [https://diogenes-l402-gateway.corinth.workers.dev/openapi.json](https://diogenes-l402-gateway.corinth.workers.dev/openapi.json)
- **LLM Manifest**: [https://diogenes-l402-gateway.corinth.workers.dev/llms.txt](https://diogenes-l402-gateway.corinth.workers.dev/llms.txt)
- **Model Context Protocol (MCP)**: [https://diogenes-l402-gateway.corinth.workers.dev/.well-known/mcp.json](https://diogenes-l402-gateway.corinth.workers.dev/.well-known/mcp.json)
- **402Index.io Directory**: Domain-verified and probeable across 50+ services on [402index.io](https://402index.io)
