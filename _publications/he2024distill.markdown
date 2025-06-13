---
layout: publication
title: 'Distill Visual Chart Reasoning Ability From Llms To Mllms'
authors: Wei He, Zhiheng Xi, Wanxu Zhao, Xiaoran Fan, Yiwen Ding, Zifei Shan, Tao Gui, Qi Zhang, Xuanjing Huang
conference: "Arxiv"
year: 2024
bibkey: he2024distill
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.18798'}
  - {name: "Code", url: 'https://github.com/hewei2001/ReachQA'}
tags: ['Has Code', 'Multimodal Models', 'Training Techniques']
---
Solving complex chart Q&A tasks requires advanced visual reasoning abilities
in multimodal large language models (MLLMs). Recent studies highlight that
these abilities consist of two main parts: recognizing key information from
visual inputs and conducting reasoning over it. Thus, a promising approach to
enhance MLLMs is to construct relevant training data focusing on the two
aspects. However, collecting and annotating complex charts and questions is
costly and time-consuming, and ensuring the quality of annotated answers
remains a challenge. In this paper, we propose Code-as-Intermediary Translation
(CIT), a cost-effective, efficient and easily scalable data synthesis method
for distilling visual reasoning abilities from LLMs to MLLMs. The code serves
as an intermediary that translates visual chart representations into textual
representations, enabling LLMs to understand cross-modal information.
Specifically, we employ text-based synthesizing techniques to construct
chart-plotting code and produce ReachQA, a dataset containing 3k
reasoning-intensive charts and 20k Q&A pairs to enhance both recognition and
reasoning abilities. Experiments show that when fine-tuned with our data,
models not only perform well on chart-related benchmarks, but also demonstrate
improved multimodal reasoning abilities on general mathematical benchmarks like
MathVista. The code and dataset are publicly available at
https://github.com/hewei2001/ReachQA.
