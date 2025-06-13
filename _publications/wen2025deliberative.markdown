---
layout: publication
title: 'Thinkguard: Deliberative Slow Thinking Leads To Cautious Guardrails'
authors: Xiaofei Wen, Wenxuan Zhou, Wenjie Jacky Mo, Muhao Chen
conference: "Arxiv"
year: 2025
bibkey: wen2025deliberative
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.13458'}
tags: ['Interpretability and Explainability', 'RAG', 'Efficiency and Optimization', 'Applications', 'Reinforcement Learning', 'Responsible AI']
---
Ensuring the safety of large language models (LLMs) is critical as they are deployed in real-world applications. Existing guardrails rely on rule-based filtering or single-pass classification, limiting their ability to handle nuanced safety violations. To address this, we propose ThinkGuard, a critique-augmented guardrail model that distills knowledge from high-capacity LLMs by generating structured critiques alongside safety labels. Fine-tuned on critique-augmented data, the captured deliberative thinking ability drastically enhances the guardrail's cautiousness and interpretability. Evaluated on multiple safety benchmarks, ThinkGuard achieves the highest average F1 and AUPRC, outperforming all baselines. Compared to LLaMA Guard 3, ThinkGuard improves accuracy by 16.1% and macro F1 by 27.0%. Moreover, it surpasses label-only fine-tuned models, confirming that structured critiques enhance both classification precision and nuanced safety reasoning while maintaining computational efficiency.
