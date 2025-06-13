---
layout: publication
title: 'Prompting Large Language Models For Clinical Temporal Relation Extraction'
authors: Jianping He, Laila Rasmy, Haifang Li, Jianfu Li, Zenan Sun, Evan Yu, Degui Zhi, Cui Tao
conference: "Arxiv"
year: 2024
bibkey: he2024prompting
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.04512'}
tags: ['Few-Shot', 'RAG', 'Efficiency and Optimization', 'Applications', 'Training Techniques', 'Quantization', 'Fine-Tuning', 'Prompting', 'Pretraining Methods']
---
Objective: This paper aims to prompt large language models (LLMs) for
clinical temporal relation extraction (CTRE) in both few-shot and fully
supervised settings. Materials and Methods: This study utilizes four LLMs:
Encoder-based GatorTron-Base (345M)/Large (8.9B); Decoder-based
LLaMA3-8B/MeLLaMA-13B. We developed full (FFT) and parameter-efficient (PEFT)
fine-tuning strategies and evaluated these strategies on the 2012 i2b2 CTRE
task. We explored four fine-tuning strategies for GatorTron-Base: (1) Standard
Fine-Tuning, (2) Hard-Prompting with Unfrozen LLMs, (3) Soft-Prompting with
Frozen LLMs, and (4) Low-Rank Adaptation (LoRA) with Frozen LLMs. For
GatorTron-Large, we assessed two PEFT strategies-Soft-Prompting and LoRA with
Frozen LLMs-leveraging Quantization techniques. Additionally, LLaMA3-8B and
MeLLaMA-13B employed two PEFT strategies: LoRA strategy with Quantization
(QLoRA) applied to Frozen LLMs using instruction tuning and standard
fine-tuning. Results: Under fully supervised settings, Hard-Prompting with
Unfrozen GatorTron-Base achieved the highest F1 score (89.54%), surpassing the
SOTA model (85.70%) by 3.74%. Additionally, two variants of QLoRA adapted to
GatorTron-Large and Standard Fine-Tuning of GatorTron-Base exceeded the SOTA
model by 2.36%, 1.88%, and 0.25%, respectively. Decoder-based models with
frozen parameters outperformed their Encoder-based counterparts in this
setting; however, the trend reversed in few-shot scenarios. Discussions and
Conclusions: This study presented new methods that significantly improved CTRE
performance, benefiting downstream tasks reliant on CTRE systems. The findings
underscore the importance of selecting appropriate models and fine-tuning
strategies based on task requirements and data availability. Future work will
explore larger models and broader CTRE applications.
