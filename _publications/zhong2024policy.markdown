---
layout: publication
title: Policy Improvement Using Language Feedback Models
authors: Zhong Victor, Misra Dipendra, Yuan Xingdi, Côté Marc-alexandre
conference: "Arxiv"
year: 2024
bibkey: zhong2024policy
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.07876"}
tags: ['Pretraining Methods', 'Reinforcement Learning']
---
We introduce Language Feedback Models (LFMs) that identify desirable behaviour - actions that help achieve tasks specified in the instruction - for imitation learning in instruction following. To train LFMs we obtain feedback from Large Language Models (LLMs) on visual trajectories verbalized to language descriptions. First by using LFMs to identify desirable behaviour to imitate we improve in task-completion rate over strong behavioural cloning baselines on three distinct language grounding environments (Touchdown ScienceWorld and ALFWorld). Second LFMs outperform using LLMs as experts to directly predict actions when controlling for the number of LLM output tokens. Third LFMs generalize to unseen environments improving task-completion rate by 3.5-12.037; through one round of adaptation. Finally LFM can be modified to provide human-interpretable feedback without performance loss allowing human verification of desirable behaviour for imitation learning.
