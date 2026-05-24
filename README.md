# PromptHound

**AI evaluation | LLM red teaming | structured output reliability | computer vision event extraction**

Self-taught AI evaluation and security builder in Calgary, Alberta.

I build small, reproducible systems that turn messy inputs into reviewable evidence.

```text
messy input -> candidate signals -> structured logs -> manual review -> documented limits
```

My focus is not broad claims. My focus is narrow tests that can be run, inspected, repeated, and improved.

![Python](https://img.shields.io/badge/Python-111827?style=flat&logo=python)
![React](https://img.shields.io/badge/React-111827?style=flat&logo=react)
![OpenCV](https://img.shields.io/badge/OpenCV-111827?style=flat&logo=opencv)
![Ollama](https://img.shields.io/badge/Ollama-111827?style=flat)
![Linux](https://img.shields.io/badge/Linux-111827?style=flat&logo=linux)
![JSONL](https://img.shields.io/badge/JSONL%20Logging-111827?style=flat)

## What I Build

| Area | Current proof of work |
|---|---|
| LLM evaluation | Local adversarial harnesses, pressure tests, policy boundary checks, and structured output reliability tests |
| Prompt injection | RAG trust-boundary tests, poisoned context cases, and instruction conflict analysis |
| Computer vision | Local OpenCV pipelines for event extraction, motion review, and candidate triage |
| Anomaly workflows | Public footage and satellite pipelines that extract candidates without overclaiming |
| Argument evaluation | Debate Furnace, a React prototype for pressure-testing both sides of a question |

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
JavaScript / React
OpenCV
JSONL logging
Ollama
Groq API
Linux / Tuxedo OS
CPU-only local inference
GitHub CLI
Vite
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
