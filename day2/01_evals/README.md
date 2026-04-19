# Evals · Build-Along

## What you're building
An eval suite for `boutique`, a simple AI shopping assistant that looks up product prices and does math. The agent works — mostly. Your job is to figure out exactly where it breaks, why, and how to fix it using a systematic eval-driven approach.

## Main learning
How to build evals for AI agents: defining test tasks, writing graders, running the harness, and using results to make targeted improvements. You'll move from "try it and see" to a repeatable feedback loop you can point to with numbers before shipping to a customer.

---

## How to run

### Option 1 — VS Code (recommended)

1. Open VS Code and go to **File → Open Folder**, select this folder.
2. Install the **Python** and **Jupyter** extensions if prompted (search "Jupyter" in the Extensions panel).
3. Open `Building_an_Eval.ipynb`. VS Code will ask you to select a kernel — choose your Python environment.
4. Set your API key. Open a terminal in VS Code (**Terminal → New Terminal**) and run:
   ```bash
   export ANTHROPIC_API_KEY=your_key_here
   ```
5. Run cells using the **▶ Run All** button at the top, or run them one at a time with **Shift+Enter**.

> Prefer a plain Python script? Open `Building_an_Eval.py` instead, set your API key as above, then run:
> ```bash
> python Building_an_Eval.py
> ```

---

### Option 2 — Jupyter locally

1. Make sure Jupyter is installed. If not:
   ```bash
   pip install notebook
   ```
2. Open a terminal, navigate to this folder:
   ```bash
   cd path/to/day2/01_evals
   ```
3. Set your API key:
   ```bash
   export ANTHROPIC_API_KEY=your_key_here
   ```
4. Launch Jupyter:
   ```bash
   jupyter notebook Building_an_Eval.ipynb
   ```
5. In the browser tab that opens, run cells with **Shift+Enter** or use **Cell → Run All**.

---

### Option 3 — Google Colab

1. Go to [colab.research.google.com](https://colab.research.google.com).
2. Click **File → Upload notebook** and select `Building_an_Eval.ipynb`.
3. Paste your Anthropic API key into the setup cell near the top of the notebook.
4. Click **Runtime → Run all**.
