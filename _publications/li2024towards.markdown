---
layout: publication
title: "Towards Faithful Chain-of-thought: Large Language Models Are Bridging Reasoners"
authors: Li Jiachun, Cao Pengfei, Chen Yubo, Liu Kang, Zhao Jun
conference: "Arxiv"
year: 2024
bibkey: li2024towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.18915"}
tags: ['Applications']
---
Large language models (LLMs) suffer from serious unfaithful chain-of-thought (CoT) issues. Previous work attempts to measure and explain it but lacks in-depth analysis within CoTs and does not consider the interactions among all reasoning components jointly. In this paper we first study the CoT faithfulness issue at the granularity of CoT steps identify two reasoning paradigms centralized reasoning and distributed reasoning and find their relationship with faithfulness. Subsequently we conduct a joint analysis of the causal relevance among the context CoT and answer during reasoning. The result proves that when the LLM predicts answers it can recall correct information missing in the CoT from the context leading to unfaithfulness issues. Finally we propose the inferential bridging method to mitigate this issue in which we use the attribution method to recall information as hints for CoT generation and filter out noisy CoTs based on their semantic consistency and attribution scores. Extensive experiments demonstrate that our approach effectively alleviates the unfaithful CoT problem.
