---
layout: publication
title: Tensor Train Low45;rank Approximation (tt45;lora) Democratizing AI With Accelerated Llms
authors: Anjum Afia, Eren Maksim E., Boureima Ismael, Alexandrov Boian, Bhattarai Manish
conference: "Arxiv"
year: 2024
bibkey: anjum2024tensor
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.01008"}
tags: ['Applications', 'Efficiency And Optimization', 'Fine Tuning', 'Quantization', 'Tools']
---
In recent years Large Language Models (LLMs) have demonstrated remarkable capabilities across a wide range of natural language processing (NLP) tasks such as question45;answering sentiment analysis text summarization and machine translation. However the ever45;growing complexity of LLMs demands immense computational resources hindering the broader research and application of these models. To address this various parameter45;efficient fine45;tuning strategies such as Low45;Rank Approximation (LoRA) and Adapters have been developed. Despite their potential these methods often face limitations in compressibility. Specifically LoRA struggles to scale effectively with the increasing number of trainable parameters in modern large scale LLMs. Additionally Low45;Rank Economic Tensor45;Train Adaptation (LoRETTA) which utilizes tensor train decomposition has not yet achieved the level of compression necessary for fine45;tuning very large scale models with limited resources. This paper introduces Tensor Train Low45;Rank Approximation (TT45;LoRA) a novel parameter45;efficient fine45;tuning (PEFT) approach that extends LoRETTA with optimized tensor train (TT) decomposition integration. By eliminating Adapters and traditional LoRA45;based structures TT45;LoRA achieves greater model compression without compromising downstream task performance along with reduced inference latency and computational overhead. We conduct an exhaustive parameter search to establish benchmarks that highlight the trade45;off between model compression and performance. Our results demonstrate significant compression of LLMs while maintaining comparable performance to larger models facilitating their deployment on resource45;constraint platforms.
