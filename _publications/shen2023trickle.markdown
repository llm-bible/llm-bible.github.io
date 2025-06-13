---
layout: publication
title: 'The Trickle-down Impact Of Reward (in-)consistency On RLHF'
authors: Lingfeng Shen, Sihao Chen, Linfeng Song, Lifeng Jin, Baolin Peng, Haitao Mi, Daniel Khashabi, Dong Yu
conference: "Arxiv"
year: 2023
bibkey: shen2023trickle
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.16155"}
tags: ['Agentic', 'RAG', 'Merging', 'Reinforcement Learning', 'Training Techniques', 'Prompting']
---
Standard practice within Reinforcement Learning from Human Feedback (RLHF)
involves optimizing against a Reward Model (RM), which itself is trained to
reflect human preferences for desirable generations. A notable subject that is
understudied is the (in-)consistency of RMs -- whether they can recognize the
semantic changes to different prompts and appropriately adapt their reward
assignments -- and their impact on the downstream RLHF model.
  In this paper, we visit a series of research questions relevant to RM
inconsistency: (1) How can we measure the consistency of reward models? (2) How
consistent are the existing RMs and how can we improve them? (3) In what ways
does reward inconsistency influence the chatbots resulting from the RLHF model
training?
  We propose Contrast Instructions -- a benchmarking strategy for the
consistency of RM. Each example in Contrast Instructions features a pair of
lexically similar instructions with different ground truth responses. A
consistent RM is expected to rank the corresponding instruction and response
higher than other combinations. We observe that current RMs trained with the
standard ranking objective fail miserably on Contrast Instructions compared to
average humans. To show that RM consistency can be improved efficiently without
using extra training budget, we propose two techniques ConvexDA and
RewardFusion, which enhance reward consistency through extrapolation during the
RM training and inference stage, respectively. We show that RLHF models trained
with a more consistent RM yield more useful responses, suggesting that reward
inconsistency exhibits a trickle-down effect on the downstream RLHF process.
