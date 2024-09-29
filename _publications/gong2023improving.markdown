---
layout: publication
title: "Improving Input-label Mapping With Demonstration Replay For In-context Learning"
authors: Gong Zhuocheng, Liu Jiahao, Wang Qifan, Wang Jingang, Cai Xunliang, Zhao Dongyan, Yan Rui
conference: "Arxiv"
year: 2023
bibkey: gong2023improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.19572"}
tags: ['Attention Mechanism', 'GPT', 'In Context Learning', 'Language Modeling', 'Merging', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Training Techniques']
---
In-context learning (ICL) is an emerging capability of large autoregressive language models where a few input-label demonstrations are appended to the input to enhance the models understanding of downstream NLP tasks without directly adjusting the model parameters. The effectiveness of ICL can be attributed to the strong language modeling capabilities of large language models (LLMs) which enable them to learn the mapping between input and labels based on in-context demonstrations. Despite achieving promising results the causal nature of language modeling in ICL restricts the attention to be backward only i.e. a token only attends to its previous tokens failing to capture the full input-label information and limiting the models performance. In this paper we propose a novel ICL method called Repeated Demonstration with Sliding Causal Attention (RdSca). Specifically we duplicate later demonstrations and concatenate them to the front allowing the model to observe the later information even under the causal restriction. Besides we introduce sliding causal attention which customizes causal attention to avoid information leakage. Experimental results show that our method significantly improves the input-label mapping in ICL demonstrations. We also conduct an in-depth analysis of how to customize the causal attention without training which has been an unexplored area in previous research.
