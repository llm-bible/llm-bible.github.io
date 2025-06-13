---
layout: publication
title: 'Dlp-lora: Efficient Task-specific Lora Fusion With A Dynamic, Lightweight Plugin For Large Language Models'
authors: Yuxuan Zhang, Ruizhe Li
conference: "Arxiv"
year: 2024
bibkey: zhang2024dlp
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.01497"}
  - {name: "Code", url: "https://github.com/MeCuping/DLP-LoRA"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Tools', 'RAG', 'Merging', 'Pretraining Methods', 'Fine-Tuning', 'Has Code', 'Applications']
---
Recent advancements in Large Language Models (LLMs) have achieved robust
performance across diverse tasks, but fine-tuning these models for specific
domains remains resource-intensive. Parameter-Efficient Fine-Tuning (PEFT)
methods like Low-Rank Adaptation (LoRA) address this challenge by fine-tuning a
small subset of parameters. However, existing methods for fusing multiple LoRAs
lack dynamic fusion based on contextual inputs and often increase inference
time due to token-level operations. We propose DLP-LoRA, a Dynamic Lightweight
Plugin that employs a mini-MLP module with only 5M parameters to dynamically
fuse multiple LoRAs at the sentence level using top-p sampling strategies. This
approach reduces inference time to less than twice that of single LoRA
inference by leveraging parallel computation. Evaluations across 26
tasks-including multiple-choice questions and question answering-demonstrate
that DLP-LoRA achieves an average accuracy of 92.34% on multiple-choice
datasets and significant improvements in BLEU and ROUGE scores on QA datasets,
outperforming different LLMs backbones under composite task settings. DLP-LoRA
effectively balances performance and efficiency, making it a practical solution
for dynamic multi-task adaptation in LLMs. Our code is available at
https://github.com/MeCuping/DLP-LoRA.
