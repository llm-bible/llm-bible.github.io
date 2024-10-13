---
layout: publication
title: 'Knowtuning: Knowledge-aware Fine-tuning For Large Language Models'
authors: Lyu Yougang, Yan Lingyong, Wang Shuaiqiang, Shi Haibo, Yin Dawei, Ren Pengjie, Chen Zhumin, De Rijke Maarten, Ren Zhaochun
conference: "Arxiv"
year: 2024
bibkey: lyu2024knowledge
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.11176"}
tags: ['Applications', 'Fine Tuning', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
Despite their success at many natural language processing (NLP) tasks, large
language models still struggle to effectively leverage knowledge for
knowledge-intensive tasks, manifesting limitations such as generating
incomplete, non-factual, or illogical answers. These limitations stem from
inadequate knowledge awareness of LLMs during vanilla fine-tuning. To address
these problems, we propose a knowledge-aware fine-tuning (KnowTuning) method to
improve fine-grained and coarse-grained knowledge awareness of LLMs. We devise
a fine-grained knowledge augmentation stage to train LLMs to identify difficult
fine-grained knowledge in answers. We also propose a coarse-grained knowledge
comparison stage to train LLMs to distinguish between reliable and unreliable
knowledge, in three aspects: completeness, factuality, and logicality.
Extensive experiments on both generic and medical question answering (QA)
datasets confirm the effectiveness of KnowTuning, through automatic and human
evaluations, across various sizes of LLMs. We further verify that KnowTuning
generates more facts with less factual error rate under fine-grained facts
evaluation.
