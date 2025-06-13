---
layout: publication
title: 'Examples As The Prompt: A Scalable Approach For Efficient LLM Adaptation In E-commerce'
authors: Jingying Zeng, Zhenwei Dai, Hui Liu, Samarth Varshney, Zhiji Liu, Chen Luo, Zhen Li, Qi He, Xianfeng Tang
conference: "Arxiv"
year: 2025
bibkey: zeng2025examples
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.13518'}
tags: ['Few-Shot', 'RAG', 'Applications', 'Training Techniques', 'Tools', 'Prompting', 'RecSys', 'Reinforcement Learning', 'Ethics and Bias']
---
Prompting LLMs offers an efficient way to guide output generation without
explicit model training. In the e-commerce domain, prompting-based applications
are widely used for tasks such as query understanding, recommender systems, and
customer support. However, adapting LLMs to different tasks often requires
extensive prompt engineering by domain experts, along with frequent updates to
align with evolving business needs. Additionally, crafting fully unbiased
natural language prompts remains a challenge for humans. To address these
challenges, we propose a novel framework, Examples as the Prompt (EaP) which
leverages labeled data to enhance prompts. Specifically, EaP automatically
selects the most representative examples to maximize the few-shot capability of
LLMs. It is efficient due to its unsupervised example selection and adaptive to
potential data distribution shifts. We validate EaP on four real-world
production use cases, demonstrating that it achieves comparable or even
superior performance comparing to hand-crafted prompts designed by domain
experts. Additionally, we introduce EaP_lite, which entirely replaces the
natural language components of prompts with labeled examples. EaP_lite improves
LLM inference speed by up to 70% without compromising performance. Latest
online A/B test shows that using EaP and EaP_lite for data labeling can bring
significant composite revenue gain by 0.06%.
