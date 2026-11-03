---
title: Local LLM on Apple Silicon
type: recipe
status: draft
topics: [local-llms, privacy, macos]
last_verified: null
---

# Local LLM on Apple Silicon

**Status: Draft, not yet verified.**

## Goal

Run a small language model locally on an Apple Silicon Mac, with no document content sent to a hosted model.

## Prerequisites

- Apple Silicon Mac
- Permission to install and run local inference software
- Enough free disk space for model weights
- Approval for the specific model, runtime, and data handling, if using a managed work computer

## Candidate workflow

1. Obtain an approved local inference runtime such as Ollama.
2. Choose a suitably sized approved model, such as a compatible Qwen-family model.
3. Download the model from a trusted source.
4. Test inference with synthetic text first.
5. Confirm the runtime is local and no sensitive content is sent to third-party endpoints.
6. Record memory use, latency, output quality, and any limitations.

## Verification checklist

- [ ] Installation permitted
- [ ] Model license and approval checked
- [ ] Test with synthetic text passed
- [ ] Network and data handling reviewed
- [ ] Instructions reproduced on a clean setup

## Lessons learned

_To be filled in after a real test._
