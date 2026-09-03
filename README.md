---
status: canonical
authority_scope: builder-story-and-case-studies
owner: Aaron Marchant
last_verified: 2026-09-02
verified_against_commit: 4e729c2
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

- **Inference FinOps & Pre-Spend Routing**: Deterministic pre-flight model selection, OpenAI-compatible proxy gateways (`/v1/chat/completions`), prompt-freeze caching, and 3-bucket traffic audits (**97.3502% measured input-cache hit rate** across 1,848,473,560 tokens).
- **Evidence-Bounded Decision Audit**: Replay analysis precedes live changes. The isolated `ExecutionController` unit contract preserves the requested model and adds no provider call in shadow mode; production integration remains a separate gate.
- **Adversarial Security & Local Model Gates**: A 16-category D1 taxonomy, fixed red-team regression corpus, Feynman Gate evaluation harness, and an incomplete local-model evaluation retained with its failure evidence.
- **Full-Stack AI Engineering**: End-to-end React/TypeScript interfaces, serverless backends, Customer Pilot Workspace (`/#pilot`), and hexagonal multi-package runtimes (EchoForge).
- **Empirical Rigor**: **1,366/1,366 automated tests across 121/121 suites** passed locally on 2026-09-02, with **1,028 commits on `main`**. Hosted GitHub CI is currently blocked before runner execution.

---

## 🏛️ The Three Flagship Projects

```text
┌─────────────────────────────────────────────────────────────────────────────┐
│                             THE 3-PILLAR TRIAD                              │
├─────────────────────────────────────────────────────────────────────────────┤
│ 1. REI.ai          ──► AI Systems & FinOps (Proxy, Evidence, 1,366 Tests)     │
│ 2. Arena Harness   ──► AI Security & Evals (Feynman Gate, 136 Blind Prompts)│
│ 3. Family Archive  ──► Full-Stack Product (GPS Evidence Tiers, Provenance)  │
└─────────────────────────────────────────────────────────────────────────────┘
```

---

### 1. REI.ai — AI FinOps Proxy & Decision Audit Engine
**Repository:** [github.com/aaronmarchant96-max/rei-ai](https://github.com/aaronmarchant96-max/rei-ai) · **Live:** [https://rei.ai](https://rei.ai)

* **Problem**: Teams lack evidence about which routine requests may be candidates for less expensive models without degrading task-specific quality.
* **Architecture**:
  - **OpenAI-Compatible Gateway (`/v1/chat/completions`)**: Drop-in proxy for Cursor, Cline, Aider, and backend pipelines.
  - **Pre-Spend Selection**: Uses deterministic in-memory policy without calling an LLM to route an LLM. A fresh retained benchmark is required before publishing a numeric latency ceiling.
  - **3-Bucket Audit Segmentation**: Categorizes requests into *Candidate to Shadow*, *Retain Current Tier*, and *Insufficient Evidence*.
  - **`ingestable ≠ replay-routable`**: Missing or redacted prompt text is normalized in denominator audits but excluded from savings claims.
  - **BYOK SaaS Model**: Customer-owned provider keys; zero inference balance-sheet liability.
* **Measured Telemetry**:
  - **1,366/1,366 passing automated tests** across 121/121 suites in the latest local run; hosted CI is currently blocked before execution.
  - **1,028 total commits** on the `main` branch as of 2026-09-02.
  - **1.848B development tokens** processed through OpenCode/DeepSeek build workflow for **\$23.52** (\$567.06 savings vs \$590.57 no-cache counterfactual).
  - **70.6% pooled classification accuracy** (96/136 unique samples), with implemented-route holdouts ranging from 90% to 100% under their documented exclusions.
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
  - **D1 Threat Taxonomy**: 16-category zero-token scanner flagging recursive jailbreaks, base64 ciphers, credential leaks, and identity spoofing before API dispatch.
  - **Feynman Gate Suite**: 136 ground-truth holdout queries evaluating accuracy across 5 specialized reasoning domains.
  - **Local Model Quality Gate**: Evaluates local candidate models (LLaMA 3.2 3B) separating CARDO structural score from Epistemic correctness score.
* **Measured Result**:
  - **12/12 correct routes** on the fixed red-team regression corpus, which exercises 11 taxonomy categories; a separate five-entry replay measured 75% route adherence.
  - The local-model overnight run is **incomplete** (98/136 records, including one delivery failure) and is not represented as promotion evidence.
  - Tool arguments are covered by JSON/Zod schema-validation and retry tests; no universal zero-failure claim is made.

---

### 3. Family Archive — Full-Stack Knowledge Graph & Genealogical Provenance
**Repository:** [github.com/aaronmarchant96-max/family-archive](https://github.com/aaronmarchant96-max/family-archive) · **Engine Spec:** [`docs/FAMILY_ARCHIVE_PORTING_SPEC.md`](https://github.com/aaronmarchant96-max/rei-ai/blob/main/docs/FAMILY_ARCHIVE_PORTING_SPEC.md)

* **Problem**: Historical databases suffer from catastrophic hallucination when AI systems merge records of individuals sharing identical names and birth years.
* **Architecture**:
  - **4-Tier Genealogical Proof Standard (GPS) Classifier**: Enforces strict epistemic tiers (`primary_direct`, `secondary_derivative`, `inferred_modeled`, `negative_search`).
  - **Disambiguation Hinge Evaluator**: Isolates conflicting facts before asserting identity matches.
  - **Negative Search Audit Receipts**: Logs exhaustively searched databases where no record was found.
* **Measured Result**:
  - Citation and provenance requirements are enforced through schemas and integrity tests; this is not a claim that every generated assertion has been externally audited.
  - Reusable standalone TypeScript library (`archivistEngine.ts`) with dedicated unit test suite.

---

## 🛠️ Build Benchmarks & Engineering Rigor

```text
┌─────────────────────────────────────────────────────────────────────────────┐
│                          AARON'S BUILD BENCHMARKS                           │
├─────────────────────────────────────────────────────────────────────────────┤
│ • Total Tokens Processed ──► 1.848 Billion development & evaluation tokens  │
│ • Total Build Spend     ──► $23.52 API spend (97.35% input cache hit rate)  │
│ • Verified Test Suite   ──► 1,366/1,366 tests across 121/121 suites (local) │
│ • Git History           ──► 1,028 commits on main (measured 2026-09-02)      │
│ • Operating Budget      ──► ~$60/month lean serverless infrastructure       │
└─────────────────────────────────────────────────────────────────────────────┘
```

---

## 🌐 Links & Contact

- 🌐 **Live Platform**: [https://rei.ai](https://rei.ai)
- 📦 **Repository**: [github.com/aaronmarchant96-max/rei-ai](https://github.com/aaronmarchant96-max/rei-ai)
- 🐦 **Twitter / X**: [@PromptHound96](https://x.com/PromptHound96)
- 💻 **GitHub**: [github.com/aaronmarchant96-max](https://github.com/aaronmarchant96-max)
