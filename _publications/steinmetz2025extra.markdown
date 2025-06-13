---
layout: publication
title: 'An Extra Rmsnorm Is All You Need For Fine Tuning To 1.58 Bits'
authors: Cody Steinmetz, Gavin Childress, Aaron Herbst, Gavin Jones, Jasdeep Singh, Eli Vang, Keagan Weinstock
conference: "Arxiv"
year: 2025
bibkey: steinmetz2025extra
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.08823"}
tags: ['Transformer', 'Efficiency and Optimization', 'Ethics and Bias', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods', 'Quantization', 'Distillation']
---
Large language models (LLMs) have transformed natural-language processing, yet their scale makes real-world deployment costly. Post-training quantization reduces memory and computation but often degrades accuracy, while quantization-aware training can recover performance at the cost of extra training. Pushing quantization to the ternary (2-bit) regime yields even larger savings but is notoriously unstable. Building on recent work showing that a bias-free, RMS-normalized Transformer with straight-through estimation can reach 1.58-bit precision, we demonstrate that simply inserting RMS normalization before every linear projection and applying a gradual, layer-wise quantization schedule stably fine-tunes full-precision checkpoints into ternary LLMs. Our approach matches or surpasses more elaborate knowledge-distillation pipelines on standard language-modeling benchmarks without adding model complexity. These results indicate that careful normalization alone can close much of the accuracy gap between ternary and full-precision LLMs, making ultra-low-bit inference practical.
