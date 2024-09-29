---
layout: publication
title: 'Lynx: An Open Source Hallucination Evaluation Model'
authors: Ravi Selvan Sunitha, Mielczarek Bartosz, Kannappan Anand, Kiela Douwe, Qian Rebecca
conference: "Arxiv"
year: 2024
bibkey: ravi2024open
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.08488"}
tags: ['GPT', 'Model Architecture', 'RAG', 'Reinforcement Learning']
---
Retrieval Augmented Generation (RAG) techniques aim to mitigate hallucinations in Large Language Models (LLMs). However LLMs can still produce information that is unsupported or contradictory to the retrieved contexts. We introduce LYNX a SOTA hallucination detection LLM that is capable of advanced reasoning on challenging real-world hallucination scenarios. To evaluate LYNX we present HaluBench a comprehensive hallucination evaluation benchmark consisting of 15k samples sourced from various real-world domains. Our experiment results show that LYNX outperforms GPT-4o Claude-3-Sonnet and closed and open-source LLM-as-a-judge models on HaluBench. We release LYNX HaluBench and our evaluation code for public access.
