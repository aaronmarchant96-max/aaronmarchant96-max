# PromptHound

Self-taught AI evaluation and security builder focused on practical tools for LLM red teaming, prompt injection testing, structured output reliability, and evidence-first analysis workflows.

I build small systems that turn messy inputs into reviewable evidence.

```text
messy input -> candidate signals -> structured logs -> manual review -> documented limits
```

## Current Focus

| Area | What I am building |
|---|---|
| LLM evaluation | Local adversarial harnesses, pressure tests, policy boundary checks, and structured output reliability tests |
| Prompt injection | RAG trust-boundary tests, poisoned context cases, and instruction conflict analysis |
| Computer vision | Local OpenCV pipelines for event extraction and motion review |
| Anomaly workflows | Satellite and public footage pipelines that extract candidates without overclaiming |
| Argument evaluation | Debate Furnace, a React prototype for pressure-testing both sides of a question |

## Featured Projects

### Arena Harness

A local LLM evaluation harness for testing whether models preserve meaning, policy decisions, and structured output integrity under control and pressure conditions.

Repo: [llm-adversarial-testing](https://github.com/aaronmarchant96-max/llm-adversarial-testing)

Current highlights:

```text
Case 006: Policy vs poisoned retrieved context
Case 007: Refund authorization boundary testing
Case 008: Transcript rule application rater validation
```

This is my flagship AI evaluation project. It focuses on narrow, repeatable tests with structured logs, explicit labels, and conservative conclusions.

### Debate Furnace

A React argument pressure-testing app that runs both sides of a question through structured rounds, flags weak reasoning, and shows what survived the heat.

Repo: [debate-furnace](https://github.com/aaronmarchant96-max/debate-furnace)

Current focus:

```text
question type detection
claim drift detection
topic-specific final reports
copyable markdown report output
rich script reference archived in /docs
```

This is a product-style evaluation prototype. The live app is intentionally compact for testing, while the richer report logic is preserved in the repo docs.

### UAP Footage Analyzer

An experimental OpenCV pipeline for extracting high motion-delta events from publicly released DOD UAP footage datasets.

Repo: [uap-footage-analyzer](https://github.com/aaronmarchant96-max/uap-footage-analyzer)

Current V3 result:

```text
57 videos processed
570 candidate motion events detected
329 residual review candidates retained
23 high-priority human review candidates
```

This tool does not classify objects or make claims about origin. It is a reproducible event extraction workflow for manual review.

### GOES Anomaly Hunter

A public-data anomaly workflow using NOAA GOES thermal imagery to extract and log candidate hotspot signals for review.

Repo: [goes-anomaly-hunter](https://github.com/aaronmarchant96-max/goes-anomaly-hunter)

Focus:

```text
public satellite data
thermal thresholding
candidate hotspot extraction
image rendering
structured summaries
```

### Local Video Motion Zone Detector

A lightweight OpenCV motion-zone detector for local video files with synthetic demo footage, JSONL event logs, and annotated snapshots.

Repo: [local-video-motion-zone-detector](https://github.com/aaronmarchant96-max/local-video-motion-zone-detector)

Focus:

```text
local video review
zone-based motion detection
synthetic demo input
JSONL event output
annotated frame snapshots
```

This is not facial recognition, object identification, or production surveillance. It is a local event extraction demo.

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

## Methodology

My projects usually follow the same pattern:

```text
Define a narrow behavior
Build a repeatable test
Run control and pressure variants
Log outputs as structured data
Label failures explicitly
Separate observation from interpretation
Document limitations
Iterate the tool
```

## What I Am Building Toward

I am building a portfolio around junior AI security, AI evaluation, LLM reliability, and red-team support work.

The focus is practical:

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
