---
layout: publication
title: 'Learning To Follow Language Instructions With Compositional Policies'
authors: Vanya Cohen, Geraud Nangue Tasse, Nakul Gopalan, Steven James, Matthew Gombolay, Benjamin Rosman
conference: "Arxiv"
year: 2021
bibkey: cohen2021learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2110.04647"}
tags: ['Agentic', 'Agent', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG']
---
We propose a framework that learns to execute natural language instructions
in an environment consisting of goal-reaching tasks that share components of
their task descriptions. Our approach leverages the compositionality of both
value functions and language, with the aim of reducing the sample complexity of
learning novel tasks. First, we train a reinforcement learning agent to learn
value functions that can be subsequently composed through a Boolean algebra to
solve novel tasks. Second, we fine-tune a seq2seq model pretrained on web-scale
corpora to map language to logical expressions that specify the required value
function compositions. Evaluating our agent in the BabyAI domain, we observe a
decrease of 86% in the number of training steps needed to learn a second task
after mastering a single task. Results from ablation studies further indicate
that it is the combination of compositional value functions and language
representations that allows the agent to quickly generalize to new tasks.
