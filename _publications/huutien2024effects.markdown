---
layout: publication
title: 'On Effects Of Steering Latent Representation For Large Language Model Unlearning'
authors: Dang Huu-tien, Trung-tin Pham, Hoang Thanh-tung, Naoya Inoue
conference: "Arxiv"
year: 2024
bibkey: huutien2024effects
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.06223"}
tags: ['Interpretability and Explainability', 'Security', 'Reinforcement Learning']
---
Representation Misdirection for Unlearning (RMU), which steers model
representation in the intermediate layer to a target random representation, is
an effective method for large language model (LLM) unlearning. Despite its high
performance, the underlying cause and explanation remain underexplored. In this
paper, we theoretically demonstrate that steering forget representations in the
intermediate layer reduces token confidence, causing LLMs to generate wrong or
nonsense responses. We investigate how the coefficient influences the alignment
of forget-sample representations with the random direction and hint at the
optimal coefficient values for effective unlearning across different network
layers. We show that RMU unlearned models are robust against adversarial
jailbreak attacks. Furthermore, our empirical analysis shows that RMU is less
effective when applied to the middle and later layers in LLMs. To resolve this
drawback, we propose Adaptive RMU--a simple yet effective alternative method
that makes unlearning effective with most layers. Extensive experiments
demonstrate that Adaptive RMU significantly improves the unlearning performance
compared to prior art while incurring no additional computational cost.
