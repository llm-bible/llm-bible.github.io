---
layout: publication
title: 'Make Some Noise: Towards LLM Audio Reasoning And Generation Using Sound Tokens'
authors: Shivam Mehta, Nebojsa Jojic, Hannes Gamper
conference: "Arxiv"
year: 2025
bibkey: mehta2025make
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.22275"}
tags: ['Efficiency and Optimization', 'Multimodal Models', 'Tokenization', 'Quantization', 'Fine-Tuning']
---
Integrating audio comprehension and generation into large language models
(LLMs) remains challenging due to the continuous nature of audio and the
resulting high sampling rates. Here, we introduce a novel approach that
combines Variational Quantization with Conditional Flow Matching to convert
audio into ultra-low bitrate discrete tokens of 0.23kpbs, allowing for seamless
integration with text tokens in LLMs. We fine-tuned a pretrained text-based LLM
using Low-Rank Adaptation (LoRA) to assess its effectiveness in achieving true
multimodal capabilities, i.e., audio comprehension and generation. Our
tokenizer outperforms a traditional VQ-VAE across various datasets with diverse
acoustic events. Despite the substantial loss of fine-grained details through
audio tokenization, our multimodal LLM trained with discrete tokens achieves
competitive results in audio comprehension with state-of-the-art methods,
though audio generation is poor. Our results highlight the need for larger,
more diverse datasets and improved evaluation metrics to advance multimodal LLM
performance.
