---
layout: publication
title: "Hydralora: An Asymmetric Lora Architecture For Efficient Fine-tuning"
authors: Tian Chunlin, Shi Zhan, Guo Zhijiang, Li Li, Xu Chengzhong
conference: "Arxiv"
year: 2024
bibkey: tian2024asymmetric
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.19245"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Adapting Large Language Models (LLMs) to new tasks through fine-tuning has been made more efficient by the introduction of Parameter-Efficient Fine-Tuning (PEFT) techniques such as LoRA. However these methods often underperform compared to full fine-tuning particularly in scenarios involving complex datasets. This issue becomes even more pronounced in complex domains highlighting the need for improved PEFT approaches that can achieve better performance. Through a series of experiments we have uncovered two critical insights that shed light on the training and parameter inefficiency of LoRA. Building on these insights we have developed HydraLoRA a LoRA framework with an asymmetric structure that eliminates the need for domain expertise. Our experiments demonstrate that HydraLoRA outperforms other PEFT approaches even those that rely on domain knowledge during the training and inference phases.
