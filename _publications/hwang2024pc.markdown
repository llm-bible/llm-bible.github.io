---
layout: publication
title: Pc45;lora Low45;rank Adaptation For Progressive Model Compression With Knowledge Distillation
authors: Hwang Injoon, Park Haewon, Lee Youngwan, Yang Jooyoung, Maeng Sunjae
conference: "Arxiv"
year: 2024
bibkey: hwang2024pc
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.09117"}
tags: ['BERT', 'Distillation', 'Efficiency And Optimization', 'Fine Tuning', 'Model Architecture', 'Prompting', 'Quantization', 'Training Techniques']
---
Low45;rank adaption (LoRA) is a prominent method that adds a small number of learnable parameters to the frozen pre45;trained weights for parameter45;efficient fine45;tuning. Prompted by the question Can we make its representation enough with LoRA weights solely at the final phase of finetuning without the pre45;trained weights In this work we introduce Progressive Compression LoRA~(PC45;LoRA) which utilizes low45;rank adaptation (LoRA) to simultaneously perform model compression and fine45;tuning. The PC45;LoRA method gradually removes the pre45;trained weights during the training process eventually leaving only the low45;rank adapters in the end. Thus these low45;rank adapters replace the whole pre45;trained weights achieving the goals of compression and fine45;tuning at the same time. Empirical analysis across various models demonstrates that PC45;LoRA achieves parameter and FLOPs compression rates of 94.3637;/89.137; for vision models e.g. ViT45;B and 93.4237;/84.237; parameters and FLOPs compressions for language models e.g. BERT.
