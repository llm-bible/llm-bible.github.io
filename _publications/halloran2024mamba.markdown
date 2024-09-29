---
layout: publication
title: Mamba State45;space Models Can Be Strong Downstream Learners
authors: Halloran John T., Gulati Manbir, Roysdon Paul F.
conference: "Arxiv"
year: 2024
bibkey: halloran2024mamba
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.00209"}
tags: ['Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
Mamba state45;space models (SSMs) have recently outperformed state45;of45;the45;art (SOTA) Transformer large language models (LLMs) in various tasks and been widely adapted. However Mambas downstream learning capabilities remain either unexploredunicode123;x2013125;e.g. mixed45;precision (MPFT) and parameter45;efficient fine45;tuning (PEFT)45;45;or under45;evaluatedunicode123;x2013125;e.g. in45;context learning (ICL). For the latter recent works reported Mambas ICL rivals SOTA Transformer LLMs using non45;standard benchmarks. In contrast we show that on standard benchmarks pretrained Mamba models achieve only 3837; of the ICL performance improvements (over zero45;shot) of comparable Transformers. Enabling MPFT and PEFT in Mamba architectures is challenging due to recurrent dynamics and highly customized CUDA kernels respectively. However we prove that Mambas recurrent dynamics are robust to small input changes using dynamical systems theory. Empirically we show that performance changes in Mambas inference and fine45;tuning due to mixed45;precision align with Transformer LLMs. Furthermore we show that targeting key memory buffers in Mambas customized CUDA kernels for low45;rank adaptation regularizes SSM parameters thus achieving parameter efficiency while retaining speedups. We show that combining MPFT and PEFT enables up to 2.15 times more tokens45;per45;second and 65.537; reduced per45;token45;memory compared to full Mamba fine45;tuning while achieving up to 81.537; of the ICL performance improvements (over zero45;shot) of comparably fine45;tuned Transformers.
