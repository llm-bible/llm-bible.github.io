---
layout: publication
title: 'Musc: Improving Complex Instruction Following With Multi-granularity Self-contrastive Training'
authors: Hui Huang, Jiaheng Liu, Yancheng He, Shilong Li, Bing Xu, Conghui Zhu, Muyun Yang, Tiejun Zhao
conference: "Arxiv"
year: 2025
bibkey: huang2025improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.11541"}
tags: ['Tools', 'GPT', 'Efficiency and Optimization', 'Model Architecture', 'Training Techniques']
---
Complex instruction-following with elaborate constraints is imperative for Large Language Models (LLMs). While existing methods have constructed data for complex instruction alignment, they all rely on a more advanced model, especially GPT-4, limiting their application. In this paper, we propose a Multi-granularity Self-Contrastive Training (MuSC) framework, to improve the complex instruction alignment without relying on a stronger model. Our method is conducted on both coarse and fine granularity. On coarse-granularity, we construct constraint-aware preference data based on instruction decomposition and recombination. On fine-granularity, we perform token-aware preference optimization with dynamic token-level supervision. Our method is evaluated on open-sourced models, and experiment results show our method achieves significant improvement on both complex and general instruction-following benchmarks, surpassing previous self-alignment methods.
