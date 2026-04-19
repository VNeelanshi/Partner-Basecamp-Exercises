# Developer Platform · Build-Along

## What you're building
A multi-tool support ticket agent for TechFlow, a B2B SaaS company processing 500+ tickets per day. The agent reads ticket details, searches a knowledge base, and produces a structured resolution — using the Claude API directly with no framework.

## Main learning
How to build an agentic loop with tool use using the Claude API. You'll define tool schemas, handle multi-step tool calls, and use Claude Sonnet 4.6's adaptive thinking to let the model reason through complex ticket triage automatically.

---

## How to run

### Option 1 — VS Code (recommended)

1. Open VS Code and go to **File → Open Folder**, select this folder.
2. Install the **Python** and **Jupyter** extensions if prompted (search "Jupyter" in the Extensions panel).
3. Open `Developer_Platform.ipynb`. VS Code will ask you to select a kernel — choose your Python environment.
4. Set your API key. Open a terminal in VS Code (**Terminal → New Terminal**) and run:
   ```bash
   export ANTHROPIC_API_KEY=your_key_here
   ```
5. Run cells using the **▶ Run All** button at the top, or run them one at a time with **Shift+Enter**.

> Prefer a plain Python script? Open `Developer_Platform.py` instead, set your API key as above, then run:
> ```bash
> python Developer_Platform.py
> ```

---

### Option 2 — Jupyter locally

1. Make sure Jupyter is installed. If not:
   ```bash
   pip install notebook
   ```
2. Open a terminal, navigate to this folder:
   ```bash
   cd path/to/day1/01_developer-platform
   ```
3. Set your API key:
   ```bash
   export ANTHROPIC_API_KEY=your_key_here
   ```
4. Launch Jupyter:
   ```bash
   jupyter notebook Developer_Platform.ipynb
   ```
5. In the browser tab that opens, run cells with **Shift+Enter** or use **Cell → Run All**.

---

### Option 3 — Google Colab

1. Go to [colab.research.google.com](https://colab.research.google.com).
2. Click **File → Upload notebook** and select `Developer_Platform.ipynb`.
3. Set your API key using Colab Secrets: click the **🔑 key icon** in the left sidebar, add a secret named `ANTHROPIC_API_KEY`, and paste your key.
4. Click **Runtime → Run all**.
