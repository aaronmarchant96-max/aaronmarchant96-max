---
status: canonical
authority_scope: builder-story-and-case-studies
owner: Aaron Marchant
last_verified: 2026-08-26
verified_against_commit: 9075399
claims_source: docs/CLAIM_LEDGER.md
supersedes: []
superseded_by: null
archived_at: null
---

# Hi there, I'm Aaron Marchant 👋 

**AI Systems Engineer & Solo Founder**  
*Creator of [REI.ai](https://github.com/aaronmarchant96-max/rei-ai) — The OpenAI-Compatible FinOps Proxy & Pre-Spend LLM Router.*

> **"REI does not begin by asking for control of your AI traffic. It begins by earning the right to recommend a change."**

---

## 🎯 Profile & Core Competencies

- **Inference FinOps & Pre-Spend Routing**: Sub-1ms in-memory pre-flight model selection (< 40ms e2e), OpenAI-compatible proxy gateways (`/v1/chat/completions`), prompt-freeze caching, and 3-bucket traffic audits (**97.35% input-cache hit rate** across 1.848B tokens).
- **Zero-Risk Decision Audit & Shadow Mode**: Decoupled `ExecutionController` enforcing shadow mode with **0 production model overrides** and **0 extra provider API calls**.
- **Adversarial Security & Local Model Gates**: D1 threat taxonomy (14 threat categories), Feynman Gate evaluation harness, and local LLaMA 3.2 epistemic quality gating.
- **Full-Stack AI Engineering**: End-to-end React/TypeScript interfaces, serverless backends, Customer Pilot Workspace (`/#pilot`), and hexagonal multi-package runtimes (EchoForge).
- **Empirical Rigor**: **1,364 automated tests across 120 suites** (100% green CI), **1,026 conventional commits**, and machine-reproducible claim verification (`scripts/gen-claims.mjs`).

---

## 🏛️ The Three Flagship Projects

```text
┌─────────────────────────────────────────────────────────────────────────────┐
│                             THE 3-PILLAR TRIAD                              │
├─────────────────────────────────────────────────────────────────────────────┤
│ 1. REI.ai          ──► AI Systems & FinOps (Proxy, <1ms Routing, 1,364 Tests) │
│ 2. Arena Harness   ──► AI Security & Evals (Feynman Gate, 136 Blind Prompts)│
│ 3. Family Archive  ──► Full-Stack Product (GPS Evidence Tiers, Provenance)  │
└─────────────────────────────────────────────────────────────────────────────┘
```

---

### 1. REI.ai — AI FinOps Proxy & Decision Audit Engine
**Repository:** [github.com/aaronmarchant96-max/rei-ai](https://github.com/aaronmarchant96-max/rei-ai) · **Live:** [https://rei.ai](https://rei.ai)

* **Problem**: Engineering teams waste 80%+ of their inference budgets by blindly routing routine queries to expensive flagship models (e.g. GPT-4o) when sub-cent models (e.g. LLaMA 3.1 8B, DeepSeek-Chat) provide identical accuracy.
* **Architecture**:
  - **OpenAI-Compatible Gateway (`/v1/chat/completions`)**: Drop-in proxy for Cursor, Cline, Aider, and backend pipelines.
  - **Pre-Spend Selection**: Evaluates prompt complexity in **`< 1ms`** in-memory (**`< 40ms`** e2e) without calling an LLM to route an LLM.
  - **3-Bucket Audit Segmentation**: Categorizes requests into *Candidate to Shadow*, *Retain Current Tier*, and *Insufficient Evidence*.
  - **`ingestable ≠ replay-routable`**: Missing or redacted prompt text is normalized in denominator audits but excluded from savings claims.
  - **BYOK SaaS Model**: Customer-owned provider keys; zero inference balance-sheet liability.
* **Measured Telemetry**:
  - **1,364 passing automated tests** across 120 test suites (100% green CI).
  - **1,026 conventional commits** on `main` branch.
  - **1.848B development tokens** processed through OpenCode/DeepSeek build workflow for **$23.52** ($567.06 savings vs $590.57 no-cache counterfactual).
  - **< 1ms in-memory decision latency**.
* **Reproduce from Clean Checkout**:
  ```bash
  git clone https://github.com/aaronmarchant96-max/rei-ai.git
  cd rei-ai && npm install
  npm test
  npm run dev
  ```

---

### 2. Arena Harness — Adversarial AI Evaluation & Benchmarking
**Integrated Module:** [`rei-ai/src/__eval__`](https://github.com/aaronmarchant96-max/rei-ai/tree/main/src/__eval__) · [`docs/DEFENSE_IN_DEPTH_CONTROL_MATRIX.md`](https://github.com/aaronmarchant96-max/rei-ai/blob/main/docs/DEFENSE_IN_DEPTH_CONTROL_MATRIX.md)

* **Problem**: AI benchmarks often suffer from dataset contamination, brittle regex parsers, and ungrounded claims. Teams lack standardized ways to test model resilience against prompt injections, system extraction, and quality degradation.
* **Architecture**:
  - **D1 Threat Taxonomy**: Zero-token scanner flagging recursive jailbreaks, base64 ciphers, credential leaks, and identity spoofing before API dispatch.
  - **Feynman Gate Suite**: 136 ground-truth holdout queries evaluating accuracy across 5 specialized reasoning domains.
  - **Local Model Quality Gate**: Evaluates local candidate models (LLaMA 3.2 3B) separating CARDO structural score from Epistemic correctness score.
* **Measured Result**:
  - **100% adherence** under red-team stress testing.
  - **99.0% epistemic correctness** on local LLaMA candidates.
  - **Zero silent tool failures**: Strictly validates tool arguments against JSON/Zod schemas with automatic retry loops.

---

### 3. Family Archive — Full-Stack Knowledge Graph & Genealogical Provenance
**Repository:** [github.com/aaronmarchant96-max/family-archive](https://github.com/aaronmarchant96-max/family-archive) · **Engine Spec:** [`docs/FAMILY_ARCHIVE_PORTING_SPEC.md`](https://github.com/aaronmarchant96-max/rei-ai/blob/main/docs/FAMILY_ARCHIVE_PORTING_SPEC.md)

* **Problem**: Historical databases suffer from catastrophic hallucination when AI systems merge records of individuals sharing identical names and birth years.
* **Architecture**:
  - **4-Tier Genealogical Proof Standard (GPS) Classifier**: Enforces strict epistemic tiers (`primary_direct`, `secondary_derivative`, `inferred_modeled`, `negative_search`).
  - **Disambiguation Hinge Evaluator**: Isolates conflicting facts before asserting identity matches.
  - **Negative Search Audit Receipts**: Logs exhaustively searched databases where no record was found.
* **Measured Result**:
  - **100% citation provenance** on generated genealogical assertions.
  - Reusable standalone TypeScript library (`archivistEngine.ts`) with dedicated unit test suite.

---

## 🛠️ Build Benchmarks & Engineering Rigor

```text
┌─────────────────────────────────────────────────────────────────────────────┐
│                          AARON'S BUILD BENCHMARKS                           │
├─────────────────────────────────────────────────────────────────────────────┤
│ • Total Tokens Processed ──► 1.848 Billion development & evaluation tokens  │
│ • Total Build Spend     ──► $23.52 API spend (97.35% input cache hit rate)  │
│ • Verified Test Suite   ──► 1,364 tests across 120 suites (100% Green CI)   │
│ • Git History           ──► 1,026 conventional commits on main branch       │
│ • Operating Budget      ──► ~$60/month lean serverless infrastructure       │
└─────────────────────────────────────────────────────────────────────────────┘
```

---

## 🌐 Links & Contact

- 🌐 **Live Platform**: [https://rei.ai](https://rei.ai)
- 📦 **Repository**: [github.com/aaronmarchant96-max/rei-ai](https://github.com/aaronmarchant96-max/rei-ai)
- 🐦 **Twitter / X**: [@PromptHound96](https://x.com/PromptHound96)
- 💻 **GitHub**: [github.com/aaronmarchant96-max](https://github.com/aaronmarchant96-max)
