# Inference Optimization · Build-Along

## What you're doing
A hands-on lab benchmarking Claude models across the key metrics that matter in production: time to first token (TTFT), time to completion (TTC), output tokens per second (OTPS), and cost. You'll then explore how prompt caching and tool use affect those numbers.

## Main learning
How to measure and optimize inference for real deployments. You'll compare Haiku, Sonnet, and Opus across speed and cost, see the impact of prompt caching on latency and spend, and instrument an agentic loop to understand where time actually goes.

---

## How to run

### Option 1 — VS Code (recommended)

1. Open VS Code and go to **File → Open Folder**, select this folder.
2. Install the **Python** and **Jupyter** extensions if prompted (search "Jupyter" in the Extensions panel).
3. Open `Inference_Optimization.ipynb`. VS Code will ask you to select a kernel — choose your Python environment.
4. Set your API key. Open a terminal in VS Code (**Terminal → New Terminal**) and run:
   ```bash
   export ANTHROPIC_API_KEY=your_key_here
   ```
5. Run cells using the **▶ Run All** button at the top, or run them one at a time with **Shift+Enter**.

> Prefer a plain Python script? Open `Inference_Optimization.py` instead, set your API key as above, then run:
> ```bash
> python Inference_Optimization.py
> ```

---

### Option 2 — Jupyter locally

1. Make sure Jupyter is installed. If not:
   ```bash
   pip install notebook
   ```
2. Open a terminal, navigate to this folder:
   ```bash
   cd path/to/day2/02_inference-optimization
   ```
3. Set your API key:
   ```bash
   export ANTHROPIC_API_KEY=your_key_here
   ```
4. Launch Jupyter:
   ```bash
   jupyter notebook Inference_Optimization.ipynb
   ```
5. In the browser tab that opens, run cells with **Shift+Enter** or use **Cell → Run All**.

---

### Option 3 — Google Colab

1. Go to [colab.research.google.com](https://colab.research.google.com).
2. Click **File → Upload notebook** and select `Inference_Optimization.ipynb`.
3. Paste your Anthropic API key into the setup cell near the top of the notebook.
4. Click **Runtime → Run all**.
