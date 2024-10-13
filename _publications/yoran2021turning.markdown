---
layout: publication
title: 'Turning Tables: Generating Examples From Semi-structured Tables For Endowing Language Models With Reasoning Skills'
authors: Yoran Ori, Talmor Alon, Berant Jonathan
conference: "Arxiv"
year: 2021
bibkey: yoran2021turning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2107.07261"}
tags: ['Efficiency And Optimization', 'Language Modeling', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Uncategorized']
---
Models pre-trained with a language modeling objective possess ample world
knowledge and language skills, but are known to struggle in tasks that require
reasoning. In this work, we propose to leverage semi-structured tables, and
automatically generate at scale question-paragraph pairs, where answering the
question requires reasoning over multiple facts in the paragraph. We add a
pre-training step over this synthetic data, which includes examples that
require 16 different reasoning skills such as number comparison, conjunction,
and fact composition. To improve data efficiency, we propose sampling
strategies that focus training on reasoning skills the model is currently
lacking. We evaluate our approach on three reading comprehension datasets that
are focused on reasoning, and show that our model, PReasM, substantially
outperforms T5, a popular pre-trained encoder-decoder model. Moreover, sampling
examples based on current model errors leads to faster training and higher
overall performance.
