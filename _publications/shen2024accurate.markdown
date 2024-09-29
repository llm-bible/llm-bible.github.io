---
layout: publication
title: Accurate And Efficient Fine45;tuning Of Quantized Large Language Models Through Optimal Balance
authors: Shen Ao, Wang Qiang, Lai Zhiquan, Li Xionglve, Li Dongsheng
conference: "Arxiv"
year: 2024
bibkey: shen2024accurate
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.17029"}
  - {name: "Code", url: "https://github.com/xiaocaigou/qbaraqahira&#125;&#123;https://github.com/xiaocaigou/qbaraqahira&#125;"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'Has Code', 'Quantization', 'Reinforcement Learning']
---
Large Language Models (LLMs) have demonstrated impressive performance across various domains. However the enormous number of model parameters makes fine45;tuning challenging significantly limiting their application and deployment. Existing solutions combine parameter quantization with Low45;Rank Adaptation (LoRA) greatly reducing memory usage but resulting in noticeable performance degradation. In this paper we identify an imbalance in fine45;tuning quantized pre45;trained models overly complex adapter inputs and outputs versus low effective trainability of the adaptation. We propose Quantized LLMs with Balanced45;rank Adaptation (Q45;BaRA) which simplifies the adapter inputs and outputs while increasing the adapters rank to achieve a more suitable balance for fine45;tuning quantized LLMs. Additionally for scenarios where fine45;tuned LLMs need to be deployed as low45;precision inference models we introduce Quantization45;Aware Fine45;tuning with Higher Rank Adaptation (QA45;HiRA) which simplifies the adapter inputs and outputs to align with the pre45;trained models block45;wise quantization while employing a single matrix to achieve a higher rank. Both Q45;BaRA and QA45;HiRA are easily implemented and offer the following optimizations (i) Q45;BaRA consistently achieves the highest accuracy compared to baselines and other variants requiring the same number of trainable parameters and computational effort; (ii) QA45;HiRA naturally merges adapter parameters into the block45;wise quantized model after fine45;tuning achieving the highest accuracy compared to other methods. We apply our Q45;BaRA and QA45;HiRA to the LLaMA and LLaMA2 model families and validate their effectiveness across different fine45;tuning datasets and downstream scenarios. Code will be made available at href123;https://github.com/xiaocaigou/qbaraqahira&#125;&#123;https://github.com/xiaocaigou/qbaraqahira&#125;
