---
layout: publication
title: "Hint Of Thought Prompting: An Explainable And Zero-shot Approach To Reasoning Tasks With Llms"
authors: Lei Ioktong, Deng Zhidong
conference: "Arxiv"
year: 2023
bibkey: lei2023hint
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.11461"}
tags: ['Few Shot', 'Prompting']
---
Prompting becomes an increasingly important research topic for better utilization of LLMs. Although simple prompting performs well on single-step questions it cannot permanently activate the correct knowledge path for multi-step reasoning tasks. The chain of thought (CoT) which often contains zero-shot CoT and few-shot CoT is a recently developed prompting method that can explain the reasoning process to the LLM and outperforms simple prompting in three challenging reasoning tasks including arithmetic symbolic and commonsense reasoning. Inspired by zero-shot CoT and further extending the zero-shot ability this paper proposes a novel hint of thought (HoT) prompting with explain-ability and zero-shot generalization. It is decomposed into three steps explainable sub-questions logical reasoning and answering. Such three steps are sequentially ordered in step-by-step hints which can be easily adjusted and explained to different tasks. Finally experimental results demonstrate that our HoT prompting has a significant advantage on the zero-shot reasoning task compared to existing zero-shot CoT. We did zero-shot experiments on math tasks like GSM8K ADDSUB AQUA SVAMP and commonsense tasks such as StrategyQA. In particular the accuracy of the proposed HoT prompting is improved with GSM8K from 40.5037; to 70.6537; with AQUA from 31.937; to 46.437; with SVAMP from 63.737; to 76.937; and with ADDSUB from 74.737; to 87.3437; respectively which even defeats the competitive PoT approach on GSM8k AQUA and SVAMP.
