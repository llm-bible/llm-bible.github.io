---
layout: publication
title: User Memory Reasoning For Conversational Recommendation
authors: Hu Xu et al.
conference: Arxiv
year: 2020
citations: 17
bibkey: xu2020user
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2006.00184'}]
tags: [Reinforcement Learning]
---
We study a conversational recommendation model which dynamically manages
users' past (offline) preferences and current (online) requests through a
structured and cumulative user memory knowledge graph, to allow for natural
interactions and accurate recommendations. For this study, we create a new
Memory Graph (MG) <--> Conversational Recommendation parallel corpus called
MGConvRex with 7K+ human-to-human role-playing dialogs, grounded on a
large-scale user memory bootstrapped from real-world user scenarios. MGConvRex
captures human-level reasoning over user memory and has disjoint
training/testing sets of users for zero-shot (cold-start) reasoning for
recommendation. We propose a simple yet expandable formulation for constructing
and updating the MG, and a reasoning model that predicts optimal dialog
policies and recommendation items in unconstrained graph space. The prediction
of our proposed model inherits the graph structure, providing a natural way to
explain the model's recommendation. Experiments are conducted for both offline
metrics and online simulation, showing competitive results.