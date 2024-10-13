---
layout: publication
title: 'Integrated Triaging For Fast Reading Comprehension'
authors: Wu Felix, Li Boyi, Wang Lequn, Lao Ni, Blitzer John, Weinberger Kilian Q.
conference: "Arxiv"
year: 2019
bibkey: wu2019integrated
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1909.13128"}
tags: ['Applications', 'Attention Mechanism', 'Efficiency And Optimization', 'Model Architecture', 'Pruning', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Although according to several benchmarks automatic machine reading
comprehension (MRC) systems have recently reached super-human performance, less
attention has been paid to their computational efficiency. However, efficiency
is of crucial importance for training and deployment in real world
applications. This paper introduces Integrated Triaging, a framework that
prunes almost all context in early layers of a network, leaving the remaining
(deep) layers to scan only a tiny fraction of the full corpus. This pruning
drastically increases the efficiency of MRC models and further prevents the
later layers from overfitting to prevalent short paragraphs in the training
set. Our framework is extremely flexible and naturally applicable to a wide
variety of models. Our experiment on doc-SQuAD and TriviaQA tasks demonstrates
its effectiveness in consistently improving both speed and quality of several
diverse MRC models.
