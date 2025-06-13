---
layout: publication
title: 'Computational Reasoning Of Large Language Models'
authors: Haitao Wu, Zongbo Han, Joey Tianyi Zhou, Huaxi Huang, Changqing Zhang
conference: "Arxiv"
year: 2025
bibkey: wu2025computational
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.20771"}
  - {name: "Code", url: "https://github.com/HaitaoWuTJU/Turing-Machine-Bench}{Repo"}
tags: ['Tools', 'Has Code', 'Reinforcement Learning']
---
With the rapid development and widespread application of Large Language Models (LLMs), multidimensional evaluation has become increasingly critical. However, current evaluations are often domain-specific and overly complex, limiting their effectiveness as cross-domain proxies for core capabilities. To address these limitations and enable a unified and simple evaluation framework, an ideal proxy task should target a basic capability that generalizes across tasks and is independent of domain-specific knowledge. Turing machine provides a powerful theoretical lens by reducing complex processes to basic, domain-agnostic computational operations. This perspective offers a principled framework for evaluating basic computational abilities essential to a wide range of tasks. Motivated by this abstraction, we introduce \textbf\{Turing Machine Bench\}, a benchmark designed to assess the ability of LLMs to \textbf\{strictly follow rules\} and \textbf\{accurately manage internal states\} for multi-step, referred to as \textbf\{computational reasoning\}. TMBench incorporates four key features: self-contained and knowledge-agnostic reasoning, a minimalistic multi-step structure, controllable difficulty, and a solid theoretical foundation based on Turing machine. Empirical results demonstrate that TMBench serves as an effective proxy for evaluating computational reasoning on representative LLMs. It produces clear step-wise accuracy curves, revealing LLMs' ability to execute multi-step reasoning processes. By analyzing performance trends across TMBench and established reasoning benchmarks, we find strong correlations with real-world tasks, bridging real-task evaluation with basic ability assessment. These findings suggest that TMBench holds potential as a cross-domain dimension for evaluating reasoning in LLMs. Code and data are available at \href\{https://github.com/HaitaoWuTJU/Turing-Machine-Bench\}\{Repo\}.
