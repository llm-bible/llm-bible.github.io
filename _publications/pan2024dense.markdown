---
layout: publication
title: Dense Training Sparse Inference Rethinking Training Of Mixture45;of45;experts Language Models
authors: Pan Bowen, Shen Yikang, Liu Haokun, Mishra Mayank, Zhang Gaoyuan, Oliva Aude, Raffel Colin, Panda Rameswar
conference: "Arxiv"
year: 2024
bibkey: pan2024dense
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.05567"}
tags: ['Efficiency And Optimization', 'GPT', 'Pretraining Methods', 'Tools', 'Training Techniques']
---
Mixture45;of45;Experts (MoE) language models can reduce computational costs by 245;4× compared to dense models without sacrificing performance making them more efficient in computation45;bounded scenarios. However MoE models generally require 245;4× times more parameters to achieve comparable performance to a dense model which incurs larger GPU memory requirements and makes MoE models less efficient in I/O45;bounded scenarios like autoregressive generation. In this work we propose a hybrid dense training and sparse inference framework for MoE models (DS45;MoE) which achieves strong computation and parameter efficiency by employing dense computation across all experts during training and sparse computation during inference. Our experiments on training LLMs demonstrate that our DS45;MoE models are more parameter45;efficient than standard sparse MoEs and are on par with dense models in terms of total parameter size and performance while being computationally cheaper (activating 3045;4037; of the models parameters). Performance tests using vLLM show that our DS45;MoE45;6B model runs up to 1.86× faster than similar dense models like Mistral45;7B and between 1.50× and 1.71× faster than comparable MoEs such as DeepSeekMoE45;16B and Qwen1.545;MoE45;A2.7B.
