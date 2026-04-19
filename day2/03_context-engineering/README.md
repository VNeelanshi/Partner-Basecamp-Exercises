# Context Engineering · Build-Along

## What you're doing
Re-running Chroma's "context rot" experiments — research showing that model performance degrades as input length grows, even on simple tasks. You'll test Claude's behavior as context scales, then explore context engineering techniques that address it.

## Main learning
How context length affects model reliability in practice, and how to engineer around it. You'll run controlled experiments (repeated word faithfulness, needle-in-a-haystack), measure degradation curves, and compare Claude's results against the published GPT-4.1 baseline from Chroma's study.

---

## How to run

### Option 1 — VS Code (recommended)

1. Open VS Code and go to **File → Open Folder**, select this folder.
2. Install the **Python** and **Jupyter** extensions if prompted (search "Jupyter" in the Extensions panel).
3. Open `Context_Engineering.ipynb`. VS Code will ask you to select a kernel — choose your Python environment.
4. Set your API key. Open a terminal in VS Code (**Terminal → New Terminal**) and run:
   ```bash
   export ANTHROPIC_API_KEY=your_key_here
   ```
5. Run cells using the **▶ Run All** button at the top, or run them one at a time with **Shift+Enter**.

> Prefer a plain Python script? Open `Context_Engineering.py` instead, set your API key as above, then run:
> ```bash
> python Context_Engineering.py
> ```

---

### Option 2 — Jupyter locally

1. Make sure Jupyter is installed. If not:
   ```bash
   pip install notebook
   ```
2. Open a terminal, navigate to this folder:
   ```bash
   cd path/to/day2/03_context-engineering
   ```
3. Set your API key:
   ```bash
   export ANTHROPIC_API_KEY=your_key_here
   ```
4. Launch Jupyter:
   ```bash
   jupyter notebook Context_Engineering.ipynb
   ```
5. In the browser tab that opens, run cells with **Shift+Enter** or use **Cell → Run All**.

---

### Option 3 — Google Colab

1. Go to [colab.research.google.com](https://colab.research.google.com).
2. Click **File → Upload notebook** and select `Context_Engineering.ipynb`.
3. Paste your Anthropic API key into the setup cell near the top of the notebook.
4. Click **Runtime → Run all**.
