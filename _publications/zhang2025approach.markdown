---
layout: publication
title: 'Cllora: An Approach To Measure The Effects Of The Context Length For LLM Fine-tuning'
authors: Ping Zhang, Zhaorui Zhang, Sheng Di, Yao Xin, Benben Liu
conference: "Arxiv"
year: 2025
bibkey: zhang2025approach
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.18910"}
tags: ['Fine-Tuning', 'Training Techniques', 'Pretraining Methods']
---
Large language model fine-tuning has been identified as an efficient approach
to applying the pre-trained Large language models to other domains. To
guarantee data privacy for different data owners, models are often fine-tuned
in federated learning environments across different data owners, which often
involve data heterogeneity issues and affect the fine-tuning performance. In
addition, the length of the context for the training data has been identified
as a major factor that affects the LLM's model performance.
  To efficiently measure how the context length affects the LLM's model
performance in heterogeneous federated learning environments, we propose
CLLoRA. CLLoRA utilizes the parameter-efficient fine-tuning approach LoRA based
on different kinds of LLMs with varying sizes as the fine-tuning approach to
investigate whether the quality and length of contexts can serve as standards
for measuring non-IID context. The findings indicate that an imbalance in
context quality not only affects local training on clients but also impacts the
global model's performance. However, context length has a minimal effect on
local training but a more significant influence on the global model. These
results provide insights into how context quality and length affect the model
performance for LLM fine-tuning in federated learning environments.
