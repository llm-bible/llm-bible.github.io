---
layout: publication
title: Owlore Outlier45;weighed Layerwise Sampled Low45;rank Projection For Memory45;efficient LLM Fine45;tuning
authors: Li Pengxiang, Yin Lu, Gao Xiaowei, Liu Shiwei
conference: "Arxiv"
year: 2024
bibkey: li2024outlier
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.18380"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'Model Architecture', 'Pruning', 'RAG', 'Tools', 'Training Techniques']
---
The rapid advancements in Large Language Models (LLMs) have revolutionized various natural language processing tasks. However the substantial size of LLMs presents significant challenges in training or fine45;tuning. While parameter45;efficient approaches such as low45;rank adaptation (LoRA) have gained popularity they often compromise performance compared to full45;rank fine45;tuning. In this paper we propose Outlier45;weighed Layerwise Sampled Low45;Rank Projection (OwLore) a new memory45;efficient fine45;tuning approach inspired by the layerwise outlier distribution of LLMs which dynamically samples pre45;trained layers to fine45;tune instead of adding additional adaptors. We first interpret the outlier phenomenon through the lens of Heavy45;Tailed Self45;Regularization theory (HT45;SR) discovering that layers with more outliers tend to be more heavy45;tailed and consequently better trained. Inspired by this finding OwLore strategically assigns higher sampling probabilities to layers with more outliers to better leverage the knowledge stored in pre45;trained LLMs. To further mitigate the memory demands of fine45;tuning we integrate gradient low45;rank projection into our approach which facilitates each layer to be efficiently trained in a low45;rank manner. By incorporating the efficient characteristics of low45;rank and optimal layerwise sampling OwLore significantly improves the memory45;performance trade45;off in LLM pruning. Our extensive experiments across various architectures including LLaMa2 LLaMa3 and Mistral demonstrate that OwLore consistently outperforms baseline approaches including full fine45;tuning. Specifically it achieves up to a 1.137; average accuracy gain on the Commonsense Reasoning benchmark a 3.037; improvement on MMLU and a notable 1037; boost on MT45;Bench while being more memory efficient. OwLore allows us to fine45;tune LLaMa245;7B with only 21GB of memory.
