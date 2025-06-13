---
layout: publication
title: 'Sambalingo: Teaching Large Language Models New Languages'
authors: Zoltan Csaki, Bo Li, Jonathan Li, Qiantong Xu, Pian Pawakapan, Leon Zhang, Yun Du, Hengyu Zhao, Changran Hu, Urmish Thakker
conference: "Arxiv"
year: 2024
bibkey: csaki2024teaching
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.05829"}
tags: ['Efficiency and Optimization', 'Reinforcement Learning']
---
Despite the widespread availability of LLMs, there remains a substantial gap
in their capabilities and availability across diverse languages. One approach
to address these issues has been to take an existing pre-trained LLM and
continue to train it on new languages. While prior works have experimented with
language adaptation, many questions around best practices and methodology have
not been covered. In this paper, we present a comprehensive investigation into
the adaptation of LLMs to new languages. Our study covers the key components in
this process, including vocabulary extension, direct preference optimization
and the data scarcity problem for human alignment in low-resource languages. We
scale these experiments across 9 languages and 2 parameter scales (7B and 70B).
We compare our models against Llama 2, Aya-101, XGLM, BLOOM and existing
language experts, outperforming all prior published baselines. Additionally,
all evaluation code and checkpoints are made public to facilitate future
research.
