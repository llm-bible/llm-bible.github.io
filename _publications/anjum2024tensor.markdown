---
layout: publication
title: Tensor Train Low-rank Approximation (TT-LoRA) Democratizing AI with Accelerated LLMs
authors: Anjum Afia, Eren Maksim E., Boureima Ismael, Alexandrov Boian, Bhattarai Manish
conference: "Arxiv"
year: 2024
bibkey: anjum2024tensor
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.01008"}
tags: ['ARXIV', 'Applications', 'Efficiency And Optimization', 'Fine Tuning', 'LLM', 'NLP', 'Pretraining Methods', 'Quantization', 'Tools', 'Training Techniques']
---
In recent years Large Language Models (LLMs) have demonstrated remarkable capabilities across a wide range of natural language processing (NLP) tasks such as question-answering sentiment analysis text summarization and machine translation. However the ever-growing complexity of LLMs demands immense computational resources hindering the broader research and application of these models. To address this various parameter-efficient fine-tuning strategies such as Low-Rank Approximation (LoRA) and Adapters have been developed. Despite their potential these methods often face limitations in compressibility. Specifically LoRA struggles to scale effectively with the increasing number of trainable parameters in modern large scale LLMs. Additionally Low-Rank Economic Tensor-Train Adaptation (LoRETTA) which utilizes tensor train decomposition has not yet achieved the level of compression necessary for fine-tuning very large scale models with limited resources. This paper introduces Tensor Train Low-Rank Approximation (TT-LoRA) a novel parameter-efficient fine-tuning (PEFT) approach that extends LoRETTA with optimized tensor train (TT) decomposition integration. By eliminating Adapters and traditional LoRA-based structures TT-LoRA achieves greater model compression without compromising downstream task performance along with reduced inference latency and computational overhead. We conduct an exhaustive parameter search to establish benchmarks that highlight the trade-off between model compression and performance. Our results demonstrate significant compression of LLMs while maintaining comparable performance to larger models facilitating their deployment on resource-constraint platforms.
