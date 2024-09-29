---
layout: publication
title: Improving Factuality In Large Language Models Via Decoding45;time Hallucinatory And Truthful Comparators
authors: Yang Dingkang, Xiao Dongling, Wei Jinjie, Li Mingcheng, Chen Zhaoyu, Li Ke, Zhang Lihua
conference: "Arxiv"
year: 2024
bibkey: yang2024improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.12325"}
tags: ['Pretraining Methods', 'Tools']
---
Despite their remarkable capabilities Large Language Models (LLMs) are prone to generate responses that contradict verifiable facts i.e. unfaithful hallucination content. Existing efforts generally focus on optimizing model parameters or editing semantic representations which compromise the internal factual knowledge of target LLMs. In addition hallucinations typically exhibit multifaceted patterns in downstream tasks limiting the models holistic performance across tasks. In this paper we propose a Comparator45;driven Decoding45;Time (CDT) framework to alleviate the response hallucination. Firstly we construct hallucinatory and truthful comparators with multi45;task fine45;tuning samples. In this case we present an instruction prototype45;guided mixture of experts strategy to enhance the ability of the corresponding comparators to capture different hallucination or truthfulness patterns in distinct task instructions. CDT constrains next45;token predictions to factuality45;robust distributions by contrasting the logit differences between the target LLMs and these comparators. Systematic experiments on multiple downstream tasks show that our framework can significantly improve the model performance and response factuality.
