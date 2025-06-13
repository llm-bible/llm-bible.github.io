---
layout: publication
title: 'How To Evaluate Reward Models For RLHF'
authors: Evan Frick, Tianle Li, Connor Chen, Wei-lin Chiang, Anastasios N. Angelopoulos, Jiantao Jiao, Banghua Zhu, Joseph E. Gonzalez, Ion Stoica
conference: "Arxiv"
year: 2024
bibkey: frick2024how
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.14872'}
  - {name: "Code", url: 'https://github.com/lmarena/PPE'}
tags: ['Agentic', 'Has Code', 'Training Techniques', 'Tools', 'Reinforcement Learning']
---
We introduce a new benchmark for reward models that quantifies their ability
to produce strong language models through RLHF (Reinforcement Learning from
Human Feedback). The gold-standard approach is to run a full RLHF training
pipeline and directly probe downstream LLM performance. However, this process
is prohibitively expensive. To address this, we build a predictive model of
downstream LLM performance by evaluating the reward model on proxy tasks. These
proxy tasks consist of a large-scale human preference and a verifiable
correctness preference dataset, in which we measure 12 metrics across 12
domains. To investigate which reward model metrics are most correlated to
gold-standard RLHF outcomes, we launch an end-to-end RLHF experiment on a
large-scale crowdsourced human preference platform to view real reward model
downstream performance as ground truth. Ultimately, we compile our data and
findings into Preference Proxy Evaluations (PPE), the first reward model
benchmark explicitly linked to post-RLHF real-world human preference
performance, which we open-source for public use and further development. Our
code and evaluations can be found at https://github.com/lmarena/PPE .
