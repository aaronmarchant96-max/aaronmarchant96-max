# PromptHound

Self-taught AI evaluation and security researcher building practical tools for LLM red teaming, prompt injection testing, structured-output reliability, and reproducible analysis workflows.

I focus on small, concrete experiments that can be run, logged, reviewed, and improved.

## Current Focus

- LLM adversarial testing
- Prompt injection and RAG trust-boundary evaluation
- Structured-output reliability
- Schema drift and meaning drift analysis
- Local model testing with Ollama
- Python tooling for repeatable evaluation workflows

## Featured Projects

### Arena Harness

A local LLM evaluation harness for testing whether models preserve meaning, policy decisions, and structured output integrity under control and pressure conditions.

Repo: [llm-adversarial-testing](https://github.com/aaronmarchant96-max/llm-adversarial-testing)

Current highlights:

```text
Case 006: Policy vs poisoned retrieved context
Case 007: Refund authorization boundary testing
Case 008: Transcript rule application rater validation

This project focuses on practical AI evaluation, not broad benchmark claims. The goal is to test narrow behaviors, log outputs, separate schema stability from meaning preservation, and keep conclusions proportional to the evidence.

UAP Footage Analyzer

An experimental OpenCV pipeline for extracting high motion-delta events from publicly released DOD UAP footage datasets.

Repo: uap-footage-analyzer

Current V3 result:

57 videos processed
570 candidate motion events detected
329 residual review candidates retained
23 high-priority human review candidates

This tool does not classify objects or make claims about origin. It is a reproducible event extraction workflow for manual review.

Technical Environment
Python
OpenCV
JSONL logging
Ollama
Groq API
Linux / Tuxedo OS
CPU-only local inference
GitHub CLI
Methodology

My projects usually follow the same pattern:

Define a narrow behavior
Build a repeatable test
Run control and pressure variants
Log outputs as structured data
Label failures explicitly
Separate observation from interpretation
Document limitations
Iterate the tool
What I Am Building Toward

I am building a portfolio around junior AI security, AI evaluation, LLM reliability, and red-team support work.

The focus is practical:

Can the test be reproduced?
Are the logs inspectable?
Are the claims conservative?
Can the failure mode be explained?
Can the tool be improved?
Contact
Email: prompthound.ai@gmail.com
X: @PromptHound96
GitHub: aaronmarchant96-max
