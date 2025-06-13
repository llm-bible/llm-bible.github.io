---
layout: publication
title: 'Vision-language Models Can Self-improve Reasoning Via Reflection'
authors: Kanzhi Cheng, Yantao Li, Fangzhi Xu, Jianbing Zhang, Hao Zhou, Yang Liu
conference: "Arxiv"
year: 2024
bibkey: cheng2024vision
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.00855'}
tags: ['GPT', 'Model Architecture', 'Tools', 'Training Techniques', 'Multimodal Models', 'Reinforcement Learning']
---
Chain-of-thought (CoT) has proven to improve the reasoning capability of
large language models (LLMs). However, due to the complexity of multimodal
scenarios and the difficulty in collecting high-quality CoT data, CoT reasoning
in multimodal LLMs has been largely overlooked. To this end, we propose a
simple yet effective self-training framework, R3V, which iteratively enhances
the model's Vision-language Reasoning by Reflecting on CoT Rationales. Our
framework consists of two interleaved parts: (1) iteratively bootstrapping
positive and negative solutions for reasoning datasets, and (2) reflection on
rationale for learning from mistakes. Specifically, we introduce the
self-refine and self-select losses, enabling the model to refine flawed
rationale and derive the correct answer by comparing rationale candidates.
Experiments on a wide range of vision-language tasks show that R3V consistently
improves multimodal LLM reasoning, achieving a relative improvement of 23 to 60
percent over GPT-distilled baselines. Additionally, our approach supports
self-reflection on generated solutions, further boosting performance through
test-time computation.
