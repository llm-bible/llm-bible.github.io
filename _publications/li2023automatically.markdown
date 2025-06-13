---
layout: publication
title: 'Autoconv: Automatically Generating Information-seeking Conversations With Large Language Models'
authors: Siheng Li, Cheng Yang, Yichun Yin, Xinyu Zhu, Zesen Cheng, Lifeng Shang, Xin Jiang, Qun Liu, Yujiu Yang
conference: "Arxiv"
year: 2023
bibkey: li2023automatically
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.06507"}
tags: ['Few-Shot', 'Training Techniques', 'Language Modeling']
---
Information-seeking conversation, which aims to help users gather information
through conversation, has achieved great progress in recent years. However, the
research is still stymied by the scarcity of training data. To alleviate this
problem, we propose AutoConv for synthetic conversation generation, which takes
advantage of the few-shot learning ability and generation capacity of large
language models (LLM). Specifically, we formulate the conversation generation
problem as a language modeling task, then finetune an LLM with a few human
conversations to capture the characteristics of the information-seeking process
and use it for generating synthetic conversations with high quality.
Experimental results on two frequently-used datasets verify that AutoConv has
substantial improvements over strong baselines and alleviates the dependence on
human annotation. In addition, we also provide several analysis studies to
promote future research.
