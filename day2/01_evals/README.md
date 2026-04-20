# Evals · Build-Along

## What you're building
An eval suite for `boutique`, a simple AI shopping assistant that looks up product prices and does math. The agent works — mostly. Your job is to figure out exactly where it breaks, why, and how to fix it using a systematic eval-driven approach.

## Main learning
How to build evals for AI agents: defining test tasks, writing graders, running the harness, and using results to make targeted improvements. You'll move from "try it and see" to a repeatable feedback loop you can point to with numbers before shipping to a customer.

---

## How to run

### Option 1 — Google Colab (easiest, no setup)

1. Go to [colab.research.google.com](https://colab.research.google.com).
2. Click **File → Upload notebook** and select `Building_an_Eval.ipynb` from this folder.
3. In the setup cell, paste your Anthropic API key between the quotes:
   ```python
   os.environ["ANTHROPIC_API_KEY"] = "paste-your-key-here"
   ```
4. Click **Runtime → Run all**.

---

### Option 2 — GitHub Codespaces (no local install needed)

1. Go to the repo on GitHub and click the green **Code** button.
2. Select the **Codespaces** tab and click **Create codespace on main**.
3. Wait for the environment to load (takes about a minute).
4. Open `day2/01_evals/Building_an_Eval.ipynb`.
5. When prompted to select a kernel, choose **Python 3**.
6. In the API key cell, paste your key between the quotes.
7. Run cells with **Shift+Enter** or use **Run All** from the top menu.

---

### Option 3 — VS Code locally

1. Open VS Code and go to **File → Open Folder**, select this folder.
2. Install the **Python** and **Jupyter** extensions if prompted (search "Jupyter" in the Extensions panel).
3. Open `Building_an_Eval.ipynb` and select your Python environment as the kernel when prompted.
4. Open a terminal in VS Code (**Terminal → New Terminal**) and set your API key:
   ```bash
   export ANTHROPIC_API_KEY=your_key_here
   ```
5. Run cells with **Shift+Enter** or click **Run All** at the top of the notebook.

---

### Option 4 — Jupyter locally

1. Install Jupyter if needed: `pip install notebook`
2. Open a terminal, navigate to this folder, and set your API key:
   ```bash
   export ANTHROPIC_API_KEY=your_key_here
   cd path/to/day2/01_evals
   jupyter notebook Building_an_Eval.ipynb
   ```
3. In the browser tab that opens, run cells with **Shift+Enter** or use **Cell → Run All**.
