---
layout: publication
title: 'Teaching Llms According To Their Aptitude: Adaptive Reasoning For Mathematical Problem Solving'
authors: Xin Xu, Yan Xu, Tianhao Chen, Yuchen Yan, Chengwu Liu, Zaoyu Chen, Yufei Wang, Yichun Yin, Yasheng Wang, Lifeng Shang, Qun Liu
conference: "Arxiv"
year: 2025
bibkey: xu2025teaching
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.12022"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Tools', 'Pretraining Methods', 'Fine-Tuning']
---
Existing approaches to mathematical reasoning with large language models
(LLMs) rely on Chain-of-Thought (CoT) for generalizability or Tool-Integrated
Reasoning (TIR) for precise computation. While efforts have been made to
combine these methods, they primarily rely on post-selection or predefined
strategies, leaving an open question: whether LLMs can autonomously adapt their
reasoning strategy based on their inherent capabilities. In this work, we
propose TATA (Teaching LLMs According to Their Aptitude), an adaptive framework
that enables LLMs to personalize their reasoning strategy spontaneously,
aligning it with their intrinsic aptitude. TATA incorporates base-LLM-aware
data selection during supervised fine-tuning (SFT) to tailor training data to
the model's unique abilities. This approach equips LLMs to autonomously
determine and apply the appropriate reasoning strategy at test time. We
evaluate TATA through extensive experiments on six mathematical reasoning
benchmarks, using both general-purpose and math-specialized LLMs. Empirical
results demonstrate that TATA effectively combines the complementary strengths
of CoT and TIR, achieving superior or comparable performance with improved
inference efficiency compared to TIR alone. Further analysis underscores the
critical role of aptitude-aware data selection in enabling LLMs to make
effective and adaptive reasoning decisions and align reasoning strategies with
model capabilities.
