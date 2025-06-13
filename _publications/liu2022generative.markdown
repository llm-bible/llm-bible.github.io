---
layout: publication
title: 'A Generative User Simulator With Gpt-based Architecture And Goal State Tracking For Reinforced Multi-domain Dialog Systems'
authors: Hong Liu, Yucheng Cai, Zhijian Ou, Yi Huang, Junlan Feng
conference: "Arxiv"
year: 2022
bibkey: liu2022generative
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.08692"}
tags: ['Agentic', 'Model Architecture', 'Reinforcement Learning', 'RAG', 'GPT', 'Attention Mechanism']
---
Building user simulators (USs) for reinforcement learning (RL) of
task-oriented dialog systems (DSs) has gained more and more attention, which,
however, still faces several fundamental challenges. First, it is unclear
whether we can leverage pretrained language models to design, for example,
GPT-2 based USs, to catch up and interact with the recently advanced GPT-2
based DSs. Second, an important ingredient in a US is that the user goal can be
effectively incorporated and tracked; but how to flexibly integrate goal state
tracking and develop an end-to-end trainable US for multi-domains has remained
to be a challenge. In this work, we propose a generative user simulator (GUS)
with GPT-2 based architecture and goal state tracking towards addressing the
above two challenges. Extensive experiments are conducted on MultiWOZ2.1.
Different DSs are trained via RL with GUS, the classic agenda-based user
simulator (ABUS) and other ablation simulators respectively, and are compared
for cross-model evaluation, corpus-based evaluation and human evaluation. The
GUS achieves superior results in all three evaluation tasks.
