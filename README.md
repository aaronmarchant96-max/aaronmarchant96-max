<!--
CARDO REI methodology applied to this document.
Reference: [CARDO REI Methodology](PROMPTHOUND-DOCS/CARDO-REI.md)
-->

# PromptHound Labs

> I build AI systems for evaluation, routing, and structured reasoning.

PromptHound Labs is my portfolio for cost-aware LLM systems, adversarial testing, and evidence-based tooling.

My work focuses on turning unclear input into structured output: classify the problem, route it to the right model, make assumptions explicit, and document the limits.

## About Me

I’m a builder and product developer in Calgary, Alberta. I work as a Data Annotator at TELUS, and that review-focused work maps directly to how I build: careful judgment, clear rationale, and conservative claims.

REI.ai is the flagship product: a cost-aware routing and reasoning system that classifies prompts locally, routes them to the cheapest capable model, and keeps the reasoning traceable. Across the public portfolio, I’ve shipped six production systems and 689+ commits.

My main focus is AI evaluation, LLM testing, structured reasoning, and adversarial testing. I look for failure modes: where systems get confused, where outputs drift, where instructions break down, and where uncertainty should be made visible.

I use AI development tools as support, not as a substitute for review. I still frame the problem, inspect the output, run the checks, test the app, clean up the docs, and decide whether the work is ready to ship.

My workflow is iterative and practical: build, verify, refine, and then go deeper into the code.

## Methodology: CARDO REI

Every project follows **CARDO REI** - a methodology I created (inspired by Michio Kaku's philosophy) for structured reasoning across any domain:

- **C**ollect: Gather all relevant information, data, and context
- **A**nalyze: Examine patterns, identify limits, separate fact from interpretation
- **R**ecord: Document with full citations and source trails
- **D**istinguish: Keep evidence separate from inference, facts from stories
- **O**rganize: Structure information for human review and action
- **R**eview: Validate against known truths, check for gaps and conflicts
- **E**valuate: Assign confidence levels, make cost-weighted decisions
- **I**terate: Refine based on feedback and new evidence

This methodology is the foundation of all my work, from AI evaluation to genealogy research. It keeps the output structured, reviewable, and evidence-based.

## How I Build

Every project follows the same basic process:

| Step | What I do | Why it matters |
|---|---|---|
| 1. Idea | Notice a bug, pattern, failure mode, or gap | Find something worth solving |
| 2. Framing | Define the problem and boundaries | Keep the work focused |
| 3. AI Prompt | Give the AI a small scoped task | Use AI for help with execution |
| 4. Build | Create a first working version | Get something real to inspect |
| 5. Verify | Run builds, scripts, diffs, logs, and checks | Catch obvious problems early |
| 6. Manual Review | Test the app, output, and docs myself | Act as the quality gate |
| 7. Commit | Save one clean change at a time | Keep the work traceable |
| 8. Push | Publish the work on GitHub | Keep public proof |
| 9. Case Study | Explain what changed, why it matters, and what the limits are | Show the value without overclaiming |

That process is the main theme of my portfolio.

I am building a repeatable way to test ideas, catch weak spots, and turn rough AI behavior into something structured, reviewable, and useful.

**AI evaluation | LLM red teaming | structured output reliability | computer vision event extraction**

I build small, reproducible systems that turn messy inputs into reviewable evidence.

```text
messy input -> candidate signals -> structured logs -> manual review -> documented limits
```

My focus is narrow tests that can be run, inspected, repeated, and improved.

![Python](https://img.shields.io/badge/Python-111827?style=flat&logo=python)
![React](https://img.shields.io/badge/React-111827?style=flat&logo=react)
![OpenCV](https://img.shields.io/badge/OpenCV-111827?style=flat&logo=opencv)
![Ollama](https://img.shields.io/badge/Ollama-111827?style=flat)
![Linux](https://img.shields.io/badge/Linux-111827?style=flat&logo=linux)
![JSONL](https://img.shields.io/badge/JSONL%20Logging-111827?style=flat)

## What I Build

**At the core:** I build structured reasoning systems that turn messy inputs into reviewable evidence. REI.ai is the flagship, and the supporting tools extend the same approach across evaluation, red-teaming, computer vision, and research workflows.

| Area | Current proof of work |
|---|---|
| REI.ai | Cost-aware LLM routing and structured reasoning. Local classification, model selection, and traceable output. |
| LLM evaluation | Local adversarial harnesses, pressure tests, policy boundary checks, and structured output reliability tests |
| Prompt injection | RAG trust-boundary tests, poisoned context cases, and instruction conflict analysis |
| Computer vision | Local OpenCV pipelines for event extraction, motion review, and candidate triage |
| Anomaly workflows | Public footage and satellite pipelines that extract candidates without overclaiming |
| Argument evaluation | Debate Furnace, a React app for structured argument pressure-testing |
| Cost-benefit analysis | CARDO GUARD, a decision engine that weighs AI risk scores against economic consequences |
| Industrial monitoring | Tracepoint, equipment signal analysis with cost-optimized action recommendations |
| Weather analysis | Storm Replay, historical weather imagery calibration and detection validation |
| Creative transformation | Story Forge, source-to-story blueprints with genre remixing |
| Genealogy research | Family Archive, a production pipeline with 117 profiles, 73 documents, and live deployment |

## Best Place To Start

If you are reviewing this portfolio quickly, start here:

1. **REI.ai**  
   The flagship product: cost-aware routing, structured reasoning, and traceable model selection.
2. **llm-adversarial-testing**  
   Local LLM evaluation harness with case studies, structured evidence, and repeatable test design.
3. **Debate Furnace**  
   A product-style React app that shows how I turn structured reasoning ideas into a usable tool.

## Experience

### Professional
- **Data Annotator, TELUS Digital** (Current): Paid AI rating work involving audio review, image-result satisfaction, writing-quality evaluation, and text-response assessment. This work directly supports my portfolio focus on guideline following, careful judgment, expected-vs-actual review, and clear rationale writing.

### Timeline
- **December 2025**: Started learning and building
- **April 2026**: Began building AI tools publicly
- **June 24-26, 2026**: Shipped **6 production systems in 11 days** (689 commits total)
- **Ongoing**: Multi-model validation and review-first development

### Key Stats
- **689+ commits** across 6+ repositories
- **6 production systems** built and shipped in 11 days
- **440+ tests** in REI.ai across 31 suites
- **117 people**, 73 documents in the live Family Archive
- **Multi-model validation**: multiple tools and providers for cross-checking

## Featured Projects

### 1. REI.ai

**Repo:** [rei-ai](https://github.com/aaronmarchant96-max/rei-ai)

Flagship product for cost-aware LLM routing and structured reasoning. REI.ai classifies prompts locally, routes them to the cheapest capable model, and keeps the reasoning traceable.

Impact: the product keeps the human in the loop while the system handles classification, routing, and the cost gate.

Current highlights:

```text
5 reasoning domains
1.35 billion tokens processed
$14.66 total API cost
440+ tests across 31 suites
12 landmark legal cases
```

### 2. llm-adversarial-testing

**Repo:** [llm-adversarial-testing](https://github.com/aaronmarchant96-max/llm-adversarial-testing)

A local LLM evaluation harness for testing whether models preserve meaning, policy decisions, and structured output integrity under control and pressure conditions.

Impact: catches policy drift, meaning loss, and brittle outputs before they reach a user.

Current highlights:

```text
case studies
control vs pressure variants
schema stability vs meaning preservation
structured JSONL logs
failure labels and conservative writeups
```

### 3. Debate Furnace

**Repo:** [debate-furnace](https://github.com/aaronmarchant96-max/debate-furnace)

A React argument pressure-testing app that runs both sides of a question through structured rounds, flags weak reasoning, and shows what survived the heat.

Impact: turns reasoning into a visible product flow instead of a hidden prompt exercise.

### 4. UAP Footage Analyzer

**Repo:** [uap-footage-analyzer](https://github.com/aaronmarchant96-max/uap-footage-analyzer)

An OpenCV pipeline for extracting high motion-delta events from publicly released DOD UAP footage datasets.

Impact: separates candidate events from interpretation so review stays human-led.

### 5. GOES Anomaly Hunter

**Repo:** [goes-anomaly-hunter](https://github.com/aaronmarchant96-max/goes-anomaly-hunter)

A public-data anomaly workflow using NOAA GOES thermal imagery to extract and log candidate hotspot signals for review.

Impact: logs candidate signals cleanly without claiming more than the data supports.

### 6. Local Video Motion Zone Detector

**Repo:** [local-video-motion-zone-detector](https://github.com/aaronmarchant96-max/local-video-motion-zone-detector)

A lightweight local motion detector for video review with JSONL event logs and annotated snapshots.

Impact: produces inspectable motion candidates for manual review.

### 7. Family Archive

**Repo:** [family-archive](https://github.com/aaronmarchant96-max/family-archive) | **Live:** [family-archive-rose.vercel.app](https://family-archive-rose.vercel.app)

A production genealogy research pipeline with 117 people, 73 documents, automated tests, CSV-to-JSON ETL, and Vercel deployment.

Impact: keeps family records structured, testable, and deployable.

## Integrated Systems

- **CARDO GUARD** — cost-benefit decision engine for AI risk scoring and action gating
- **Tracepoint** — industrial signal monitoring with human-review-ready recommendations
- **Storm Replay** — historical weather imagery calibration and detection validation
- **Story Forge** — source-to-story transformation with visible source trails

## Common Workflow

Most of my projects follow the same pattern:

```text
1. Define a narrow behavior or signal
2. Build a repeatable test or extraction tool
3. Run control and pressure variants where relevant
4. Log outputs as structured data
5. Label failures explicitly
6. Separate observation from interpretation
7. Document limitations
8. Improve the tool based on what broke
```

## Technical Environment

```text
Python
JavaScript
React
Vite
OpenCV
JSONL logging
Ollama
Groq API
Linux / Tuxedo OS
CPU-only local inference
GitHub CLI
```

## What I Am Building Toward

I am a self-taught builder and product developer in Calgary, Alberta. I build a portfolio for AI security, AI evaluation, LLM reliability, and red-team support work.

The practical standard I use:

```text
Can the test be reproduced?
Are the logs inspectable?
Are the claims conservative?
Can the failure mode be explained?
Can the tool be improved?
```

## Contact

Email: prompthound.ai@gmail.com  
X: [@PromptHound96](https://twitter.com/PromptHound96)  
GitHub: [aaronmarchant96-max](https://github.com/aaronmarchant96-max)

---

## My Philosophy

**Structured outputs for messy input. Bring the hard question. We'll find the hinge.**

CARDO REI is the operating method behind the portfolio. It keeps the reasoning visible, separates facts from assumptions, and makes the output easier to review.

What I bring:
- **Methodology-first thinking**: CARDO REI works across domains
- **Evidence-first review**: claims stay tied to testable output
- **Multi-model validation**: multiple tools and providers for cross-checking
- **Production mindset**: public repos, live deployments, and documented limits
