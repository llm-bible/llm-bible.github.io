---
layout: publication
title: 'Adaprompt: Adaptive Model Training For Prompt-based NLP'
authors: Yulong Chen, Yang Liu, Li Dong, Shuohang Wang, Chenguang Zhu, Michael Zeng, Yue Zhang
conference: "Arxiv"
year: 2022
bibkey: chen2022adaptive
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2202.04824'}
tags: ['Attention Mechanism', 'Language Modeling', 'Few-Shot', 'Training Techniques', 'Model Architecture', 'Prompting', 'Pretraining Methods']
---
Prompt-based learning, with its capability to tackle zero-shot and few-shot
NLP tasks, has gained much attention in community. The main idea is to bridge
the gap between NLP downstream tasks and language modeling (LM), by mapping
these tasks into natural language prompts, which are then filled by pre-trained
language models (PLMs). However, for prompt learning, there are still two
salient gaps between NLP tasks and pretraining. First, prompt information is
not necessarily sufficiently present during LM pretraining. Second,
task-specific data are not necessarily well represented during pretraining. We
address these two issues by proposing AdaPrompt, adaptively retrieving external
data for continual pretraining of PLMs by making use of both task and prompt
characteristics. In addition, we make use of knowledge in Natural Language
Inference models for deriving adaptive verbalizers. Experimental results on
five NLP benchmarks show that AdaPrompt can improve over standard PLMs in
few-shot settings. In addition, in zero-shot settings, our method outperforms
standard prompt-based methods by up to 26.35% relative error reduction.
