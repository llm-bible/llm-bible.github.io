---
layout: publication
title: 'Mamba State-space Models Can Be Strong Downstream Learners'
authors: Halloran John T., Gulati Manbir, Roysdon Paul F.
conference: "Arxiv"
year: 2024
bibkey: halloran2024mamba
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.00209"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'In Context Learning', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Training Techniques', 'Transformer']
---
Mamba state-space models (SSMs) have recently outperformed state-of-the-art (SOTA) Transformer large language models (LLMs) in various tasks and been widely adapted. However Mambas downstream learning capabilities remain either unexplored()e.g. mixed-precision (MPFT) and parameter-efficient fine-tuning (PEFT)--or under-evaluated()e.g. in-context learning (ICL). For the latter recent works reported Mambas ICL rivals SOTA Transformer LLMs using non-standard benchmarks. In contrast we show that on standard benchmarks pretrained Mamba models achieve only 3837; of the ICL performance improvements (over zero-shot) of comparable Transformers. Enabling MPFT and PEFT in Mamba architectures is challenging due to recurrent dynamics and highly customized CUDA kernels respectively. However we prove that Mambas recurrent dynamics are robust to small input changes using dynamical systems theory. Empirically we show that performance changes in Mambas inference and fine-tuning due to mixed-precision align with Transformer LLMs. Furthermore we show that targeting key memory buffers in Mambas customized CUDA kernels for low-rank adaptation regularizes SSM parameters thus achieving parameter efficiency while retaining speedups. We show that combining MPFT and PEFT enables up to 2.15 times more tokens-per-second and 65.537; reduced per-token-memory compared to full Mamba fine-tuning while achieving up to 81.537; of the ICL performance improvements (over zero-shot) of comparably fine-tuned Transformers.
