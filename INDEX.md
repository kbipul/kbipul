# Every build, by lane

45 builds. Generated from [state.json](https://github.com/kbipul/kb-daily-builds/blob/main/state/state.json) on every publish.


## Azure (5)

| Day | Project | What it does | Demo |
|----:|---------|--------------|------|
| 038 | [Still Untrusted](https://github.com/kbipul/still-untrusted) | From-scratch TypeScript reimplementation of Microsoft Agent Framework's FIDES label algebra, checked against its spec. | [Live demo](https://kbipul.github.io/still-untrusted/) |
| 035 | [Conduct Gap](https://github.com/kbipul/conduct-gap) | Falsifiability triage over Microsoft's MAI Code of Conduct: which clauses your evidence could ever test. | [Live demo](https://kbipul.github.io/conduct-gap/) |
| 021 | [kb-agent-framework](https://github.com/kbipul/kb-agent-framework) | Dependency-free TypeScript agent runtime: typed tools, memory, a step-guarded ReAct loop and structured traces. | [Live demo](https://kbipul.github.io/kb-agent-framework/) |
| 019 | [Agent Memory Inspector](https://github.com/kbipul/agent-memory-inspector) | Agent-memory hygiene checks (expired TTLs, contradictions, scope leaks, PII) plus a poisoned-recall simulation. | [Live demo](https://kbipul.github.io/agent-memory-inspector/) |
| 015 | [Will It Fit?](https://github.com/kbipul/will-it-fit) | VRAM and throughput calculator for open-weight LLMs: quantization and KV-cache math against GPUs and Azure VMs. | [Live demo](https://kbipul.github.io/will-it-fit/) |

## Controls (20)

| Day | Project | What it does | Demo |
|----:|---------|--------------|------|
| 045 | [Half the Findings](https://github.com/kbipul/half-the-findings) | Run an audit pipeline on a repo with known ground truth and watch verified findings accumulate without closing the gap. | [Live demo](https://kbipul.github.io/half-the-findings/) |
| 044 | [Approved A, Ran B](https://github.com/kbipul/approved-a-ran-b) | Step through both Loopjacking routes against four approval-binding shapes and see which let a swapped action run. | [Live demo](https://kbipul.github.io/approved-a-ran-b/) |
| 043 | [Pinned, Not Checked](https://github.com/kbipul/pinned-not-checked) | Run the four Plugin4Shell install sequences against a hostile repo and watch a SHA pin report green over swapped code. | [Live demo](https://kbipul.github.io/pinned-not-checked/) |
| 041 | [Oversight Gap](https://github.com/kbipul/oversight-gap) | Anthropic published three agent-oversight metrics and 1-in-47,000 blocked. Move the catch rate it did not publish. | [Live demo](https://kbipul.github.io/oversight-gap/) |
| 040 | [Last Record](https://github.com/kbipul/last-record) | Check an agent tool-call log against the IETF Agent Audit Trail draft, and see what its SHA-256 chain cannot prove. | [Live demo](https://kbipul.github.io/last-record/) |
| 039 | [Ready for Disclosure](https://github.com/kbipul/disclosure-track) | OpenAI's 3-track misalignment disclosure decision rule, checked against the six incidents it just disclosed under it. | [Live demo](https://kbipul.github.io/disclosure-track/) |
| 036 | [Quota Commons](https://github.com/kbipul/quota-commons) | Simulate a fallback router, a batch job and a user app silently sharing one API key's rate limit. | [Live demo](https://kbipul.github.io/quota-commons/) |
| 034 | [Harness Tell](https://github.com/kbipul/harness-tell) | Simulate huggingface_hub's agent/&lt;harness&gt; header: registry fetch, env matching, kill switches, exact User-Agent. | [Live demo](https://kbipul.github.io/harness-tell/) |
| 033 | [Second Tenant](https://github.com/kbipul/second-tenant) | Separate an API usage export into behavioural workloads and see whether one key is carrying two tenants. | [Live demo](https://kbipul.github.io/second-tenant/) |
| 032 | [Burial Depth](https://github.com/kbipul/burial-depth) | Measure how many words of preamble come before an agent's answer, checked against published output conventions. | [Live demo](https://kbipul.github.io/burial-depth/) |
| 031 | [Compaction Drift](https://github.com/kbipul/compaction-drift) | Simulate a long agent session and see which standing rules survive repeated context compaction. | [Live demo](https://kbipul.github.io/compaction-drift/) |
| 030 | [Quiet Throttle](https://github.com/kbipul/quiet-throttle) | Map an AI fleet to CISA AA26-251A's distillation indicators and see how long a silent downgrade hides in eval noise. | [Live demo](https://kbipul.github.io/quiet-throttle/) |
| 029 | [Read-Only Illusion](https://github.com/kbipul/readonly-illusion) | Egress-policy simulator: 13 documented ways a read-only agent policy still writes, triggers or exfiltrates. | [Live demo](https://kbipul.github.io/readonly-illusion/) |
| 027 | [Silent Reasoning](https://github.com/kbipul/silent-reasoning) | See which AI safety controls stop working when a model reasons in latent space instead of visible thought. | [Live demo](https://kbipul.github.io/silent-reasoning/) |
| 026 | [RAG Injection Scanner](https://github.com/kbipul/rag-injection-scanner) | Scan retrieved RAG chunks for prompt injection: overrides, role spoofing, tool-call bait and invisible Unicode. | [Live demo](https://kbipul.github.io/rag-injection-scanner/) |
| 023 | [Escape Sim](https://github.com/kbipul/escape-sim) | AI containment simulator: set sandbox, network, credential and monitoring controls, then watch escalation probe them. | [Live demo](https://kbipul.github.io/escape-sim/) |
| 020 | [Contamination Scanner](https://github.com/kbipul/contamination-scanner) | Train/test contamination scanner: exact, n-gram and near-duplicate overlap, with a clean-subset rescore. | [Live demo](https://kbipul.github.io/contamination-scanner/) |
| 010 | [Blast Radius](https://github.com/kbipul/blast-radius) | Simulate a shell command's blast radius against a virtual filesystem: what dies, what's recoverable, safer rewrite. | [Live demo](https://kbipul.github.io/blast-radius/) |
| 007 | [MCP Auditor](https://github.com/kbipul/mcp-auditor) | Client-side security auditor for MCP server configs: secrets, unpinned execution, capability combos. | [Live demo](https://kbipul.github.io/mcp-auditor/) |
| 006 | [SkillScan](https://github.com/kbipul/skill-scan) | Client-side security scanner for AI agent skill files: injection, exfiltration, permissions, context cost. | [Live demo](https://kbipul.github.io/skill-scan/) |

## Multi-cloud (1)

| Day | Project | What it does | Demo |
|----:|---------|--------------|------|
| 037 | [Alias Drift](https://github.com/kbipul/alias-drift) | Nine identifier types across five AI providers, classified by what happens on deprecation day. | [Live demo](https://kbipul.github.io/alias-drift/) |

## India (3)

| Day | Project | What it does | Demo |
|----:|---------|--------------|------|
| 042 | [Consent Ledger](https://github.com/kbipul/consent-ledger) | Build a DPDP-shaped consent notice for an AI feature and see which pipeline stages it actually authorises. | [Live demo](https://kbipul.github.io/consent-ledger/) |
| 028 | [Indic PII Redactor](https://github.com/kbipul/indic-pii-redactor) | In-browser redaction of Indian identifiers (Aadhaar, PAN, GSTIN, UPI) with checksums and honest confidence tiers. | [Live demo](https://kbipul.github.io/indic-pii-redactor/) |
| 014 | [Bhasha Detect](https://github.com/kbipul/bhasha-detect) | Language ID for India's 22 scheduled languages plus Hinglish, in the browser, with a confusion matrix. No API key. | [Live demo](https://kbipul.github.io/bhasha-detect/) |

## Director (7)

| Day | Project | What it does | Demo |
|----:|---------|--------------|------|
| 025 | [PAIR Planner](https://github.com/kbipul/pair-planner) | Simulate NVIDIA PAIR over your real fleet: which machines are eligible, and what the ineligible ones cost per run. | [Live demo](https://kbipul.github.io/pair-planner/) |
| 024 | [Cache Cliff](https://github.com/kbipul/cache-cliff) | Find the block breaking your Claude prompt-cache prefix, what it strands, and what reordering it is worth per month. | [Live demo](https://kbipul.github.io/cache-cliff/) |
| 022 | [Token Clock](https://github.com/kbipul/token-clock) | Price a full week of LLM traffic against DeepSeek's weekday peak bands and weekend exemption, in your timezone. | [Live demo](https://kbipul.github.io/token-clock/) |
| 011 | [Prompt Compressor](https://github.com/kbipul/prompt-compressor) | Prompt compression lab: measures real token savings on your own text, with embedding fidelity checked in-browser. | [Live demo](https://kbipul.github.io/prompt-compressor/) |
| 009 | [Open Model Passport](https://github.com/kbipul/open-model-passport) | Can you actually ship that model? Licence, weights, residency + EU AI Act clearance report, 100% in-browser. | [Live demo](https://kbipul.github.io/open-model-passport/) |
| 008 | [Prompt Router](https://github.com/kbipul/prompt-router) | Browser LLM router: sends each prompt to the cheapest capable model tier and keeps a live savings ledger. | [Live demo](https://kbipul.github.io/prompt-router/) |
| 004 | [Token Cost Lab](https://github.com/kbipul/token-cost-lab) | LLM cost calculator in the browser: a real tokenizer plus editable per-model pricing, compared side by side. | [Live demo](https://kbipul.github.io/token-cost-lab/) |

## Open (9)

| Day | Project | What it does | Demo |
|----:|---------|--------------|------|
| 018 | [Handoff](https://github.com/kbipul/handoff-inspector) | Multi-agent trace inspector: swimlane timeline plus detectors for dropped handoffs, loops and lost context. | [Live demo](https://kbipul.github.io/handoff-inspector/) |
| 017 | [Agent Scratchpad](https://github.com/kbipul/agent-scratchpad) | ReAct trace player and loop-health analyzer: replays an agent transcript and flags tool-use failures. No key. | [Live demo](https://kbipul.github.io/agent-scratchpad/) |
| 016 | [Tool Caller](https://github.com/kbipul/tool-caller-ts) | Validate and safely repair LLM tool calls against JSON Schema, mapped to the tool-use failure taxonomy. No key. | [Live demo](https://kbipul.github.io/tool-caller-ts/) |
| 013 | [Hybrid Search](https://github.com/kbipul/hybrid-search-ts) | In-browser hybrid search: BM25 + MiniLM vectors fused with Reciprocal Rank Fusion, all client-side. | [Live demo](https://kbipul.github.io/hybrid-search-ts/) |
| 012 | [Context Window Packer](https://github.com/kbipul/context-packer) | Context optimizer: BM25 relevance, a real tokenizer and a 0/1-knapsack packer that beats naive truncation. | [Live demo](https://kbipul.github.io/context-packer/) |
| 005 | [Similar or Not](https://github.com/kbipul/similar-or-not) | Embeddings playground: cosine-similarity heatmap and a live 2D PCA map of any sentences, all in the browser. | [Live demo](https://kbipul.github.io/similar-or-not/) |
| 003 | [Zero-Shot Tagger](https://github.com/kbipul/zero-shot-tagger) | Zero-shot text classification in the browser with transformers.js: your own labels, no training, no API key. | [Live demo](https://kbipul.github.io/zero-shot-tagger/) |
| 002 | [Mood of the Room](https://github.com/kbipul/mood-of-the-room) | In-browser per-sentence sentiment heatmap with transformers.js. No server, no keys. Day 2 of kb-daily-builds. | [Live demo](https://kbipul.github.io/mood-of-the-room/) |
| 001 | [Neural Notes](https://github.com/kbipul/neural-notes) | Semantic note search in the browser with transformers.js. No server, no API keys. Day 1 of kb-daily-builds. | [Live demo](https://kbipul.github.io/neural-notes/) |
