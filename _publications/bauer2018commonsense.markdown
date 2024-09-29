---
layout: publication
title: Commonsense For Generative Multi45;hop Question Answering Tasks
authors: Bauer Lisa, Wang Yicheng, Bansal Mohit
conference: "Arxiv"
year: 2018
bibkey: bauer2018commonsense
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1809.06309"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'Transformer']
---
Reading comprehension QA tasks have seen a recent surge in popularity yet most works have focused on fact45;finding extractive QA. We instead focus on a more challenging multi45;hop generative task (NarrativeQA) which requires the model to reason gather and synthesize disjoint pieces of information within the context to generate an answer. This type of multi45;step reasoning also often requires understanding implicit relations which humans resolve via external background commonsense knowledge. We first present a strong generative baseline that uses a multi45;attention mechanism to perform multiple hops of reasoning and a pointer45;generator decoder to synthesize the answer. This model performs substantially better than previous generative models and is competitive with current state45;of45;the45;art span prediction models. We next introduce a novel system for selecting grounded multi45;hop relational commonsense information from ConceptNet via a pointwise mutual information and term45;frequency based scoring function. Finally we effectively use this extracted commonsense information to fill in gaps of reasoning between context hops using a selectively45;gated attention mechanism. This boosts the models performance significantly (also verified via human evaluation) establishing a new state45;of45;the45;art for the task. We also show promising initial results of the generalizability of our background knowledge enhancements by demonstrating some improvement on QAngaroo45;WikiHop another multi45;hop reasoning dataset.
