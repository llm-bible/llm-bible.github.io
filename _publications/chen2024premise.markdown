---
layout: publication
title: 'Premise Order Matters In Reasoning With Large Language Models'
authors: Chen Xinyun, Chi Ryan A., Wang Xuezhi, Zhou Denny
conference: "Arxiv"
year: 2024
bibkey: chen2024premise
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.08939"}
tags: ['Pretraining Methods', 'Prompting', 'Reinforcement Learning']
---
Large language models (LLMs) have accomplished remarkable reasoning performance in various domains. However in the domain of reasoning tasks we discover a frailty LLMs are surprisingly brittle to the ordering of the premises despite the fact that such ordering does not alter the underlying task. In particular we observe that LLMs achieve the best performance when the premise order aligns with the context required in intermediate reasoning steps. For example in deductive reasoning tasks presenting the premises in the same order as the ground truth proof in the prompt (as opposed to random ordering) drastically increases the models accuracy. We first examine the effect of premise ordering on deductive reasoning on a variety of LLMs and our evaluation shows that permuting the premise order can cause a performance drop of over 3037;. In addition we release the benchmark R-GSM based on GSM8K to examine the ordering effect for mathematical problem-solving and we again observe a significant drop in accuracy relative to the original GSM8K benchmark.
