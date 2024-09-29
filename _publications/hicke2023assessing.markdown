---
layout: publication
title: Assessing the efficacy of large language models in generating accurate teacher responses
authors: Hicke Yann, Masand Abhishek, Guo Wentao, Gangavarapu Tushaar
conference: "ACL Innovative Use of NLP for Building Educational Applications Workshop"
year: 2023
bibkey: hicke2023assessing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.04274"}
tags: ['Agentic', 'Applications', 'BERT', 'Few Shot', 'Fine Tuning', 'GPT', 'In Context Learning', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
(Tack et al. 2023) organized the shared task hosted by the 18th Workshop on Innovative Use of NLP for Building Educational Applications on generation of teacher language in educational dialogues. Following the structure of the shared task in this study we attempt to assess the generative abilities of large language models in providing informative and helpful insights to students thereby simulating the role of a knowledgeable teacher. To this end we present an extensive evaluation of several benchmarking generative models including GPT-4 (few-shot in-context learning) fine-tuned GPT-2 and fine-tuned DialoGPT. Additionally to optimize for pedagogical quality we fine-tuned the Flan-T5 model using reinforcement learning. Our experimental findings on the Teacher-Student Chatroom Corpus subset indicate the efficacy of GPT-4 over other fine-tuned models measured using BERTScore and DialogRPT. We hypothesize that several dataset characteristics including sampling representativeness and dialog completeness pose significant challenges to fine-tuning thus contributing to the poor generalizability of the fine-tuned models. Finally we note the need for these generative models to be evaluated with a metric that relies not only on dialog coherence and matched language modeling distribution but also on the models ability to showcase pedagogical skills.
