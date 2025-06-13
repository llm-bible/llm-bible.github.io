---
layout: publication
title: 'Lego-compiler: Enhancing Neural Compilation Through Translation Composability'
authors: Shuoming Zhang, Jiacheng Zhao, Chunwei Xia, Zheng Wang, Yunji Chen, Xiaobing Feng, Huimin Cui
conference: "Arxiv"
year: 2025
bibkey: zhang2025lego
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.20356"}
tags: ['RAG', 'Tools', 'Reinforcement Learning']
---
Large language models (LLMs) have the potential to revolutionize how we design and implement compilers and code translation tools. However, existing LLMs struggle to handle long and complex programs. We introduce LEGO-Compiler, a novel neural compilation system that leverages LLMs to translate high-level languages into assembly code. Our approach centers on three key innovations: LEGO translation, which decomposes the input program into manageable blocks; breaking down the complex compilation process into smaller, simpler verifiable steps by organizing it as a verifiable LLM workflow by external tests; and a feedback mechanism for self-correction. Supported by formal proofs of translation composability, LEGO-Compiler demonstrates high accuracy on multiple datasets, including over 99% on ExeBench and 97.9% on industrial-grade AnsiBench. Additionally, LEGO-Compiler has also acheived near one order-of-magnitude improvement on compilable code size scalability. This work opens new avenues for applying LLMs to system-level tasks, complementing traditional compiler technologies.
