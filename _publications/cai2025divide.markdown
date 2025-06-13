---
layout: publication
title: 'Divide-and-conquer: Tree-structured Strategy With Answer Distribution Estimator For Goal-oriented Visual Dialogue'
authors: Shuo Cai, Xinzhe Han, Shuhui Wang
conference: "Arxiv"
year: 2025
bibkey: cai2025divide
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.05806"}
tags: ['Agentic', 'Efficiency and Optimization', 'Model Architecture', 'Reinforcement Learning', 'RAG', 'Applications', 'Attention Mechanism']
---
Goal-oriented visual dialogue involves multi-round interaction between
artificial agents, which has been of remarkable attention due to its wide
applications. Given a visual scene, this task occurs when a Questioner asks an
action-oriented question and an Answerer responds with the intent of letting
the Questioner know the correct action to take. The quality of questions
affects the accuracy and efficiency of the target search progress. However,
existing methods lack a clear strategy to guide the generation of questions,
resulting in the randomness in the search process and inconvergent results. We
propose a Tree-Structured Strategy with Answer Distribution Estimator (TSADE)
which guides the question generation by excluding half of the current candidate
objects in each round. The above process is implemented by maximizing a binary
reward inspired by the ``divide-and-conquer'' paradigm. We further design a
candidate-minimization reward which encourages the model to narrow down the
scope of candidate objects toward the end of the dialogue. We experimentally
demonstrate that our method can enable the agents to achieve high task-oriented
accuracy with fewer repeating questions and rounds compared to traditional
ergodic question generation approaches. Qualitative results further show that
TSADE facilitates agents to generate higher-quality questions.
