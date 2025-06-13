---
layout: publication
title: 'Normalized Narrow Jump To Conclusions: Normalized Narrow Shortcuts For Parameter Efficient Early Exit Transformer Prediction'
authors: Amrit Diggavi Seshadri
conference: "Arxiv"
year: 2024
bibkey: seshadri2024normalized
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.14091'}
tags: ['Transformer', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'Pretraining Methods']
---
With the size and cost of large transformer-based language models growing,
recently, there has been interest in shortcut casting of early transformer
hidden-representations to final-representations for cheaper model inference. In
particular, shortcutting pre-trained transformers with linear transformations
over early layers has been shown to improve precision in early inference.
However, for large language models, even this becomes computationally
expensive. In this work, we propose Narrow Jump to Conclusions (NJTC) and
Normalized Narrow Jump to Conclusions (N-NJTC) - parameter efficient
alternatives to standard linear shortcutting that reduces shortcut parameter
count by over 97%. We show that N-NJTC reliably outperforms Identity shortcuts
at early stages and offers stable precision from all transformer block levels
for GPT-2-XL, Phi3-Mini and Llama2-7B transformer models, demonstrating the
viability of more parameter efficient short-cutting approaches.
