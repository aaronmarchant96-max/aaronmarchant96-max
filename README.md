<!--
CARDO REI methodology applied to this document.
Reference: [CARDO REI Methodology](PROMPTHOUND-DOCS/CARDO-REI.md)
-->

# PromptHound Labs

> I build AI tools that help people think more clearly.

PromptHound Labs is my portfolio for AI evaluation, reasoning systems, and evidence-based tooling.

My work focuses on turning unclear input into structured output: define the problem, separate facts from assumptions, test the result, and document the limits.

## About Me

I'm a self-taught builder from Calgary, Alberta. I started with my first computer in December 2025 and began building with AI in April 2026. I’m 30, with no formal CS degree, and I’ve focused on learning through shipped work.

I use a small tool stack for cross-checking and validation, including 4 CLI tools and 6 LLM models. The goal is not speed alone — it is to make judgment more disciplined and outputs easier to verify.

In June 2026, I shipped **6 production systems in 11 days** under the PromptHound Labs umbrella, totaling **689 commits** across my repos. I currently work as a **Data Annotator at TELUS**, which keeps my work grounded in careful review, guideline following, and evidence-based judgment.

My main focus is AI evaluation, LLM testing, structured reasoning, and adversarial testing frameworks. I look for failure modes: where systems get confused, where outputs drift, where instructions break down, and where uncertainty should be made explicit.

I use AI development tools as support, not as a substitute for review. I still frame the problem, inspect the output, run the checks, test the app, clean up the docs, and decide whether the work is ready to ship.

My learning style is iterative and practical: build, verify, refine, and then go deeper into the code. That approach has helped me move fast without losing discipline.

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

Self-taught AI evaluation and security builder in Calgary, Alberta.

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

**At the core:** I build structured reasoning systems that turn messy inputs into reviewable evidence. My tools operate across multiple domains, all unified by the CARDO REI methodology.

| Area | Current proof of work |
|---|---|
| LLM evaluation | Local adversarial harnesses, pressure tests, policy boundary checks, and structured output reliability tests |
| Prompt injection | RAG trust-boundary tests, poisoned context cases, and instruction conflict analysis |
| Computer vision | Local OpenCV pipelines for event extraction, motion review, and candidate triage |
| Anomaly workflows | Public footage and satellite pipelines that extract candidates without overclaiming |
| Argument evaluation | Debate Furnace, a React prototype for pressure-testing both sides of a question |
| Cost-benefit analysis | CARDO GUARD, a decision engine that weighs AI risk scores against economic consequences |
| Industrial monitoring | Tracepoint, equipment signal analysis with cost-optimized action recommendations |
| Weather analysis | Storm Replay, historical weather imagery calibration and detection validation |
| Creative transformation | Story Forge, source-to-story blueprints with genre remixing |
| Genealogy research | Family Archive, a production pipeline with 117 profiles, 73 documents, and live deployment |

## Best Place To Start

If you are reviewing this portfolio quickly, start here:

1. **Arena Harness**  
   The strongest AI evaluation repo, with case studies, structured evidence, and repeatable test design.
2. **QA Artifacts**  
   Job-facing QA and UAT examples inside [llm-adversarial-testing/qa_artifacts](https://github.com/aaronmarchant96-max/llm-adversarial-testing/tree/main/qa_artifacts).
3. **Debate Furnace**  
   A product-style React app that shows how I turn structured reasoning ideas into a usable tool.

## Experience

### Professional
- **Data Annotator, TELUS Digital** (Current): Paid AI rating work involving audio review, image-result satisfaction, writing-quality evaluation, and text-response assessment. This work directly supports my portfolio focus on guideline following, careful judgment, expected-vs-actual review, and clear rationale writing.

### Self-Taught Journey
- **December 2025**: First computer
- **April 2026**: Started building with AI
- **June 24-26, 2026**: Shipped **6 production systems in 11 days** (689 commits total)
- **Ongoing**: Continuous learning with 4 CLI tools + 6 LLM models for cross-checking and validation

### Key Stats
- **689+ commits** across 6+ repositories
- **6 production systems** built and shipped in 11 days
- **24 passing Jest tests** in family-archive
- **117 people**, 73 documents in the live Family Archive
- **Multi-AI orchestration**: Using multiple models as support for validation and refinement

## Featured Projects

### 1. Arena Harness

**Repo:** [llm-adversarial-testing](https://github.com/aaronmarchant96-max/llm-adversarial-testing)

A local LLM evaluation harness for testing whether models preserve meaning, policy decisions, and structured output integrity under control and pressure conditions.

Current highlights:

```text
Case 006: Policy vs poisoned retrieved context
Case 007: Refund authorization boundary testing
Case 008: Transcript rule application rater validation
```

What this shows:

```text
local model testing
control vs pressure variants
schema stability vs meaning preservation
structured JSONL logs
failure labels and conservative writeups
```

This is my flagship AI evaluation project.

### 2. Debate Furnace

**Repo:** [debate-furnace](https://github.com/aaronmarchant96-max/debate-furnace)

A React argument pressure-testing app that runs both sides of a question through structured rounds, flags weak reasoning, and shows what survived the heat.

Core line:

```text
We do not give you the answer. We show you what survived the heat.
```

Current focus:

```text
question type detection
claim drift detection
topic-specific final reports
copyable markdown report output
rich script reference archived in /docs
```

This is a product-style evaluation prototype. The live app is intentionally compact for testing, while the richer report logic is preserved in the repo docs.

### 3. UAP Footage Analyzer

**Repo:** [uap-footage-analyzer](https://github.com/aaronmarchant96-max/uap-footage-analyzer)

An experimental OpenCV pipeline for extracting high motion-delta events from publicly released DOD UAP footage datasets.

Current V3 result:

```text
57 videos processed
570 candidate motion events detected
329 residual review candidates retained
23 high-priority human review candidates
```

This tool does not classify objects or make claims about origin. It is a reproducible event extraction workflow for manual review.

### 4. GOES Anomaly Hunter

**Repo:** [goes-anomaly-hunter](https://github.com/aaronmarchant96-max/goes-anomaly-hunter)

A public-data anomaly workflow using NOAA GOES thermal imagery to extract and log candidate hotspot signals for review.

Focus:

```text
public satellite data
thermal thresholding
candidate hotspot extraction
image rendering
structured summaries
```

This project fits the same pattern as the footage tools: extract candidate signals, log them clearly, and avoid claiming more than the data supports.

### 5. Local Video Motion Zone Detector

**Repo:** [local-video-motion-zone-detector](https://github.com/aaronmarchant96-max/local-video-motion-zone-detector)

A lightweight OpenCV motion-zone detector for local video files with synthetic demo footage, JSONL event logs, and annotated snapshots.

Focus:

```text
local video review
zone-based motion detection
synthetic demo input
JSONL event output
annotated frame snapshots
```

This is not facial recognition, object identification, or production surveillance. It is a local event extraction demo.

### 6. CARDO GUARD

**Repo:** [llm-adversarial-testing](https://github.com/aaronmarchant96-max/llm-adversarial-testing) (integrated)

A cost-benefit decision engine that weighs AI risk scores against economic consequences. Built on the principle that "AI confidence is not the decision - cost-weighted consequence is the decision gate."

### 7. Tracepoint

**Repo:** [Private/Industrial] (Integrated into workflow)

Industrial signal monitoring with cost-optimized action recommendations. Tracks equipment signals (vibration, temperature, pressure, flow) and provides human-review-ready decision support.

### 8. Storm Replay

**Repo:** [Private/Weather] (Integrated into workflow)

Historical weather imagery calibration system. Tests detection systems against known events (like the Dec 10-11, 2021 tornado outbreak) to validate thresholds and reduce false negatives.

### 9. Story Forge

**Repo:** [Private/Creative] (Integrated into workflow)

Source-to-story transformation engine. Takes real historical events (like the Donner Party) and generates genre-remixed narratives while maintaining visible source trails.

### 10. Family Archive

**Repo:** [family-archive](https://github.com/aaronmarchant96-max/family-archive) | **Live:** [family-archive-rose.vercel.app](https://family-archive-rose.vercel.app)

A production-grade genealogy research pipeline with 117 people, 73 documents, and 3 family stories. Features automated testing (24 passing Jest tests), CSV-to-JSON ETL, and deployment on Vercel.

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

I am building a portfolio for junior AI security, AI evaluation, LLM reliability, and red-team support work.

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

I don't claim to be an expert in any single domain. But I've built a **methodology (CARDO REI)** and a **brain bank (4 CLIs + 6 LLMs)** that lets me learn fast, build faster, and ship production-grade systems across multiple domains.

What I bring:
- **Self-taught relentlessness**: From zero to production in months
- **Methodology-first thinking**: CARDO REI works across any problem
- **Multi-AI orchestration**: Using multiple models as thinking partners
- **Production mindset**: 689 commits, 6 systems, 11 days. Live site. Real impact.
- **Proven trajectory**: Self-taught, construction background, age 30. Skills beat credentials.

**I'm not waiting for permission. I'm building the future.**
