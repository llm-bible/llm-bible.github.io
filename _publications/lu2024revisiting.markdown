---
layout: publication
title: 'Revisiting Multi-modal LLM Evaluation'
authors: Jian Lu, Shikhar Srivastava, Junyu Chen, Robik Shrestha, Manoj Acharya, Kushal Kafle, Christopher Kanan
conference: "Arxiv"
year: 2024
bibkey: lu2024revisiting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.05334"}
  - {name: "Code", url: "https://kevinlujian.github.io/MLLM_Evaluations/"}
tags: ['Model Architecture', 'Tools', 'Reinforcement Learning', 'GPT', 'Ethics and Bias', 'Has Code', 'Applications']
---
With the advent of multi-modal large language models (MLLMs), datasets used
for visual question answering (VQA) and referring expression comprehension have
seen a resurgence. However, the most popular datasets used to evaluate MLLMs
are some of the earliest ones created, and they have many known problems,
including extreme bias, spurious correlations, and an inability to permit
fine-grained analysis. In this paper, we pioneer evaluating recent MLLMs (LLaVA
1.5, LLaVA-NeXT, BLIP2, InstructBLIP, GPT-4V, and GPT-4o) on datasets designed
to address weaknesses in earlier ones. We assess three VQA datasets: 1) TDIUC,
which permits fine-grained analysis on 12 question types; 2) TallyQA, which has
simple and complex counting questions; and 3) DVQA, which requires optical
character recognition for chart understanding. We also study VQDv1, a dataset
that requires identifying all image regions that satisfy a given query. Our
experiments reveal the weaknesses of many MLLMs that have not previously been
reported. Our code is integrated into the widely used LAVIS framework for MLLM
evaluation, enabling the rapid assessment of future MLLMs. Project webpage:
https://kevinlujian.github.io/MLLM_Evaluations/
