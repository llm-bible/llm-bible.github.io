---
layout: publication
title: Assessing The Efficacy Of Large Language Models In Generating Accurate Teacher Responses
authors: Hicke Yann, Masand Abhishek, Guo Wentao, Gangavarapu Tushaar
conference: "ACL Innovative Use of NLP for Building Educational Applications Workshop"
year: 2023
bibkey: hicke2023assessing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.04274"}
tags: ['Agentic', 'Applications', 'BERT', 'GPT', 'Language Modeling', 'Model Architecture', 'Reinforcement Learning']
---
(Tack et al. 2023) organized the shared task hosted by the 18th Workshop on Innovative Use of NLP for Building Educational Applications on generation of teacher language in educational dialogues. Following the structure of the shared task in this study we attempt to assess the generative abilities of large language models in providing informative and helpful insights to students thereby simulating the role of a knowledgeable teacher. To this end we present an extensive evaluation of several benchmarking generative models including GPT45;4 (few45;shot in45;context learning) fine45;tuned GPT45;2 and fine45;tuned DialoGPT. Additionally to optimize for pedagogical quality we fine45;tuned the Flan45;T5 model using reinforcement learning. Our experimental findings on the Teacher45;Student Chatroom Corpus subset indicate the efficacy of GPT45;4 over other fine45;tuned models measured using BERTScore and DialogRPT. We hypothesize that several dataset characteristics including sampling representativeness and dialog completeness pose significant challenges to fine45;tuning thus contributing to the poor generalizability of the fine45;tuned models. Finally we note the need for these generative models to be evaluated with a metric that relies not only on dialog coherence and matched language modeling distribution but also on the models ability to showcase pedagogical skills.
