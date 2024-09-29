---
layout: publication
title: Lora45;fa Memory45;efficient Low45;rank Adaptation For Large Language Models Fine45;tuning
authors: Zhang Longteng, Zhang Lin, Shi Shaohuai, Chu Xiaowen, Li Bo
conference: "Arxiv"
year: 2023
bibkey: zhang2023lora
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.03303"}
tags: ['BERT', 'Efficiency And Optimization', 'Fine Tuning', 'Model Architecture']
---
The low45;rank adaptation (LoRA) method can largely reduce the amount of trainable parameters for fine45;tuning large language models (LLMs) however it still requires expensive activation memory to update low45;rank weights. Reducing the number of LoRA layers or using activation recomputation could harm the fine45;tuning performance or increase the computational overhead. In this work we present LoRA45;FA a memory45;efficient fine45;tuning method that reduces the activation memory without performance degradation and expensive recomputation. LoRA45;FA chooses to freeze the projection45;down weight of A and update the projection45;up weight of B in each LoRA layer. It ensures the change of model weight reside in a low45;rank space during LLMs fine45;tuning while eliminating the requirement to store full45;rank input activations. We conduct extensive experiments across multiple model types (RoBERTa T5 LLaMA) and model scales. Our results show that LoRA45;FA can always achieve close fine45;tuning accuracy across different tasks compared to full parameter fine45;tuning and LoRA. Furthermore LoRA45;FA can reduce the overall memory cost by up to 1.4× compared to LoRA.
