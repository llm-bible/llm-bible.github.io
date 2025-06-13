---
layout: publication
title: 'PALT: Parameter-lite Transfer Of Language Models For Knowledge Graph Completion'
authors: Jianhao Shen, Chenguang Wang, Ye Yuan, Jiawei Han, Heng Ji, Koushik Sen, Ming Zhang, Dawn Song
conference: "Arxiv"
year: 2022
bibkey: shen2022parameter
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.13715"}
  - {name: "Code", url: "https://github.com/yuanyehome/PALT"}
tags: ['Fine-Tuning', 'Has Code', 'Applications', 'Reinforcement Learning']
---
This paper presents a parameter-lite transfer learning approach of pretrained
language models (LM) for knowledge graph (KG) completion. Instead of
finetuning, which modifies all LM parameters, we only tune a few new parameters
while keeping the original LM parameters fixed. We establish this via
reformulating KG completion as a "fill-in-the-blank" task, and introducing a
parameter-lite encoder on top of the original LMs. We show that, by tuning far
fewer parameters than finetuning, LMs transfer non-trivially to most tasks and
reach competitiveness with prior state-of-the-art approaches. For instance, we
outperform the fully finetuning approaches on a KG completion benchmark by
tuning only 1% of the parameters. The code and datasets are available at
\url\{https://github.com/yuanyehome/PALT\}.
