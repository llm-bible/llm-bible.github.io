---
layout: publication
title: 'GOLD: Generalized Knowledge Distillation Via Out-of-distribution-guided Language Data Generation'
authors: Mohsen Gholami, Mohammad Akbari, Cindy Hu, Vaden Masrani, Z. Jane Wang, Yong Zhang
conference: "Arxiv"
year: 2024
bibkey: gholami2024generalized
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.19754"}
tags: ['Efficiency and Optimization', 'Tools', 'Reinforcement Learning', 'RAG', 'Distillation']
---
Knowledge distillation from LLMs is essential for the efficient deployment of
language models. Prior works have proposed data generation using LLMs for
preparing distilled models. We argue that generating data with LLMs is prone to
sampling mainly from the center of original content distribution. This
limitation hinders the distilled model from learning the true underlying data
distribution and to forget the tails of the distributions (samples with lower
probability). To this end, we propose GOLD, a task-agnostic data generation and
knowledge distillation framework, which employs an iterative
out-of-distribution-guided feedback mechanism for the LLM. As a result, the
generated data improves the generalizability of distilled models. An
energy-based OOD evaluation approach is also introduced to deal with noisy
generated data. Our extensive experiments on 10 different classification and
sequence-to-sequence tasks in NLP show that GOLD respectively outperforms prior
arts and the LLM with an average improvement of 5% and 14%. We will also show
that the proposed method is applicable to less explored and novel tasks. The
code is available.
