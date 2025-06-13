---
layout: publication
title: 'Lora-mini : Adaptation Matrices Decomposition And Selective Training'
authors: Ayush Singh, Rajdeep Aher, Shivank Garg
conference: "Arxiv"
year: 2024
bibkey: singh2024lora
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.15804"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Tools', 'RAG', 'Pretraining Methods', 'Fine-Tuning']
---
The rapid advancements in large language models (LLMs) have revolutionized
natural language processing, creating an increased need for efficient,
task-specific fine-tuning methods. Traditional fine-tuning of LLMs involves
updating a large number of parameters, which is computationally expensive and
memory-intensive. Low-Rank Adaptation (LoRA) has emerged as a promising
solution, enabling parameter-efficient fine-tuning by reducing the number of
trainable parameters. However, while LoRA reduces the number of trainable
parameters, LoRA modules still create significant storage challenges. We
propose LoRA-Mini, an optimized adaptation of LoRA that improves parameter
efficiency by splitting low-rank matrices into four parts, with only the two
inner matrices being trainable. This approach achieves upto a 20x reduction
compared to standard LoRA in the number of trainable parameters while
preserving performance levels comparable to standard LoRA, addressing both
computational and storage efficiency in LLM fine-tuning.
