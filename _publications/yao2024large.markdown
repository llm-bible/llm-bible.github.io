---
layout: publication
title: 'Large Language Models Are Contrastive Reasoners'
authors: Liang Yao
conference: "Arxiv"
year: 2024
bibkey: yao2024large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.08211"}
  - {name: "Code", url: "https://github.com/yao8839836/cp"}
tags: ['Model Architecture', 'Few-Shot', 'GPT', 'Has Code', 'Prompting']
---
Prompting methods play a crucial role in enhancing the capabilities of
pre-trained large language models (LLMs). We explore how contrastive prompting
(CP) significantly improves the ability of large language models to perform
complex reasoning. We demonstrate that LLMs are decent contrastive reasoners by
simply adding "Let's give a correct and a wrong answer." before LLMs provide
answers. Experiments on various large language models show that zero-shot
contrastive prompting improves the performance of standard zero-shot prompting
on a range of arithmetic, commonsense, and symbolic reasoning tasks without any
hand-crafted few-shot examples, such as increasing the accuracy on GSM8K from
35.9% to 88.8% and AQUA-RAT from 41.3% to 62.2% with the state-of-the-art GPT-4
model. Our method not only surpasses zero-shot CoT and few-shot CoT in most
arithmetic and commonsense reasoning tasks but also can seamlessly integrate
with existing prompting methods, resulting in improved or comparable results
when compared to state-of-the-art methods. Our code is available at
https://github.com/yao8839836/cp
