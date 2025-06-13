---
layout: publication
title: 'Cost-optimal Grouped-query Attention For Long-context Modeling'
authors: Yingfa Chen, Yutong Wu, Chenyang Song, Zhen Leng Thai, Xingyu Shen, Xu Han, Zhiyuan Liu, Maosong Sun
conference: "Arxiv"
year: 2025
bibkey: chen2025cost
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.09579"}
  - {name: "Code", url: "https://www.github.com/THUNLP/cost-optimal-gqa"}
tags: ['Has Code', 'Model Architecture', 'Attention Mechanism', 'Reinforcement Learning']
---
Grouped-Query Attention (GQA) is a widely adopted strategy for reducing the computational cost of attention layers in large language models (LLMs). However, current GQA configurations are often suboptimal because they overlook how context length influences inference cost. Since inference cost grows with context length, the most cost-efficient GQA configuration should also vary accordingly. In this work, we analyze the relationship among context length, model size, GQA configuration, and model loss, and introduce two innovations: (1) we decouple the total head size from the hidden size, enabling more flexible control over attention FLOPs; and (2) we jointly optimize the model size and the GQA configuration to arrive at a better allocation of inference resources between attention layers and other components. Our analysis reveals that commonly used GQA configurations are highly suboptimal for long-context scenarios. More importantly, we propose a recipe for deriving cost-optimal GQA configurations. Our results show that for long-context scenarios, one should use fewer attention heads while scaling up model size. Configurations selected by our recipe can reduce both memory usage and FLOPs by more than 50% compared to Llama-3's GQA, with *no degradation in model capabilities*. Our findings offer valuable insights for designing efficient long-context LLMs. The code is available at https://www.github.com/THUNLP/cost-optimal-gqa .
