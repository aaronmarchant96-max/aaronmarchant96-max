<!--
CARDO REI methodology applied to this document.
Reference: [CARDO REI Methodology](PROMPTHOUND-DOCS/CARDO-REI.md)
-->

# PromptHound Labs

> **"The future of AI isn't just about better models — it's about better systems."**
>
> Practical tools and formal frameworks for evaluating AI behavior, catching failures before production, and optimizing LLM systems for security, truthfulness, and cost.

---

## The Short Story

Hi, I'm Aaron Marchant, an AI systems builder and evaluator based in Calgary, Alberta.

I got my first computer in December 2025 and started building software and AI systems in April 2026. Prior to this, I worked in construction with no formal computer science background.

Instead of generic wrappers, I focus on systems engineering: **testing LLM boundaries, catching where models fail, and building deterministic routing and evaluation frameworks to make AI production-ready.**

Today, I work as a **Data Annotator at TELUS Digital**, evaluating real-world AI outputs while designing and shipping open-source AI infrastructure.

---

## Core Focus Areas

Most AI applications send unstructured prompts into frontier models and hope for the best. I build **systems around AI** to enforce:

1. **Security:** Pre-flight prompt firewalls, Base64 decoders, and adversarial scanners that block jailbreaks and role-hijacks before they reach the model.
2. **Cost & Caching Economics:** Smart routing cascades that direct routine queries to cheap models and reserve reasoning models for complex tasks, sustained by deterministic prompt-prefix caching (97%+ cache hit rate).
3. **Empirical Evaluation:** Strict test-driven verification (Feynman Gates) to ensure every claimed metric is backed by reproducible logs, explicit denominators, and counterfactual isolation.

---

## Methodology: CARDO REI

Whether evaluating an LLM router, building a computer-vision pipeline, or structuring historical archives, I use the 8-step **CARDO REI** framework:

* **Collect** — Gather all raw inputs and context without filtering.
* **Analyze** — Examine patterns and separate empirical facts from interpretation.
* **Record** — Isolate and document the load-bearing detail (the hinge).
* **Distinguish** — Maintain clear separation between evidence and inference.
* **Organize** — Structure findings for human auditability and review.
* **Review** — Validate against verified facts and known invariants.
* **Evaluate** — Assign confidence ratings and compute cost-weighted tradeoffs.
* **Iterate** — Refine continuously based on feedback, failure logs, and test evidence.

---

## Projects

| Project | Description | Links |
|---|---|---|
| **REI.ai Platform** | Cost-aware LLM router with multi-provider fallbacks (DeepSeek/Gemini/Groq/OpenAI), Hierarchical Context Memory (HCM), and in-browser security firewall. 876 tests across 69 suites. | [Live App](https://prompthound-labs.vercel.app/#rei) · [Code](https://github.com/aaronmarchant96-max/rei-ai) |
| **Arena Harness** | Automated adversarial evaluation environment for stress-testing LLM rule adherence, jailbreak resistance, and mitigation tracking. | [Code](https://github.com/aaronmarchant96-max/llm-adversarial-testing) |
| **Debate Furnace** | Argument pressure-testing engine that isolates load-bearing reasons from rhetoric and maps decision branches. | [Code](https://github.com/aaronmarchant96-max/debate-furnace) |
| **Family Archive** | Evidence-backed genealogy knowledge base with 117 profiles, 73 original documents, and automated validation tests. | [Live Site](https://family-archive-rose.vercel.app) · [Code](https://github.com/aaronmarchant96-max/family-archive) |
| **UAP Footage Analyzer** | Local OpenCV/Python computer-vision pipeline for automated motion extraction and frame triage from video datasets. | [Code](https://github.com/aaronmarchant96-max/uap-footage-analyzer) |
| **GOES Anomaly Hunter** | NOAA GOES satellite thermal anomaly detection pipeline for identifying and extracting hotspot candidates for review. | [Code](https://github.com/aaronmarchant96-max/goes-anomaly-hunter) |

---

## By The Numbers

- **6 Production Systems** built and deployed
- **876 Automated Unit & Integration Tests** across 69 test suites in the main REI platform, ensuring zero regressions
- **800+ Code Commits** across portfolio repositories
- **$14.66 Total API Spend** processing over **1.35 billion tokens** on an Intel Celeron J4105 PC with a $25/mo budget
- **97%+ Prompt Cache Hit Rate** on structured prefix workloads

---

## Contact

Open to discussions on AI evaluation, prompt security, LLM routing economics, and systems testing.

- **Email:** prompthound.ai@gmail.com
- **X (Twitter):** [@PromptHound96](https://twitter.com/PromptHound96)
- **GitHub:** [github.com/aaronmarchant96-max](https://github.com/aaronmarchant96-max)

---

*Calgary, Alberta.*
