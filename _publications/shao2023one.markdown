---
layout: publication
title: 'One-shot Sensitivity-aware Mixed Sparsity Pruning For Large Language Models'
authors: Hang Shao, Bei Liu, Bo Xiao, Ke Zeng, Guanglu Wan, Yanmin Qian
conference: "Arxiv"
year: 2023
bibkey: shao2023one
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.09499"}
tags: ['Transformer', 'Efficiency and Optimization', 'GPT', 'Applications', 'Model Architecture', 'Reinforcement Learning', 'Language Modeling', 'Pruning', 'Training Techniques', 'Pretraining Methods', 'Quantization']
---
Various Large Language Models~(LLMs) from the Generative Pretrained
Transformer(GPT) family have achieved outstanding performances in a wide range
of text generation tasks. However, the enormous model sizes have hindered their
practical use in real-world applications due to high inference latency.
Therefore, improving the efficiencies of LLMs through quantization, pruning,
and other means has been a key issue in LLM studies. In this work, we propose a
method based on Hessian sensitivity-aware mixed sparsity pruning to prune LLMs
to at least 50% sparsity without the need of any retraining. It allocates
sparsity adaptively based on sensitivity, allowing us to reduce pruning-induced
error while maintaining the overall sparsity level. The advantages of the
proposed method exhibit even more when the sparsity is extremely high.
Furthermore, our method is compatible with quantization, enabling further
compression of LLMs. We have released the available code.
