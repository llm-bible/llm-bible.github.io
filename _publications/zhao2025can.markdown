---
layout: publication
title: 'Can Pruning Improve Reasoning? Revisiting Long-cot Compression With Capability In Mind For Better Reasoning'
authors: Shangziqi Zhao, Jiahao Yuan, Guisong Yang, Usman Naseem
conference: "Arxiv"
year: 2025
bibkey: zhao2025can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.14582"}
tags: ['Fine-Tuning', 'Tools', 'Efficiency and Optimization', 'Pruning', 'Training Techniques', 'Pretraining Methods', 'Distillation']
---
Long chain-of-thought (Long-CoT) reasoning improves accuracy in LLMs, yet its verbose, self-reflective style often hinders effective distillation into small language models (SLMs). We revisit Long-CoT compression through the lens of capability alignment and ask: Can pruning improve reasoning? We propose Prune-on-Logic, a structure-aware framework that transforms Long-CoT into logic graphs and selectively prunes low-utility reasoning steps under self-verification constraints. Through systematic analysis across three pruning strategies -- targeting entire chains, core reasoning, and verification -- we find that pruning verification steps yields consistent accuracy gains while reducing inference cost, outperforming token-level baselines and uncompressed fine-tuning. In contrast, pruning reasoning or all-chain steps degrades performance, revealing that small models benefit not from shorter CoTs, but from semantically leaner ones. Our findings highlight pruning as a structural optimization strategy for aligning CoT reasoning with SLM capacity.
