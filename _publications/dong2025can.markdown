---
layout: publication
title: 'Can Compressed Llms Truly Act? An Empirical Evaluation Of Agentic Capabilities In LLM Compression'
authors: Peijie Dong, Zhenheng Tang, Xiang Liu, Lujun Li, Xiaowen Chu, Bo Li
conference: "Arxiv"
year: 2025
bibkey: dong2025can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.19433"}
  - {name: "Code", url: "https://github.com/pprp/ACBench"}
tags: ['Agentic', 'GPT', 'Efficiency and Optimization', 'Applications', 'Model Architecture', 'Reinforcement Learning', 'Language Modeling', 'Pruning', 'Training Techniques', 'Has Code', 'Quantization']
---
Post-training compression reduces the computational and memory costs of large language models (LLMs), enabling resource-efficient deployment. However, existing compression benchmarks only focus on language modeling (e.g., perplexity) and natural language understanding tasks (e.g., GLUE accuracy), ignoring the agentic capabilities - workflow, tool use/function call, long-context understanding and real-world application. We introduce the Agent Compression Benchmark (ACBench), the first comprehensive benchmark for evaluating how compression impacts LLMs' agentic abilities. ACBench spans (1) 12 tasks across 4 capabilities (e.g., WorfBench for workflow generation, Needle-in-Haystack for long-context retrieval), (2) quantization (GPTQ, AWQ) and pruning (Wanda, SparseGPT), and (3) 15 models, including small (Gemma-2B), standard (Qwen2.5 7B-32B), and distilled reasoning LLMs (DeepSeek-R1-Distill). Our experiments reveal compression tradeoffs: 4-bit quantization preserves workflow generation and tool use (1%-3% drop) but degrades real-world application accuracy by 10%-15%. We introduce ERank, Top-k Ranking Correlation and Energy to systematize analysis. ACBench provides actionable insights for optimizing LLM compression in agentic scenarios. The code can be found in https://github.com/pprp/ACBench.
