---
layout: publication
title: CITING Large Language Models Create Curriculum for Instruction Tuning
authors: Feng Tao, Wang Zifeng, Sun Jimeng
conference: "Arxiv"
year: 2023
bibkey: feng2023citing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.02527"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'GPT', 'Model Architecture', 'RAG', 'Reinforcement Learning']
---
The recent advancement of large language models (LLMs) has been achieved through a combo of instruction tuning and human alignment. However building manually crafted instruction datasets and performing human alignment become the bottleneck for scaling the development of LLMs. In this paper we exploit the idea of leveraging AI models in lieu of humans as the teacher to train student LLMs. Our method is inspired by how human students refine their writing skills by following the rubrics and learning from the revisions offered by their tutors. Specifically we employ a teacher LLM to create a curriculum for instruction tuning of the student LLM namely Curriculum Instruction TunING (CITING). It encompasses two main steps (1) the teacher LLM crafts the rubrics for evaluating the answers corresponding to various types of questions and (2) the student LLM learns to follow the rubrics and perform self-correction from the revision made by the teacher. We further iteratively carry out it to embody the procedure of CITING. We compare CITING to a series of state-of-the-art baselines on four datasets. Our method demonstrates strong improvement in terms of articulate in-depth and comprehensive by GPT-4 evaluation. Specifically it achieves an average winning rate of 79.4 over SFT 73.4 over RLHF 78.1 over RRHF and 76.3 over RAFT respectively.
