---
layout: publication
title: A Corpus-free State2seq User Simulator For Task-oriented Dialogue
authors: Hou Yutai, Fang Meng, Che Wanxiang, Liu Ting
conference: "Arxiv"
year: 2019
bibkey: hou2019corpus
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1909.04448"}
tags: ['Agentic', 'RAG', 'Reinforcement Learning', 'TACL', 'Tools', 'Training Techniques']
---
Recent reinforcement learning algorithms for task-oriented dialogue system absorbs a lot of interest. However an unavoidable obstacle for training such algorithms is that annotated dialogue corpora are often unavailable. One of the popular approaches addressing this is to train a dialogue agent with a user simulator. Traditional user simulators are built upon a set of dialogue rules and therefore lack response diversity. This severely limits the simulated cases for agent training. Later data-driven user models work better in diversity but suffer from data scarcity problem. To remedy this we design a new corpus-free framework that taking advantage of their benefits. The framework builds a user simulator by first generating diverse dialogue data from templates and then build a new State2Seq user simulator on the data. To enhance the performance we propose the State2Seq user simulator model to efficiently leverage dialogue state and history. Experiment results on an open dataset show that our user simulator helps agents achieve an improvement of 6.3637; on success rate. State2Seq model outperforms the seq2seq baseline for 1.9 F-score.
