---
layout: publication
title: Investigating The Catastrophic Forgetting In Multimodal Large Language Models
authors: Zhai Yuexiang, Tong Shengbang, Li Xiao, Cai Mu, Qu Qing, Lee Yong Jae, Ma Yi
conference: "Arxiv"
year: 2023
bibkey: zhai2023investigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.10313"}
tags: ['GPT', 'Model Architecture', 'Multimodal Models', 'Reinforcement Learning']
---
Following the success of GPT4 there has been a surge in interest in multimodal large language model (MLLM) research. This line of research focuses on developing general45;purpose LLMs through fine45;tuning pre45;trained LLMs and vision models. However catastrophic forgetting a notorious phenomenon where the fine45;tuned model fails to retain similar performance compared to the pre45;trained model still remains an inherent problem in multimodal LLMs (MLLM). In this paper we introduce EMT Evaluating MulTimodality for evaluating the catastrophic forgetting in MLLMs by treating each MLLM as an image classifier. We first apply EMT to evaluate several open45;source fine45;tuned MLLMs and we discover that almost all evaluated MLLMs fail to retain the same performance levels as their vision encoders on standard image classification tasks. Moreover we continue fine45;tuning LLaVA an MLLM and utilize EMT to assess performance throughout the fine45;tuning. Interestingly our results suggest that early45;stage fine45;tuning on an image dataset improves performance across other image datasets by enhancing the alignment of text and visual features. However as fine45;tuning proceeds the MLLMs begin to hallucinate resulting in a significant loss of generalizability even when the image encoder remains frozen. Our results suggest that MLLMs have yet to demonstrate performance on par with their vision models on standard image classification tasks and the current MLLM fine45;tuning procedure still has room for improvement.
