---
layout: publication
title: 'Refuse Whenever You Feel Unsafe: Improving Safety In Llms Via Decoupled Refusal Training'
authors: Youliang Yuan, Wenxiang Jiao, Wenxuan Wang, Jen-tse Huang, Jiahao Xu, Tian Liang, Pinjia He, Zhaopeng Tu
conference: "Arxiv"
year: 2024
bibkey: yuan2024refuse
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2407.09121'}
tags: ['Efficiency and Optimization', 'Security', 'Training Techniques', 'Prompting', 'Ethics and Bias', 'Responsible AI']
---
This study addresses a critical gap in safety tuning practices for Large Language Models (LLMs) by identifying and tackling a refusal position bias within safety tuning data, which compromises the models' ability to appropriately refuse generating unsafe content. We introduce a novel approach, Decoupled Refusal Training (DeRTa), designed to empower LLMs to refuse compliance to harmful prompts at any response position, significantly enhancing their safety capabilities. DeRTa incorporates two novel components: (1) Maximum Likelihood Estimation (MLE) with Harmful Response Prefix, which trains models to recognize and avoid unsafe content by appending a segment of harmful response to the beginning of a safe response, and (2) Reinforced Transition Optimization (RTO), which equips models with the ability to transition from potential harm to safety refusal consistently throughout the harmful response sequence. Our empirical evaluation, conducted using LLaMA3 and Mistral model families across six attack scenarios, demonstrates that our method not only improves model safety without compromising performance but also surpasses baseline methods in defending against attacks.
