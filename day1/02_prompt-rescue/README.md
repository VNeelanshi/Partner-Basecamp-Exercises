# Prompt Rescue · Build-Along

## What you're doing
You've been pulled in as a technical consultant for TechSupport Corp. They have a production prompt that processes support tickets — classifying priority, extracting entities, and drafting responses. It works on clean inputs but fails badly on messy real-world tickets. Their renewal meeting is in 48 hours. Your job: rescue the prompt.

## Main learning
How to systematically diagnose and fix a broken prompt. You'll study failure cases, identify root causes (wrong priority classification, hallucinated entities, broken JSON output), and iterate using a built-in eval harness that scores your fixes against a set of real-world test cases.

## How to run

**Option 1 — Google Colab (recommended)**
Open `Prompt_Rescue_solo.ipynb` in Colab. Paste your Anthropic API key into the API key cell, then run all cells.

**Option 2 — Jupyter locally**
```bash
jupyter notebook Prompt_Rescue_solo.ipynb
```

**Option 3 — Python in VS Code or terminal**
```bash
python Prompt_Rescue_solo.py
```
Set your API key as an environment variable first:
```bash
export ANTHROPIC_API_KEY=your_key_here
```
