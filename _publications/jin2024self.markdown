---
layout: publication
title: Self45;selected Attention Span For Accelerating Large Language Model Inference
authors: Jin Tian, Yazar Wanzin, Xu Zifei, Sharify Sayeh, Wang Xin
conference: "Arxiv"
year: 2024
bibkey: jin2024self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.09336"}
tags: ['Applications', 'Attention Mechanism', 'Efficiency And Optimization', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Large language models (LLMs) can solve challenging tasks. However their inference computation on modern GPUs is highly inefficient due to the increasing number of tokens they must attend to as they generate new ones. To address this inefficiency we capitalize on LLMs problem45;solving capabilities to optimize their own inference45;time efficiency. We demonstrate with two specific tasks (a) evaluating complex arithmetic expressions and (b) summarizing news articles. For both tasks we create custom datasets to fine45;tune an LLM. The goal of fine45;tuning is twofold first to make the LLM learn to solve the evaluation or summarization task and second to train it to identify the minimal attention spans required for each step of the task. As a result the fine45;tuned model is able to convert these self45;identified minimal attention spans into sparse attention masks on45;the45;fly during inference. We develop a custom CUDA kernel to take advantage of the reduced context to attend to. We demonstrate that using this custom CUDA kernel improves the throughput of LLM inference by 2837;. Our work presents an end45;to45;end demonstration showing that training LLMs to self45;select their attention spans speeds up autoregressive inference in solving real45;world tasks.
