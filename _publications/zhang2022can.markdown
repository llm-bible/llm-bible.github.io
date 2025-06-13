---
layout: publication
title: 'Can Offline Reinforcement Learning Help Natural Language Understanding?'
authors: Ziqi Zhang, Yile Wang, Yue Zhang, Donglin Wang
conference: "Arxiv"
year: 2022
bibkey: zhang2022can
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2212.03864'}
tags: ['Agentic', 'Language Modeling', 'Transformer', 'Training Techniques', 'Model Architecture', 'Applications', 'Reinforcement Learning', 'Pre-Training', 'Pretraining Methods']
---
Pre-training has been a useful method for learning implicit transferable
knowledge and it shows the benefit of offering complementary features across
different modalities. Recent work mainly focuses on the modalities such as
image and text, for example, studies show that visual features learned from
images can help visual-grounded language understanding. In this paper, we
consider investigating the potential connection between offline reinforcement
learning (RL) and language modeling (LM). Intuitively, RL and LM are similar in
predicting the next states based on the current and previous states, which rely
on both local and long-range dependency across states. To validate such an
assumption, we pre-trained different offline RL tasks using Transformer and
then evaluate these models on various language-related tasks. Experimental
results show that our RL pre-trained models can give close performance compared
with the models using the LM training objective, showing that there exist
common useful features across these two modalities. To further explore the
potential relationship, we investigate some factors such as Markov property and
the sequential nature of RL trajectory.
