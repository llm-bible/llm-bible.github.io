---
layout: publication
title: 'Droidspeak: KV Cache Sharing For Cross-llm Communication And Multi-llm Serving'
authors: Yuhan Liu, Yuyang Huang, Jiayi Yao, Zhuohan Gu, Kuntai Du, Hanchen Li, Yihua Cheng, Junchen Jiang, Shan Lu, Madan Musuvathi, Esha Choukse
conference: "Arxiv"
year: 2024
bibkey: liu2024kv
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.02820"}
tags: ['Tools', 'Efficiency and Optimization']
---
Large Language Models (LLMs) are increasingly employed in complex workflows,
where different LLMs and fine-tuned variants collaboratively address complex
tasks. However, these systems face significant inefficiencies due to redundant
context processing of the shared context. We propose DroidSpeak, a framework
that optimizes context sharing between fine-tuned LLMs derived from the same
foundational model. DroidSpeak identifies critical layers in the KV cache and
selectively recomputes them, enabling effective reuse of intermediate data
while maintaining high accuracy.
  Our approach balances computational efficiency and task fidelity,
significantly reducing inference latency and throughput bottlenecks.
Experiments on diverse datasets and model pairs demonstrate that DroidSpeak
achieves up to 3x higher throughputs and 2.6x faster prefill times with
negligible accuracy loss compared to full recomputation.
