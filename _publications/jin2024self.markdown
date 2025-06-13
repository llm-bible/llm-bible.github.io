---
layout: publication
title: 'Self-selected Attention Span For Accelerating Large Language Model Inference'
authors: Tian Jin, Wanzin Yazar, Zifei Xu, Sayeh Sharify, Xin Wang
conference: "Arxiv"
year: 2024
bibkey: jin2024self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.09336"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'GPT', 'Pretraining Methods', 'Fine-Tuning', 'Applications', 'Attention Mechanism']
---
Large language models (LLMs) can solve challenging tasks. However, their
inference computation on modern GPUs is highly inefficient due to the
increasing number of tokens they must attend to as they generate new ones. To
address this inefficiency, we capitalize on LLMs' problem-solving capabilities
to optimize their own inference-time efficiency. We demonstrate with two
specific tasks: (a) evaluating complex arithmetic expressions and (b)
summarizing news articles. For both tasks, we create custom datasets to
fine-tune an LLM. The goal of fine-tuning is twofold: first, to make the LLM
learn to solve the evaluation or summarization task, and second, to train it to
identify the minimal attention spans required for each step of the task. As a
result, the fine-tuned model is able to convert these self-identified minimal
attention spans into sparse attention masks on-the-fly during inference. We
develop a custom CUDA kernel to take advantage of the reduced context to attend
to. We demonstrate that using this custom CUDA kernel improves the throughput
of LLM inference by 28%. Our work presents an end-to-end demonstration showing
that training LLMs to self-select their attention spans speeds up
autoregressive inference in solving real-world tasks.
