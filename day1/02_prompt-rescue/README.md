# Prompt Rescue · Build-Along

## What you're doing
You've been pulled in as a technical consultant for TechSupport Corp. They have a production prompt that processes support tickets — classifying priority, extracting entities, and drafting responses. It works on clean inputs but fails badly on messy real-world tickets. Their renewal meeting is in 48 hours. Your job: rescue the prompt.

## Main learning
How to systematically diagnose and fix a broken prompt. You'll study failure cases, identify root causes (wrong priority classification, hallucinated entities, broken JSON output), and iterate using a built-in eval harness that scores your fixes against a set of real-world test cases.

---

## How to run

### Option 1 — VS Code (recommended)

1. Open VS Code and go to **File → Open Folder**, select this folder.
2. Install the **Python** and **Jupyter** extensions if prompted (search "Jupyter" in the Extensions panel).
3. Open `Prompt_Rescue_solo.ipynb`. VS Code will ask you to select a kernel — choose your Python environment.
4. Set your API key. Open a terminal in VS Code (**Terminal → New Terminal**) and run:
   ```bash
   export ANTHROPIC_API_KEY=your_key_here
   ```
5. Run cells using the **▶ Run All** button at the top, or run them one at a time with **Shift+Enter**.

> Prefer a plain Python script? Open `Prompt_Rescue_solo.py` instead, set your API key as above, then run:
> ```bash
> python Prompt_Rescue_solo.py
> ```

---

### Option 2 — Jupyter locally

1. Make sure Jupyter is installed. If not:
   ```bash
   pip install notebook
   ```
2. Open a terminal, navigate to this folder:
   ```bash
   cd path/to/day1/02_prompt-rescue
   ```
3. Set your API key:
   ```bash
   export ANTHROPIC_API_KEY=your_key_here
   ```
4. Launch Jupyter:
   ```bash
   jupyter notebook Prompt_Rescue_solo.ipynb
   ```
5. In the browser tab that opens, run cells with **Shift+Enter** or use **Cell → Run All**.

---

### Option 3 — Google Colab

1. Go to [colab.research.google.com](https://colab.research.google.com).
2. Click **File → Upload notebook** and select `Prompt_Rescue_solo.ipynb`.
3. Paste your Anthropic API key into the API key cell near the top of the notebook.
4. Click **Runtime → Run all**.
