---
layout: publication
title: 'Rethinking How To Evaluate Language Model Jailbreak'
authors: Cai Hongyu, Arunasalam Arjun, Lin Leo Y., Bianchi Antonio, Celik Z. Berkay
conference: "Arxiv"
year: 2024
bibkey: cai2024rethinking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.06407"}
tags: ['Applications', 'Pretraining Methods', 'RAG', 'Responsible AI']
---
Large language models (LLMs) have become increasingly integrated with various applications. To ensure that LLMs do not generate unsafe responses they are aligned with safeguards that specify what content is restricted. However such alignment can be bypassed to produce prohibited content using a technique commonly referred to as jailbreak. Different systems have been proposed to perform the jailbreak automatically. These systems rely on evaluation methods to determine whether a jailbreak attempt is successful. However our analysis reveals that current jailbreak evaluation methods have two limitations. (1) Their objectives lack clarity and do not align with the goal of identifying unsafe responses. (2) They oversimplify the jailbreak result as a binary outcome successful or not. In this paper we propose three metrics safeguard violation informativeness and relative truthfulness to evaluate language model jailbreak. Additionally we demonstrate how these metrics correlate with the goal of different malicious actors. To compute these metrics we introduce a multifaceted approach that extends the natural language generation evaluation method after preprocessing the response. We evaluate our metrics on a benchmark dataset produced from three malicious intent datasets and three jailbreak systems. The benchmark dataset is labeled by three annotators. We compare our multifaceted approach with three existing jailbreak evaluation methods. Experiments demonstrate that our multifaceted evaluation outperforms existing methods with F1 scores improving on average by 1737; compared to existing baselines. Our findings motivate the need to move away from the binary view of the jailbreak problem and incorporate a more comprehensive evaluation to ensure the safety of the language model.
