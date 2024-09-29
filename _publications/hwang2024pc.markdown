---
layout: publication
title: Pc-lora: Low-rank Adaptation For Progressive Model Compression With Knowledge Distillation
authors: Hwang Injoon, Park Haewon, Lee Youngwan, Yang Jooyoung, Maeng Sunjae
conference: "Arxiv"
year: 2024
bibkey: hwang2024pc
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.09117"}
tags: ['BERT', 'Distillation', 'Efficiency And Optimization', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Quantization', 'Training Techniques']
---
Low-rank adaption (LoRA) is a prominent method that adds a small number of learnable parameters to the frozen pre-trained weights for parameter-efficient fine-tuning. Prompted by the question Can we make its representation enough with LoRA weights solely at the final phase of finetuning without the pre-trained weights In this work we introduce Progressive Compression LoRA~(PC-LoRA) which utilizes low-rank adaptation (LoRA) to simultaneously perform model compression and fine-tuning. The PC-LoRA method gradually removes the pre-trained weights during the training process eventually leaving only the low-rank adapters in the end. Thus these low-rank adapters replace the whole pre-trained weights achieving the goals of compression and fine-tuning at the same time. Empirical analysis across various models demonstrates that PC-LoRA achieves parameter and FLOPs compression rates of 94.3637;/89.137; for vision models e.g. ViT-B and 93.4237;/84.237; parameters and FLOPs compressions for language models e.g. BERT.
