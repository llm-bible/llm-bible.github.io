---
layout: publication
title: 'Reassessing Layer Pruning In Llms: New Insights And Methods'
authors: Yao Lu, Hao Cheng, Yujie Fang, Zeyu Wang, Jiaheng Wei, Dongwei Xu, Qi Xuan, Xiaoniu Yang, Zhaowei Zhu
conference: "Arxiv"
year: 2024
bibkey: lu2024reassessing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.15558"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Pruning', 'Pretraining Methods', 'Fine-Tuning']
---
Although large language models (LLMs) have achieved remarkable success across
various domains, their considerable scale necessitates substantial
computational resources, posing significant challenges for deployment in
resource-constrained environments. Layer pruning, as a simple yet effective
compression method, removes layers of a model directly, reducing computational
overhead. However, what are the best practices for layer pruning in LLMs? Are
sophisticated layer selection metrics truly effective? Does the LoRA (Low-Rank
Approximation) family, widely regarded as a leading method for pruned model
fine-tuning, truly meet expectations when applied to post-pruning fine-tuning?
To answer these questions, we dedicate thousands of GPU hours to benchmarking
layer pruning in LLMs and gaining insights across multiple dimensions. Our
results demonstrate that a simple approach, i.e., pruning the final 25% of
layers followed by fine-tuning the \texttt\{lm\_head\} and the remaining last
three layer, yields remarkably strong performance. Following this guide, we
prune Llama-3.1-8B-It and obtain a model that outperforms many popular LLMs of
similar size, such as ChatGLM2-6B, Vicuna-7B-v1.5, Qwen1.5-7B and Baichuan2-7B.
We release the optimal model weights on Huggingface, and the code is available
on GitHub.
