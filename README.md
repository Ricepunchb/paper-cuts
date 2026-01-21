# Paper Cuts

> **"Bleeding on the bleeding edge of AI."**

![Python](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-Latest-ee4c2c?logo=pytorch&logoColor=white)
![Status](https://img.shields.io/badge/Status-Experimental-yellow)

## About This Repo

Welcome to **Paper Cuts**. This is my personal sandbox for scratching the itch of curiosity.

When I read a new paper (SOTA or otherwise) and think, *"Wait, does this actually work simply?"* or *"How would this behave on a smaller scale?"*, I write code here.

Unlike polished libraries, this repository contains **raw, standalone experiments**. It represents the painful yet satisfying process of turning complex math into running code—one paper cut at a time.

## What's Inside?

You'll find lightweight implementations, reproduction scripts, and "sanity checks" for various AI/ML topics. The code is organized by **topic** and **paper/keyword**.

<!-- 
* **Pruning & Sparsity:** Testing structured/unstructured pruning methods (Wanda, SparseGPT, etc.).
* **Quantization:** Experiments with low-bit precision (AWQ, BitNet) and custom kernels.
* **SLM (Small Language Models):** Probing capabilities of smaller models like Qwen, Phi, or DeepSeek-R1 distillations.
* **Mechanistic Interpretability:** Poking around attention heads and activations.
 -->
 
## Directory Structure

Navigation is simple. Pick a topic, then pick a paper/method.

<!--
```text
paper-cuts/
├── 📂 pruning/           # Cutting weights, keeping sanity
│   ├── 2025_wanda_ex/    # Implementation of Wanda pruning
│   └── ...
├── 📂 quantization/      # How low can we go?
│   ├── awq_activation/   # Activation-aware quantization tests
│   └── ...
├── 📂 slm/               # Small models, big dreams
│   ├── deepseek_r1/      # Inference tests for distilled models
│   └── ...
└── requirements.txt      # General dependencies
-->
