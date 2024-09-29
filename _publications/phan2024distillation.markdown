---
layout: publication
title: Distillation Contrastive Decoding: Improving Llms Reasoning With Contrastive Decoding And Distillation
authors: Phan Phuc, Tran Hieu, Phan Long
conference: "Arxiv"
year: 2024
bibkey: phan2024distillation
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.14874"}
tags: ['Distillation', 'Efficiency And Optimization', 'Prompting', 'Quantization']
---
We propose a straightforward approach called Distillation Contrastive Decoding (DCD) to enhance the reasoning capabilities of Large Language Models (LLMs) during inference. In contrast to previous approaches that relied on smaller amateur models or analysis of hidden state differences DCD employs Contrastive Chain-of-thought Prompting and advanced distillation techniques including Dropout and Quantization. This approach effectively addresses the limitations of Contrastive Decoding (CD) which typically requires both an expert and an amateur model thus increasing computational resource demands. By integrating contrastive prompts with distillation DCD obviates the need for an amateur model and reduces memory usage. Our evaluations demonstrate that DCD significantly enhances LLM performance across a range of reasoning benchmarks surpassing both CD and existing methods in the GSM8K and StrategyQA datasets.
