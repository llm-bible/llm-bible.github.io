---
layout: publication
title: 'Chinese-vicuna: A Chinese Instruction-following Llama-based Model'
authors: Chenghao Fan, Zhenyi Lu, Jie Tian
conference: "Arxiv"
year: 2025
bibkey: fan2025chinese
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.12737'}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Applications', 'Training Techniques', 'Fine-Tuning', 'Quantization', 'Reinforcement Learning', 'Pretraining Methods']
---
Chinese-Vicuna is an open-source, resource-efficient language model designed
to bridge the gap in Chinese instruction-following capabilities by fine-tuning
Meta's LLaMA architecture using Low-Rank Adaptation (LoRA). Targeting
low-resource environments, it enables cost-effective deployment on consumer
GPUs (e.g., RTX-2080Ti for 7B models) and supports domain-specific adaptation
in fields like healthcare and law. By integrating hybrid datasets (BELLE and
Guanaco) and 4-bit quantization (QLoRA), the model achieves competitive
performance in tasks such as translation, code generation, and domain-specific
Q\&A. The project provides a comprehensive toolkit for model conversion, CPU
inference, and multi-turn dialogue interfaces, emphasizing accessibility for
researchers and developers. Evaluations indicate competitive performance across
medical tasks, multi-turn dialogue coherence, and real-time legal updates.
Chinese-Vicuna's modular design, open-source ecosystem, and community-driven
enhancements position it as a versatile foundation for Chinese LLM
applications.
