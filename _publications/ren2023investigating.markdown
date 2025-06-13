---
layout: publication
title: 'Investigating The Factual Knowledge Boundary Of Large Language Models With Retrieval Augmentation'
authors: Ruiyang Ren, Yuhao Wang, Yingqi Qu, Wayne Xin Zhao, Jing Liu, Hao Tian, Hua Wu, Ji-rong Wen, Haifeng Wang
conference: "Arxiv"
year: 2023
bibkey: ren2023investigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.11019"}
  - {name: "Code", url: "https://github.com/RUCAIBox/LLM-Knowledge-Boundary"}
tags: ['Applications', 'Has Code', 'Reinforcement Learning']
---
Large language models (LLMs) have shown impressive prowess in solving a wide
range of tasks with world knowledge. However, it remains unclear how well LLMs
are able to perceive their factual knowledge boundaries, particularly under
retrieval augmentation settings. In this study, we present the first analysis
on the factual knowledge boundaries of LLMs and how retrieval augmentation
affects LLMs on open-domain question answering (QA), with a bunch of important
findings. Specifically, we focus on three research questions and analyze them
by examining QA, priori judgement and posteriori judgement capabilities of
LLMs. We show evidence that LLMs possess unwavering confidence in their
knowledge and cannot handle the conflict between internal and external
knowledge well. Furthermore, retrieval augmentation proves to be an effective
approach in enhancing LLMs' awareness of knowledge boundaries. We further
conduct thorough experiments to examine how different factors affect LLMs and
propose a simple method to dynamically utilize supporting documents with our
judgement strategy. Additionally, we find that the relevance between the
supporting documents and the questions significantly impacts LLMs' QA and
judgemental capabilities. The code to reproduce this work is available at
https://github.com/RUCAIBox/LLM-Knowledge-Boundary.
