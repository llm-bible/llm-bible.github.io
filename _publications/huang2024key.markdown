---
layout: publication
title: 'Key-point-driven Data Synthesis With Its Enhancement On Mathematical Reasoning'
authors: Huang Yiming, Liu Xiao, Gong Yeyun, Gou Zhibin, Shen Yelong, Duan Nan, Chen Weizhu
conference: "Arxiv"
year: 2024
bibkey: huang2024key
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.02333"}
tags: ['GPT', 'Model Architecture', 'RAG', 'Tools', 'Training Techniques']
---
Large language models (LLMs) have shown great potential in complex reasoning
tasks, yet their performance is often hampered by the scarcity of high-quality
and reasoning-focused training datasets. Addressing this challenge, we propose
Key-Point-Driven Data Synthesis (KPDDS), a novel data synthesis framework that
synthesizes question-answer pairs by leveraging key points and exemplar
practices from authentic data sources. KPDDS ensures the generation of novel
questions with rigorous quality control and substantial scalability. As a
result, we present KPMath, an extensive synthetic dataset tailored for
mathematical reasoning, comprising over 800K question-answer pairs. Utilizing
KPMath and augmenting it with additional reasoning-intensive corpora, we create
the comprehensive KPMath-Plus dataset. The Qwen1.5-72B model, fine-tuned on
KPMath-Plus, achieves 87.0% PASS@1 accuracy on GSM8K and 58.3% on MATH,
surpassing competitors in the 7B to 70B range and best commercial models like
GPT-4 across multiple math reasoning datasets.
