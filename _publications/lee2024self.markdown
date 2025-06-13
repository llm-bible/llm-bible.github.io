---
layout: publication
title: 'Self-training Meets Consistency: Improving Llms'' Reasoning With Consistency-driven Rationale Evaluation'
authors: Jaehyeok Lee, Keisuke Sakaguchi, Jinyeong Bak
conference: "Arxiv"
year: 2024
bibkey: lee2024self
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.06387'}
tags: ['RAG', 'Security', 'Training Techniques', 'Tools']
---
Self-training approach for large language models (LLMs) improves reasoning
abilities by training the models on their self-generated rationales. Previous
approaches have labeled rationales that produce correct answers for a given
question as appropriate for training. However, a single measure risks
misjudging rationale quality, leading the models to learn flawed reasoning
patterns. To address this issue, we propose CREST (Consistency-driven Rationale
Evaluation for Self-Training), a self-training framework that further evaluates
each rationale through follow-up questions and leverages this evaluation to
guide its training. Specifically, we introduce two methods: (1) filtering out
rationales that frequently result in incorrect answers on follow-up questions
and (2) preference learning based on mixed preferences from rationale
evaluation results of both original and follow-up questions. Experiments on
three question-answering datasets using open LLMs show that CREST not only
improves the logical robustness and correctness of rationales but also improves
reasoning abilities compared to previous self-training approaches.
