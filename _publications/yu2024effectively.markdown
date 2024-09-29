---
layout: publication
title: 'Effectively Compress KV Heads For LLM'
authors: Yu Hao, Yang Zelan, Li Shen, Li Yong, Wu Jianxin
conference: "Arxiv"
year: 2024
bibkey: yu2024effectively
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.07056"}
tags: ['Attention Mechanism', 'Model Architecture', 'Reinforcement Learning']
---
The advent of pre-trained large language models (LLMs) has revolutionized various natural language processing tasks. These models predominantly employ an auto-regressive decoding mechanism that utilizes Key-Value (KV) caches to eliminate redundant calculations for previous tokens. Nevertheless as context lengths and batch sizes increase the linear expansion in memory footprint of KV caches becomes a key bottleneck of LLM deployment which decreases generation speeds significantly. To mitigate this issue previous techniques like multi-query attention (MQA) and grouped-query attention (GQA) have been developed in order to reduce KV heads to accelerate inference with comparable accuracy to multi-head attention (MHA). Despite their effectiveness existing strategies for compressing MHA often overlook the intrinsic properties of the KV caches. In this work we explore the low-rank characteristics of the KV caches and propose a novel approach for compressing KV heads. In particular we carefully optimize the MHA-to-GQA transformation to minimize compression error and to remain compatible with rotary position embeddings (RoPE) we also introduce specialized strategies for key caches with RoPE. We demonstrate that our method can compress half or even three-quarters of KV heads while maintaining performance comparable to the original LLMs which presents a promising direction for more efficient LLM deployment in resource-constrained environments.
