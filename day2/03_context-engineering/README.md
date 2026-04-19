# Context Engineering · Build-Along

## What you're doing
Re-running Chroma's "context rot" experiments — research showing that model performance degrades as input length grows, even on simple tasks. You'll test Claude's behavior as context scales, then explore context engineering techniques that address it.

## Main learning
How context length affects model reliability in practice, and how to engineer around it. You'll run controlled experiments (repeated word faithfulness, needle-in-a-haystack), measure degradation curves, and compare Claude's results against the published GPT-4.1 baseline from Chroma's study.

## How to run

**Option 1 — Google Colab (recommended)**
Open `Context_Engineering.ipynb` in Colab. Paste your Anthropic API key into the setup cell, then run all cells.

**Option 2 — Jupyter locally**
```bash
jupyter notebook Context_Engineering.ipynb
```

**Option 3 — Python in VS Code or terminal**
```bash
python Context_Engineering.py
```
Set your API key as an environment variable first:
```bash
export ANTHROPIC_API_KEY=your_key_here
```
