---
layout: publication
title: 'DESTEIN: Navigating Detoxification Of Language Models Via Universal Steering Pairs And Head-wise Activation Fusion'
authors: Yu Li, Han Jiang, Chuanyang Gong, Zhihua Wei
conference: "Arxiv"
year: 2024
bibkey: li2024navigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.10464"}
  - {name: "Code", url: "https://github.com/LizLizLi/DeStein"}
tags: ['Merging', 'Has Code']
---
Despite the remarkable achievements of language models (LMs) across a broad
spectrum of tasks, their propensity for generating toxic outputs remains a
prevalent concern. Current solutions involving finetuning or auxiliary models
usually require extensive computational resources, hindering their practicality
in large language models (LLMs). In this paper, we propose DeStein, a novel
method that detoxifies LMs by applying representation engineering in activation
spaces with lower resource and time costs. Specifically, we derive
detoxification vectors from self-induced, universal steering pairs through
arithmetic operations in activation spaces. During inference, detoxification is
achieved by fusing the detoxification vectors with the original representations
in a head-wise manner. Empirical results demonstrate that our method
significantly outperforms previous state-of-the-art approaches on various
metrics, while also maintaining satisfactory generation quality and diversity.
We further validate the practicality and scalability of DeStein with a series
of white-box LLMs. The method is open-sourced at
https://github.com/LizLizLi/DeStein. Warning: Some example model outputs may
contain highly offensive or disturbing text.
