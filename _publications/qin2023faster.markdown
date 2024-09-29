---
layout: publication
title: "Transnormerllm: A Faster And Better Large Language Model With Improved Transnormer"
authors: Qin Zhen, Li Dong, Sun Weigao, Sun Weixuan, Shen Xuyang, Han Xiaodong, Wei Yunshen, Lv Baohong, Luo Xiao, Qiao Yu, Zhong Yiran
conference: "Arxiv"
year: 2023
bibkey: qin2023faster
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.14995"}
  - {name: "Code", url: "https://github.com/OpenNLPLab/TransnormerLLM"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
We present TransNormerLLM the first linear attention-based Large Language Model (LLM) that outperforms conventional softmax attention-based models in terms of both accuracy and efficiency. TransNormerLLM evolves from the previous linear attention architecture TransNormer by making advanced modifications that include positional embedding linear attention acceleration gating mechanisms tensor normalization and inference acceleration and stabilization. Specifically we use LRPE together with an exponential decay to avoid attention dilution issues while allowing the model to retain global interactions between tokens. Additionally we propose Lightning Attention a cutting-edge technique that accelerates linear attention by more than twice in runtime and reduces memory usage by a remarkable four times. To further enhance the performance of TransNormer we leverage a gating mechanism for smooth training and a new tensor normalization scheme to accelerate the model resulting in an impressive acceleration of over 2037;. Furthermore we develop a robust inference algorithm that ensures numerical stability and consistent inference speed regardless of the sequence length showcasing superior efficiency during both training and inference stages. We also implement an efficient model parallel schema for TransNormerLLM enabling seamless deployment on large-scale clusters and facilitating expansion to even more extensive models i.e. LLMs with 175B parameters. We validate our model design through a series of ablations and train models with sizes of 385M 1B and 7B on our self-collected corpus. Benchmark results demonstrate that our models not only match the performance of state-of-the-art LLMs with Transformer but are also significantly faster. Code is released at https://github.com/OpenNLPLab/TransnormerLLM."
