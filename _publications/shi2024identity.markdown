---
layout: publication
title: Reslora Identity Residual Mapping In Low45;rank Adaption
authors: Shi Shuhua, Huang Shaohan, Song Minghui, Li Zhoujun, Zhang Zihan, Huang Haizhen, Wei Furu, Deng Weiwei, Sun Feng, Zhang Qi
conference: "Arxiv"
year: 2024
bibkey: shi2024identity
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.18039"}
  - {name: "Code", url: "https://github.com/microsoft/LMOps/tree/main/reslora"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'Has Code', 'Merging', 'Tools', 'Training Techniques']
---
As one of the most popular parameter45;efficient fine45;tuning (PEFT) methods low45;rank adaptation (LoRA) is commonly applied to fine45;tune large language models (LLMs). However updating the weights of LoRA blocks effectively and expeditiously is challenging due to the long calculation path in the original model. To address this we propose ResLoRA an improved framework of LoRA. By adding residual paths during training and using merging approaches to eliminate these extra paths during inference our method can achieve better results in fewer training steps without any extra trainable parameters or inference cost compared to LoRA. The experiments on NLG NLU and text45;to45;image tasks demonstrate the effectiveness of our method. To the best of our knowledge ResLoRA is the first work that combines the residual path with LoRA. The code of our method is available at https://github.com/microsoft/LMOps/tree/main/reslora .
