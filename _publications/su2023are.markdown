---
layout: publication
title: 'Are Llms Rigorous Logical Reasoner? Empowering Natural Language Proof Generation With Contrastive Stepwise Decoding'
authors: Ying Su, Xiaojin Fu, Mingwen Liu, Zhijiang Guo
conference: "Arxiv"
year: 2023
bibkey: su2023are
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.06736"}
tags: ['Interpretability and Explainability']
---
Logical reasoning remains a pivotal component within the realm of artificial
intelligence. The recent evolution of large language models (LLMs) has marked
significant progress in this domain. The adoption of strategies like
chain-of-thought (CoT) has enhanced the performance of LLMs across diverse
reasoning tasks. Nonetheless, logical reasoning that involves proof planning,
specifically those that necessitate the validation of explanation accuracy,
continues to present stumbling blocks. In this study, we first evaluate the
efficacy of LLMs with advanced CoT strategies concerning such tasks. Our
analysis reveals that LLMs still struggle to navigate complex reasoning chains,
which demand the meticulous linkage of premises to derive a cogent conclusion.
To address this issue, we finetune a smaller-scale language model, equipping it
to decompose proof objectives into more manageable subgoals. We also introduce
contrastive decoding to stepwise proof generation, making use of negative
reasoning paths to strengthen the model's capacity for logical deduction.
Experiments on EntailmentBank underscore the success of our method in
augmenting the proof planning abilities of language models.
