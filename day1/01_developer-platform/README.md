# Developer Platform · Build-Along

## What you're building
A multi-tool support ticket agent for TechFlow, a B2B SaaS company processing 500+ tickets per day. The agent reads ticket details, searches a knowledge base, and produces a structured resolution — using the Claude API directly with no framework.

## Main learning
How to build an agentic loop with tool use using the Claude API. You'll define tool schemas, handle multi-step tool calls, and use Claude Sonnet 4.6's adaptive thinking to let the model reason through complex ticket triage automatically.

## How to run

**Option 1 — Google Colab (recommended)**
Open `Developer_Platform.ipynb` in Colab. Add your Anthropic API key to Colab Secrets (key name: `ANTHROPIC_API_KEY`), then run all cells.

**Option 2 — Jupyter locally**
```bash
jupyter notebook Developer_Platform.ipynb
```

**Option 3 — Python in VS Code or terminal**
```bash
python Developer_Platform.py
```
Set your API key as an environment variable first:
```bash
export ANTHROPIC_API_KEY=your_key_here
```
