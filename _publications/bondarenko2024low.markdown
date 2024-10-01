---
layout: publication
title: 'Low-rank Quantization-aware Training For Llms'
authors: Bondarenko Yelysei, Del Chiaro Riccardo, Nagel Markus
conference: "Arxiv"
year: 2024
bibkey: bondarenko2024low
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.06385"}
  - {name: "Code", url: "https://github.com/qualcomm-ai-research/LR-QAT"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'Has Code', 'Pretraining Methods', 'Quantization', 'Tools', 'Training Techniques']
---
Large language models (LLMs) are omnipresent, however their practical deployment is challenging due to their ever increasing computational and memory demands. Quantization is one of the most effective ways to make them more compute and memory efficient. Quantization-aware training (QAT) methods, generally produce the best quantized performance, however it comes at the cost of potentially long training time and excessive memory usage, making it impractical when applying for LLMs. Inspired by parameter-efficient fine-tuning (PEFT) and low-rank adaptation (LoRA) literature, we propose LR-QAT -- a lightweight and memory-efficient QAT algorithm for LLMs. LR-QAT employs several components to save memory without sacrificing predictive performance: (a) low-rank auxiliary weights that are aware of the quantization grid; (b) a downcasting operator using fixed-point or double-packed integers and (c) checkpointing. Unlike most related work, our method (i) is inference-efficient, leading to no additional overhead compared to traditional PTQ; (ii) can be seen as a general extended pretraining framework, meaning that the resulting model can still be utilized for any downstream task afterwards; (iii) can be applied across a wide range of quantization settings, such as different choices quantization granularity, activation quantization, and seamlessly combined with many PTQ techniques. We apply LR-QAT to LLaMA-1/2/3 and Mistral model families and validate its effectiveness on several downstream tasks. Our method outperforms common post-training quantization (PTQ) approaches and reaches the same model performance as full-model QAT at the fraction of its memory usage. Specifically, we can train a 7B LLM on a single consumer grade GPU with 24GB of memory. Our source code is available at https://github.com/qualcomm-ai-research/LR-QAT
