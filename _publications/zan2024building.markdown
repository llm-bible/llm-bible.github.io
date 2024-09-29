---
layout: publication
title: Building Accurate Translation45;tailored Llms With Language Aware Instruction Tuning
authors: Zan Changtong, Ding Liang, Shen Li, Zhen Yibing, Liu Weifeng, Tao Dacheng
conference: "Arxiv"
year: 2024
bibkey: zan2024building
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.14399"}
  - {name: "Code", url: "https://github.com/alphadl/LanguageAware&#95;Tuning&#125;"}
tags: ['Has Code', 'Prompting', 'RAG', 'Reinforcement Learning']
---
Translation45;tailored Large language models (LLMs) exhibit remarkable translation capabilities even competing with supervised45;trained commercial translation systems. However off45;target translation remains an unsolved problem especially for low45;resource languages hindering us from developing accurate LLMs45;based translation models. To mitigate the off45;target translation problem and enhance the performance of LLMs on translation recent works have either designed advanced prompting strategies to highlight the functionality of translation instructions or exploited the in45;context learning ability of LLMs by feeding few45;shot demonstrations. However these methods essentially do not improve LLMs ability to follow translation instructions especially the language direction information. In this work we design a two45;stage fine45;tuning algorithm to improve the instruction45;following ability (especially the translation direction) of LLMs. Specifically we first tune LLMs with the maximum likelihood estimation loss on the translation dataset to elicit the basic translation capabilities. In the second stage we construct instruction45;conflicting samples by randomly replacing the translation directions with a wrong one within the instruction and then introduce an extra unlikelihood loss to learn those samples. Experiments on IWSLT and WMT benchmarks upon the LLaMA model spanning 16 zero45;shot directions show that compared to the competitive baseline 45;45; translation45;finetuned LLama our method could effectively reduce the off45;target translation ratio (averagely 45;53.337;) thus improving translation quality with average +5.7 SacreBLEU and +16.4 BLEURT. Analysis shows that our method could preserve the models general task performance on AlpacaEval. Code and models will be released at url123;https://github.com/alphadl/LanguageAware&#95;Tuning&#125;.
