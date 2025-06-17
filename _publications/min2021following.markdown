---
layout: publication
title: 'FILM: Following Instructions In Language With Modular Methods'
authors: So Yeon Min, Devendra Singh Chaplot, Pradeep Ravikumar, Yonatan Bisk, Ruslan
  Salakhutdinov
conference: Arxiv
year: 2021
citations: 52
bibkey: min2021following
additional_links:
- name: Paper
  url: https://arxiv.org/abs/2110.07342
tags:
- Multimodal Models
- Fine-Tuning
---
Recent methods for embodied instruction following are typically trained
end-to-end using imitation learning. This often requires the use of expert
trajectories and low-level language instructions. Such approaches assume that
neural states will integrate multimodal semantics to perform state tracking,
building spatial memory, exploration, and long-term planning. In contrast, we
propose a modular method with structured representations that (1) builds a
semantic map of the scene and (2) performs exploration with a semantic search
policy, to achieve the natural language goal. Our modular method achieves SOTA
performance (24.46 %) with a substantial (8.17 % absolute) gap from previous
work while using less data by eschewing both expert trajectories and low-level
instructions. Leveraging low-level language, however, can further increase our
performance (26.49 %). Our findings suggest that an explicit spatial memory and
a semantic search policy can provide a stronger and more general representation
for state-tracking and guidance, even in the absence of expert trajectories or
low-level instructions.