---
layout: publication
title: 'Small Language Models In The Real World: Insights From Industrial Text Classification'
authors: Lujun Li, Lama Sleem, Niccolo' Gentile, Geoffrey Nichil, Radu State
conference: "Arxiv"
year: 2025
bibkey: li2025small
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.16078"}
tags: ['Fine-Tuning', 'Transformer', 'Efficiency and Optimization', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods', 'Prompting']
---
With the emergence of ChatGPT, Transformer models have significantly advanced text classification and related tasks. Decoder-only models such as Llama exhibit strong performance and flexibility, yet they suffer from inefficiency on inference due to token-by-token generation, and their effectiveness in text classification tasks heavily depends on prompt quality. Moreover, their substantial GPU resource requirements often limit widespread adoption. Thus, the question of whether smaller language models are capable of effectively handling text classification tasks emerges as a topic of significant interest. However, the selection of appropriate models and methodologies remains largely underexplored. In this paper, we conduct a comprehensive evaluation of prompt engineering and supervised fine-tuning methods for transformer-based text classification. Specifically, we focus on practical industrial scenarios, including email classification, legal document categorization, and the classification of extremely long academic texts. We examine the strengths and limitations of smaller models, with particular attention to both their performance and their efficiency in Video Random-Access Memory (VRAM) utilization, thereby providing valuable insights for the local deployment and application of compact models in industrial settings.
