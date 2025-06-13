---
layout: publication
title: 'Dense Training, Sparse Inference: Rethinking Training Of Mixture-of-experts Language Models'
authors: Bowen Pan, Yikang Shen, Haokun Liu, Mayank Mishra, Gaoyuan Zhang, Aude Oliva, Colin Raffel, Rameswar Panda
conference: "Arxiv"
year: 2024
bibkey: pan2024dense
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2404.05567'}
tags: ['Efficiency and Optimization', 'Training Techniques', 'GPT', 'Tools', 'Pretraining Methods']
---
Mixture-of-Experts (MoE) language models can reduce computational costs by
2-4\\(\times\\) compared to dense models without sacrificing performance, making
them more efficient in computation-bounded scenarios. However, MoE models
generally require 2-4\\(\times\\) times more parameters to achieve comparable
performance to a dense model, which incurs larger GPU memory requirements and
makes MoE models less efficient in I/O-bounded scenarios like autoregressive
generation. In this work, we propose a hybrid dense training and sparse
inference framework for MoE models (DS-MoE) which achieves strong computation
and parameter efficiency by employing dense computation across all experts
during training and sparse computation during inference. Our experiments on
training LLMs demonstrate that our DS-MoE models are more parameter-efficient
than standard sparse MoEs and are on par with dense models in terms of total
parameter size and performance while being computationally cheaper (activating
30-40% of the model's parameters). Performance tests using vLLM show that our
DS-MoE-6B model runs up to \\(1.86\times\\) faster than similar dense models like
Mistral-7B, and between \\(1.50\times\\) and \\(1.71\times\\) faster than comparable
MoEs, such as DeepSeekMoE-16B and Qwen1.5-MoE-A2.7B.
