---
layout: publication
title: Adaprompt Adaptive Model Training For Prompt45;based NLP
authors: Chen Yulong, Liu Yang, Dong Li, Wang Shuohang, Zhu Chenguang, Zeng Michael, Zhang Yue
conference: "Arxiv"
year: 2022
bibkey: chen2022adaptive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2202.04824"}
tags: ['Attention Mechanism', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Training Techniques']
---
Prompt45;based learning with its capability to tackle zero45;shot and few45;shot NLP tasks has gained much attention in community. The main idea is to bridge the gap between NLP downstream tasks and language modeling (LM) by mapping these tasks into natural language prompts which are then filled by pre45;trained language models (PLMs). However for prompt learning there are still two salient gaps between NLP tasks and pretraining. First prompt information is not necessarily sufficiently present during LM pretraining. Second task45;specific data are not necessarily well represented during pretraining. We address these two issues by proposing AdaPrompt adaptively retrieving external data for continual pretraining of PLMs by making use of both task and prompt characteristics. In addition we make use of knowledge in Natural Language Inference models for deriving adaptive verbalizers. Experimental results on five NLP benchmarks show that AdaPrompt can improve over standard PLMs in few45;shot settings. In addition in zero45;shot settings our method outperforms standard prompt45;based methods by up to 26.3537; relative error reduction.
