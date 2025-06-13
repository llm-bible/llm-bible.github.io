---
layout: publication
title: 'Scalable Multi-stage Influence Function For Large Language Models Via Eigenvalue-corrected Kronecker-factored Parameterization'
authors: Yuntai Bao, Xuhong Zhang, Tianyu Du, Xinkui Zhao, Jiang Zong, Hao Peng, Jianwei Yin
conference: "Arxiv"
year: 2025
bibkey: bao2025scalable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.05017"}
  - {name: "Code", url: "https://github.com/colored-dye/multi_stage_influence_function"}
tags: ['Fine-Tuning', 'Pre-Training', 'Efficiency and Optimization', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Has Code', 'Pretraining Methods']
---
Pre-trained large language models (LLMs) are commonly fine-tuned to adapt to
downstream tasks. Since the majority of knowledge is acquired during
pre-training, attributing the predictions of fine-tuned LLMs to their
pre-training data may provide valuable insights. Influence functions have been
proposed as a means to explain model predictions based on training data.
However, existing approaches fail to compute ``multi-stage'' influence and lack
scalability to billion-scale LLMs.
  In this paper, we propose the multi-stage influence function to attribute the
downstream predictions of fine-tuned LLMs to pre-training data under the
full-parameter fine-tuning paradigm. To enhance the efficiency and practicality
of our multi-stage influence function, we leverage Eigenvalue-corrected
Kronecker-Factored (EK-FAC) parameterization for efficient approximation.
Empirical results validate the superior scalability of EK-FAC approximation and
the effectiveness of our multi-stage influence function. Additionally, case
studies on a real-world LLM, dolly-v2-3b, demonstrate its interpretive power,
with exemplars illustrating insights provided by multi-stage influence
estimates. Our code is public at
https://github.com/colored-dye/multi_stage_influence_function.
