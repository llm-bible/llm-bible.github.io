---
layout: publication
title: 'Balancing Truthfulness And Informativeness With Uncertainty-aware Instruction Fine-tuning'
authors: Tianyi Wu, Jingwei Ni, Bryan Hooi, Jiaheng Zhang, Elliott Ash, See-kiong Ng, Mrinmaya Sachan, Markus Leippold
conference: "Arxiv"
year: 2025
bibkey: wu2025balancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.11962"}
tags: ['Pretraining Methods', 'Training Techniques', 'Pre-Training', 'Fine-Tuning']
---
Instruction fine-tuning (IFT) can increase the informativeness of large language models (LLMs), but may reduce their truthfulness. This trade-off arises because IFT steers LLMs to generate responses containing long-tail knowledge that was not well covered during pre-training. As a result, models become more informative but less accurate when generalizing to unseen tasks. In this paper, we empirically demonstrate how unfamiliar knowledge in IFT datasets can negatively affect the truthfulness of LLMs, and we introduce two new IFT paradigms, \\(UNIT_\{cut\}\\) and \\(UNIT_\{ref\}\\), to address this issue. \\(UNIT_\{cut\}\\) identifies and removes unfamiliar knowledge from IFT datasets to mitigate its impact on model truthfulness, whereas \\(UNIT_\{ref\}\\) trains LLMs to recognize their uncertainty and explicitly indicate it at the end of their responses. Our experiments show that \\(UNIT_\{cut\}\\) substantially improves LLM truthfulness, while \\(UNIT_\{ref\}\\) maintains high informativeness and reduces hallucinations by distinguishing between confident and uncertain statements.
