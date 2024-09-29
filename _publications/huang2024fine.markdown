---
layout: publication
title: Rolora Fine45;tuning Rotated Outlier45;free Llms For Effective Weight45;activation Quantization
authors: Huang Xijie, Liu Zechun, Liu Shih-yang, Cheng Kwang-ting
conference: "Arxiv"
year: 2024
bibkey: huang2024fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.08044"}
  - {name: "Code", url: "https://github.com/HuangOwen/RoLoRA"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'Has Code', 'Multimodal Models', 'Quantization', 'Security', 'Training Techniques']
---
Low45;Rank Adaptation (LoRA) as a representative Parameter45;Efficient Fine45;Tuning (PEFT)method significantly enhances the training efficiency by updating only a small portion of the weights in Large Language Models (LLMs). Recently weight45;only quantization techniques have also been applied to LoRA methods to reduce the memory footprint of fine45;tuning. However applying weight45;activation quantization to the LoRA pipeline is under45;explored and we observe substantial performance degradation primarily due to the presence of activation outliers. In this work we propose RoLoRA the first LoRA45;based scheme for effective weight45;activation quantization. RoLoRA utilizes rotation for outlier elimination and proposes rotation45;aware fine45;tuning to preserve the outlier45;free characteristics in rotated LLMs. Experimental results show RoLoRA consistently improves low45;bit LoRA convergence and post45;training quantization robustness in weight45;activation settings. We evaluate RoLoRA across LLaMA245;7B/13B LLaMA345;8B models achieving up to 29.537; absolute accuracy gain of 445;bit weight45;activation quantized LLaMA245; 13B on commonsense reasoning tasks compared to LoRA baseline. We further demonstrate its effectiveness on Large Multimodal Models (LLaVA45;1.545;7B). Codes are available at https://github.com/HuangOwen/RoLoRA
