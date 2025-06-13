---
layout: publication
title: 'Disentangling Length Bias In Preference Learning Via Response-conditioned Modeling'
authors: Jianfeng Cai, Jinhua Zhu, Ruopei Sun, Yue Wang, Li Li, Wengang Zhou, Houqiang Li
conference: "Arxiv"
year: 2025
bibkey: cai2025disentangling
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.00814'}
tags: ['Agentic', 'RAG', 'Efficiency and Optimization', 'Training Techniques', 'Tools', 'Merging', 'Reinforcement Learning', 'Ethics and Bias']
---
Reinforcement Learning from Human Feedback (RLHF) has achieved considerable success in aligning large language models (LLMs) by modeling human preferences with a learnable reward model and employing a reinforcement learning algorithm to maximize the reward model's scores. However, these reward models are susceptible to exploitation through various superficial confounding factors, with length bias emerging as a particularly significant concern. Moreover, while the pronounced impact of length bias on preference modeling suggests that LLMs possess an inherent sensitivity to length perception, our preliminary investigations reveal that fine-tuned LLMs consistently struggle to adhere to explicit length instructions. To address these two limitations, we propose a novel framework wherein the reward model explicitly differentiates between human semantic preferences and response length requirements. Specifically, we introduce a \\(\textbf\{R\}\\)esponse-\\(\textbf\{c\}\\)onditioned \\(\textbf\{B\}\\)radley-\\(\textbf\{T\}\\)erry (Rc-BT) model that enhances the model's capability in length bias mitigating and length instruction following, through training on our augmented dataset. Furthermore, we propose the Rc-RM and Rc-DPO algorithm to leverage the Rc-BT model for reward modeling and direct policy optimization (DPO) of LLMs, simultaneously mitigating length bias and promoting adherence to length instructions. Extensive experiments across various foundational models and datasets demonstrate the effectiveness and generalizability of our approach.
