---
layout: publication
title: 'Bring Reason To Vision: Understanding Perception And Reasoning Through Model Merging'
authors: Shiqi Chen, Jinghan Zhang, Tongyao Zhu, Wei Liu, Siyang Gao, Miao Xiong, Manling Li, Junxian He
conference: "Arxiv"
year: 2025
bibkey: chen2025bring
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.05464'}
tags: ['Reinforcement Learning', 'Multimodal Models', 'Training Techniques', 'Merging']
---
Vision-Language Models (VLMs) combine visual perception with the general
capabilities, such as reasoning, of Large Language Models (LLMs). However, the
mechanisms by which these two abilities can be combined and contribute remain
poorly understood. In this work, we explore to compose perception and reasoning
through model merging that connects parameters of different models. Unlike
previous works that often focus on merging models of the same kind, we propose
merging models across modalities, enabling the incorporation of the reasoning
capabilities of LLMs into VLMs. Through extensive experiments, we demonstrate
that model merging offers a successful pathway to transfer reasoning abilities
from LLMs to VLMs in a training-free manner. Moreover, we utilize the merged
models to understand the internal mechanism of perception and reasoning and how
merging affects it. We find that perception capabilities are predominantly
encoded in the early layers of the model, whereas reasoning is largely
facilitated by the middle-to-late layers. After merging, we observe that all
layers begin to contribute to reasoning, whereas the distribution of perception
abilities across layers remains largely unchanged. These observations shed
light on the potential of model merging as a tool for multimodal integration
and interpretation.
