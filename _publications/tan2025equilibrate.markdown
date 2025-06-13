---
layout: publication
title: 'Equilibrate RLHF: Towards Balancing Helpfulness-safety Trade-off In Large Language Models'
authors: Yingshui Tan, Yilei Jiang, Yanshi Li, Jiaheng Liu, Xingyuan Bu, Wenbo Su, Xiangyu Yue, Xiaoyong Zhu, Bo Zheng
conference: "Arxiv"
year: 2025
bibkey: tan2025equilibrate
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.11555"}
tags: ['Responsible AI', 'Agentic', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning']
---
Fine-tuning large language models (LLMs) based on human preferences, commonly
achieved through reinforcement learning from human feedback (RLHF), has been
effective in improving their performance. However, maintaining LLM safety
throughout the fine-tuning process remains a significant challenge, as
resolving conflicts between safety and helpfulness can be non-trivial.
Typically, the safety alignment of LLM is trained on data with safety-related
categories. However, our experiments find that naively increasing the scale of
safety training data usually leads the LLMs to an ``overly safe'' state rather
than a ``truly safe'' state, boosting the refusal rate through extensive
safety-aligned data without genuinely understanding the requirements for safe
responses. Such an approach can inadvertently diminish the models' helpfulness.
To understand the phenomenon, we first investigate the role of safety data by
categorizing them into three different groups, and observe that each group
behaves differently as training data scales up. To boost the balance between
safety and helpfulness, we propose an Equilibrate RLHF framework including a
Fine-grained Data-centric (FDC) approach that achieves better safety alignment
even with fewer training data, and an Adaptive Message-wise Alignment (AMA)
approach, which selectively highlight the key segments through a gradient
masking strategy. Extensive experimental results demonstrate that our approach
significantly enhances the safety alignment of LLMs while balancing safety and
helpfulness.
