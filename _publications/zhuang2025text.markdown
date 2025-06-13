---
layout: publication
title: 'Text Generation Beyond Discrete Token Sampling'
authors: Yufan Zhuang, Liyuan Liu, Chandan Singh, Jingbo Shang, Jianfeng Gao
conference: "Arxiv"
year: 2025
bibkey: zhuang2025text
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.14827'}
tags: ['Language Modeling', 'GPT', 'Applications', 'Training Techniques', 'Pretraining Methods']
---
In standard autoregressive generation, an LLM predicts the next-token distribution, samples a discrete token, and then discards the distribution, passing only the sampled token as new input. To preserve this distribution's rich information, we propose Mixture of Inputs (MoI), a training-free method for autoregressive generation. After generating a token following the standard paradigm, we construct a new input that blends the generated discrete token with the previously discarded token distribution. Specifically, we employ a Bayesian estimation method that treats the token distribution as the prior, the sampled token as the observation, and replaces the conventional one-hot vector with the continuous posterior expectation as the new model input. MoI allows the model to maintain a richer internal representation throughout the generation process, resulting in improved text quality and reasoning capabilities. On mathematical reasoning, code generation, and PhD-level QA tasks, MoI consistently improves performance across multiple models including QwQ-32B, Nemotron-Super-49B, Gemma-3-27B, and DAPO-Qwen-32B, with no additional training and negligible computational overhead.
