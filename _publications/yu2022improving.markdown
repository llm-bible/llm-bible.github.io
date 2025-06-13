---
layout: publication
title: 'KRLS: Improving End-to-end Response Generation In Task Oriented Dialog With Reinforced Keywords Learning'
authors: Xiao Yu, Qingyang Wu, Kun Qian, Zhou Yu
conference: "Arxiv"
year: 2022
bibkey: yu2022improving
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2211.16773'}
tags: ['Reinforcement Learning', 'Fine-Tuning', 'Agentic', 'Training Techniques']
---
In task-oriented dialogs (TOD), reinforcement learning (RL) algorithms train
a model to directly optimize response for task-related metrics. However, RL
needs to perform exploration, which can be time-consuming due to the slow
auto-regressive sequence generation process. We investigate an approach to
create a more efficient RL-based algorithm to improve TOD performance in an
offline setting. First, we use a faster generation procedure that samples from
independent next-word distributions after training the language model (LM) with
supervised learning. We then introduce a fine-grained reward function to help
the model focus on learning key information in a dialog, by measuring the
importance and semantic closeness of each generated token. Experiments on the
MultiWoZ dataset show our new training algorithm, Keywords Reinforcement
Learning with Next-word Sampling (KRLS), achieves state-of-the-art performance
on the end-to-end response generation task, with a 15% training time reduction
compared to a standard RL algorithm using auto-regressive generation.
