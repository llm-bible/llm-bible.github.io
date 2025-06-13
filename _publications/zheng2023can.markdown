---
layout: publication
title: 'Can We Edit Factual Knowledge By In-context Learning?'
authors: Ce Zheng, Lei Li, Qingxiu Dong, Yuxuan Fan, Zhiyong Wu, Jingjing Xu, Baobao Chang
conference: "Arxiv"
year: 2023
bibkey: zheng2023can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.12740"}
  - {name: "Code", url: "https://github.com/Zce1112zslx/IKE"}
tags: ['Fine-Tuning', 'GPT', 'Model Architecture', 'Training Techniques', 'Has Code', 'Pretraining Methods', 'Prompting', 'In-Context Learning']
---
Previous studies have shown that large language models (LLMs) like GPTs store
massive factual knowledge in their parameters. However, the stored knowledge
could be false or out-dated. Traditional knowledge editing methods refine LLMs
via fine-tuning on texts containing specific knowledge. However, with the
increasing scales of LLMs, these gradient-based approaches bring large
computation costs. The trend of model-as-a-service also makes it impossible to
modify knowledge in black-box LMs. Inspired by in-context learning (ICL), a new
paradigm based on demonstration contexts without parameter updating, we explore
whether ICL can edit factual knowledge. To answer this question, we give a
comprehensive empirical study of ICL strategies. Experiments show that
in-context knowledge editing (IKE), without any gradient and parameter
updating, achieves a competitive success rate compared to gradient-based
methods on GPT-J (6B) but with much fewer side effects, including less
over-editing on similar but unrelated facts and less knowledge forgetting on
previously stored knowledge. We also apply the method to larger LMs with tens
or hundreds of parameters like OPT-175B, which shows the scalability of our
method. The code is available at https://github.com/Zce1112zslx/IKE.
