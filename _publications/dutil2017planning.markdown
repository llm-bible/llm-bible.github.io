---
layout: publication
title: 'Plan, Attend, Generate: Planning For Sequence-to-sequence Models'
authors: Francis Dutil, Caglar Gulcehre, Adam Trischler, Yoshua Bengio
conference: "Arxiv"
year: 2017
bibkey: dutil2017planning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1711.10462"}
tags: ['Agentic', 'Model Architecture', 'WMT', 'Reinforcement Learning', 'Attention Mechanism']
---
We investigate the integration of a planning mechanism into
sequence-to-sequence models using attention. We develop a model which can plan
ahead in the future when it computes its alignments between input and output
sequences, constructing a matrix of proposed future alignments and a commitment
vector that governs whether to follow or recompute the plan. This mechanism is
inspired by the recently proposed strategic attentive reader and writer (STRAW)
model for Reinforcement Learning. Our proposed model is end-to-end trainable
using primarily differentiable operations. We show that it outperforms a strong
baseline on character-level translation tasks from WMT'15, the algorithmic task
of finding Eulerian circuits of graphs, and question generation from the text.
Our analysis demonstrates that the model computes qualitatively intuitive
alignments, converges faster than the baselines, and achieves superior
performance with fewer parameters.
