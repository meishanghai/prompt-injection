# 🔓 Prompt Injection Red-Team Benchmark

A research framework for studying and benchmarking prompt-injection robustness in Large Language Models (LLMs).

> ⚠️ **Ethical Use Only**: This tool is designed for defensive security research. Only test systems you own or have explicit authorization to test.

## 🎯 Overview

This repository provides a modular, reproducible pipeline for:

1. **Seeding** — Starting with publicly documented injection/jailbreak pattern categories
2. **Mutating** — Using LLMs to paraphrase seeds into diverse test cases
3. **Testing** — Running candidates against a target system (local model or authorized API)
4. **Scoring** — Evaluating success via heuristic checks + LLM-judge
5. **Learning** — Fine-tuning a small generator model on successful attacks

This architecture mirrors established open-source red-team tools like NVIDIA `garak`, Microsoft `PyRIT`, and `promptfoo`.

## 🏗️ Architecture
