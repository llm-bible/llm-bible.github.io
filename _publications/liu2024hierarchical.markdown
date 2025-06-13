---
layout: publication
title: 'Hierllm: Hierarchical Large Language Model For Question Recommendation'
authors: Yuxuan Liu, Haipeng Liu, Ting Long
conference: "Arxiv"
year: 2024
bibkey: liu2024hierarchical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.06177"}
tags: ['Efficiency and Optimization', 'Reinforcement Learning']
---
Question recommendation is a task that sequentially recommends questions for
students to enhance their learning efficiency. That is, given the learning
history and learning target of a student, a question recommender is supposed to
select the question that will bring the most improvement for students. Previous
methods typically model the question recommendation as a sequential
decision-making problem, estimating students' learning state with the learning
history, and feeding the learning state with the learning target to a neural
network to select the recommended question from a question set. However,
previous methods are faced with two challenges: (1) learning history is
unavailable in the cold start scenario, which makes the recommender generate
inappropriate recommendations; (2) the size of the question set is much large,
which makes it difficult for the recommender to select the best question
precisely. To address the challenges, we propose a method called hierarchical
large language model for question recommendation (HierLLM), which is a
LLM-based hierarchical structure. The LLM-based structure enables HierLLM to
tackle the cold start issue with the strong reasoning abilities of LLM. The
hierarchical structure takes advantage of the fact that the number of concepts
is significantly smaller than the number of questions, narrowing the range of
selectable questions by first identifying the relevant concept for the
to-recommend question, and then selecting the recommended question based on
that concept. This hierarchical structure reduces the difficulty of the
recommendation.To investigate the performance of HierLLM, we conduct extensive
experiments, and the results demonstrate the outstanding performance of
HierLLM.
