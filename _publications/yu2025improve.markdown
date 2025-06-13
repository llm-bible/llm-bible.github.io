---
layout: publication
title: 'Improve Llm-as-a-judge Ability As A General Ability'
authors: Jiachen Yu, Shaoning Sun, Xiaohui Hu, Jiaxu Yan, Kaidong Yu, Xuelong Li
conference: "Arxiv"
year: 2025
bibkey: yu2025improve
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.11689"}
tags: ['Fine-Tuning', 'Efficiency and Optimization', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
LLM-as-a-Judge leverages the generative and reasoning capabilities of large
language models (LLMs) to evaluate LLM responses across diverse scenarios,
providing accurate preference signals. This approach plays a vital role in
aligning LLMs with human values, ensuring ethical and reliable AI outputs that
align with societal norms. Recent studies have raised many methods to train LLM
as generative judges, but most of them are data consuming or lack accuracy, and
only focus on LLM's judge ability. In this work, we regard judge ability as a
general ability of LLM and implement a two-stage training approach, comprising
supervised fine-tuning (SFT) warm-up and direct preference optimization (DPO)
enhancement, to achieve judge style adaptation and improve judgment accuracy.
Additionally, we introduce an efficient data synthesis method to generate
judgmental content. Experimental results demonstrate that our approach,
utilizing only about 2% to 40% of the data required by other methods, achieves
SOTA performance on RewardBench. Furthermore, our training method enhances the
general capabilities of the model by constructing complicated judge task, and
the judge signals provided by our model have significantly enhanced the
downstream DPO training performance of our internal models in our test to
optimize policy model with Judge Model. We also open-source our model weights
and training data to facilitate further research.
