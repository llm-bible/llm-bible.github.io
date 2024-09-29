---
layout: publication
title: Binding Language Models In Symbolic Languages
authors: Zhoujun Cheng, Tianbao Xie, Peng Shi, Chengzu Li, Rahul Nadkarni, Yushi Hu, Caiming Xiong, Dragomir Radev, Mari Ostendorf, Luke Zettlemoyer, Noah A. Smith, Tao Yu
conference: "Arxiv"
year: 2022
bibkey: cheng2022binding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2210.02875v2"}
  - {name: "Code", url: "https://github.com/HKUNLP/Binder"}
tags: ['GPT', 'Has Code', 'Interpretability And Explainability', 'Model Architecture', 'Prompting', 'RAG', 'Reinforcement Learning', 'Security', 'Tools', 'Training Techniques']
---
Though end45;to45;end neural approaches have recently been dominating NLP tasks in both performance and ease45;of45;use they lack interpretability and robustness. We propose Binder a training45;free neural45;symbolic framework that maps the task input to a program which (1) allows binding a unified API of language model (LM) functionalities to a programming language (e.g. SQL Python) to extend its grammar coverage and thus tackle more diverse questions (2) adopts an LM as both the program parser and the underlying model called by the API during execution and (3) requires only a few in45;context exemplar annotations. Specifically we employ GPT45;3 Codex as the LM. In the parsing stage with only a few in45;context exemplars Codex is able to identify the part of the task input that cannot be answerable by the original programming language correctly generate API calls to prompt Codex to solve the unanswerable part and identify where to place the API calls while being compatible with the original grammar. In the execution stage Codex can perform versatile functionalities (e.g. commonsense QA information extraction) given proper prompts in the API calls. Binder achieves state45;of45;the45;art results on WikiTableQuestions and TabFact datasets with explicit output programs that benefit human debugging. Note that previous best systems are all finetuned on tens of thousands of task45;specific samples while Binder only uses dozens of annotations as in45;context exemplars without any training. Our code is available at https://github.com/HKUNLP/Binder .
