# Inference Optimization · Build-Along

## What you're doing
A hands-on lab benchmarking Claude models across the key metrics that matter in production: time to first token (TTFT), time to completion (TTC), output tokens per second (OTPS), and cost. You'll then explore how prompt caching and tool use affect those numbers.

## Main learning
How to measure and optimize inference for real deployments. You'll compare Haiku, Sonnet, and Opus across speed and cost, see the impact of prompt caching on latency and spend, and instrument an agentic loop to understand where time actually goes.

## How to run

**Option 1 — Google Colab (recommended)**
Open `Inference_Optimization.ipynb` in Colab. Paste your Anthropic API key into the setup cell, then run all cells.

**Option 2 — Jupyter locally**
```bash
jupyter notebook Inference_Optimization.ipynb
```

**Option 3 — Python in VS Code or terminal**
```bash
python Inference_Optimization.py
```
Set your API key as an environment variable first:
```bash
export ANTHROPIC_API_KEY=your_key_here
```
