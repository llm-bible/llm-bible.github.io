---
layout: publication
title: 'On Effects Of Steering Latent Representation For Large Language Model Unlearning'
authors: Huu-tien Dang, Pham Trung-tin, Thanh-tung Hoang, Inoue Naoya
conference: "Arxiv"
year: 2024
bibkey: huutien2024effects
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.06223"}
tags: ['Interpretability And Explainability', 'Reinforcement Learning', 'Security']
---
Representation Misdirection for Unlearning (RMU), which steers model
representation in the intermediate layer to a target random representation, is
an effective method for large language model (LLM) unlearning. Despite its high
performance, the underlying cause and explanation remain underexplored. In this
paper, we first theoretically demonstrate that steering forget representations
in the intermediate layer reduces token confidence, causing LLMs to generate
wrong or nonsense responses. Second, we investigate how the coefficient
influences the alignment of forget-sample representations with the random
direction and hint at the optimal coefficient values for effective unlearning
across different network layers. Third, we show that RMU unlearned models are
robust against adversarial jailbreak attacks. Last, our empirical analysis
shows that RMU is less effective when applied to the middle and later layers in
LLMs. To resolve this drawback, we propose Adaptive RMU -- a simple yet
effective alternative method that makes unlearning effective with most layers.
Extensive experiments demonstrate that Adaptive RMU significantly improves the
unlearning performance compared to prior art while incurring no additional
computational cost.
