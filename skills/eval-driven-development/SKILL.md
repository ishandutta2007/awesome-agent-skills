---
name: eval-driven-development
description: Building rigorous LLM evaluation pipelines. Use when developing AI features to ensure quality and prevent regressions across different model versions.
---

# Eval-Driven Development

## Overview
Eval-Driven Development ensures that AI features behave deterministically and predictably by testing them against a golden dataset using automated evaluators.

## When to Use
- Building an AI-powered feature
- Tuning prompts or changing underlying models
- Implementing RAG pipelines

## Process
1. **Curate Golden Dataset**: Create diverse test cases including edge cases.
2. **Define Metrics**: Choose appropriate evaluators (e.g., exact match, semantic similarity, LLM-as-a-judge).
3. **Run Pipeline**: Execute the AI feature over the dataset and collect results.
4. **Analyze Failures**: Inspect low-scoring examples and update prompts or logic.
5. **Establish Baseline**: Set a minimum threshold for CI/CD checks.
