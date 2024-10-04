---
layout: publication
title: 'Soaring From 4K To 400K: Extending Llm''s Context With Activation Beacon'
authors: Zhang Peitian, Liu Zheng, Xiao Shitao, Shao Ninglu, Ye Qiwei, Dou Zhicheng
conference: "Arxiv"
year: 2024
bibkey: zhang2024soaring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.03462"}
  - {name: "Code", url: "https://github.com/FlagOpen/FlagEmbedding"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'Has Code', 'Language Modeling', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
The utilization of long contexts poses a big challenge for LLMs due to their limited context window size. Although the context window can be extended through fine-tuning, it will result in a considerable cost at both training and inference time, and exert an unfavorable impact to the LLM's original capabilities. In this work, we propose a new method called Activation Beacon, which condenses LLM's raw activations into compact forms such that the LLM can perceive a longer context with a limited context window. Activation Beacon is introduced as a plug-in module, which fully preserves the LLM's original capability in short contexts. It works with the sliding window to streamingly process the long context, which leads to a competitive memory and time efficiency in both training and inference. Activation Beacon is trained with short-sequence data of diversified condensing ratios. Thanks to such a treatment, it can be effectively learned to support different context lengths with a small training cost. Our experiment verifies Activation Beacon's effectiveness of context extension: it can remarkably accomplish high-quality extension of Llama-2-7B's context by \\(\times100\\) times (from 4K to 400K); meanwhile, it can also achieve superior performances across a variety of long-context language modeling and understanding tasks. The source code and model checkpoint are available at \url\{https://github.com/FlagOpen/FlagEmbedding\}.
