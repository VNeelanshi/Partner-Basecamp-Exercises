# Evals · Build-Along

## What you're building
An eval suite for `boutique`, a simple AI shopping assistant that looks up product prices and does math. The agent works — mostly. Your job is to figure out exactly where it breaks, why, and how to fix it using a systematic eval-driven approach.

## Main learning
How to build evals for AI agents: defining test tasks, writing graders, running the harness, and using results to make targeted improvements. You'll move from "try it and see" to a repeatable feedback loop you can point to with numbers before shipping to a customer.

## How to run

**Option 1 — Google Colab (recommended)**
Open `Building_an_Eval.ipynb` in Colab. Paste your Anthropic API key into the setup cell, then run all cells.

**Option 2 — Jupyter locally**
```bash
jupyter notebook Building_an_Eval.ipynb
```

**Option 3 — Python in VS Code or terminal**
```bash
python Building_an_Eval.py
```
Set your API key as an environment variable first:
```bash
export ANTHROPIC_API_KEY=your_key_here
```
