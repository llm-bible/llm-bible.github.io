---
layout: publication
title: 'Teacherlm: Teaching To Fish Rather Than Giving The Fish, Language Modeling Likewise'
authors: Nan He, Hanyu Lai, Chenyang Zhao, Zirui Cheng, Junting Pan, Ruoyu Qin, Ruofan Lu, Rui Lu, Yunchen Zhang, Gangming Zhao, Zhaohui Hou, Zhiyuan Huang, Shaoqing Lu, Ding Liang, Mingjie Zhan
conference: "Arxiv"
year: 2023
bibkey: he2023teaching
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2310.19019'}
tags: ['Reinforcement Learning', 'Language Modeling']
---
Large Language Models (LLMs) exhibit impressive reasoning and data
augmentation capabilities in various NLP tasks. However, what about small
models? In this work, we propose TeacherLM-7.1B, capable of annotating relevant
fundamentals, chain of thought, and common mistakes for most NLP samples, which
makes annotation more than just an answer, thus allowing other models to learn
"why" instead of just "what". The TeacherLM-7.1B model achieved a zero-shot
score of 52.3 on MMLU, surpassing most models with over 100B parameters. Even
more remarkable is its data augmentation ability. Based on TeacherLM-7.1B, we
augmented 58 NLP datasets and taught various student models with different
parameters from OPT and BLOOM series in a multi-task setting. The experimental
results indicate that the data augmentation provided by TeacherLM has brought
significant benefits. We will release the TeacherLM series of models and
augmented datasets as open-source.
