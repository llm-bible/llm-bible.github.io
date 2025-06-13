---
layout: publication
title: 'Cot2align: Cross-chain Of Thought Distillation Via Optimal Transport Alignment For Language Models With Different Tokenizers'
authors: Anh Duc Le, Tu Vu, Nam Le Hai, Nguyen Thi Ngoc Diep, Linh Ngo Van, Trung Le, Thien Huu Nguyen
conference: "Arxiv"
year: 2025
bibkey: le2025cross
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.16806'}
tags: ['Efficiency and Optimization', 'Distillation', 'Security', 'Tools', 'Reinforcement Learning']
---
Large Language Models (LLMs) achieve state-of-the-art performance across
various NLP tasks but face deployment challenges due to high computational
costs and memory constraints. Knowledge distillation (KD) is a promising
solution, transferring knowledge from large teacher models to smaller student
models. However, existing KD methods often assume shared vocabularies and
tokenizers, limiting their flexibility. While approaches like Universal Logit
Distillation (ULD) and Dual-Space Knowledge Distillation (DSKD) address
vocabulary mismatches, they overlook the critical \textbf\{reasoning-aware
distillation\} aspect. To bridge this gap, we propose CoT2Align a universal KD
framework that integrates Chain-of-Thought (CoT) augmentation and introduces
Cross-CoT Alignment to enhance reasoning transfer. Additionally, we extend
Optimal Transport beyond token-wise alignment to a sequence-level and
layer-wise alignment approach that adapts to varying sequence lengths while
preserving contextual integrity. Comprehensive experiments demonstrate that
CoT2Align outperforms existing KD methods across different vocabulary settings,
improving reasoning capabilities and robustness in domain-specific tasks.
