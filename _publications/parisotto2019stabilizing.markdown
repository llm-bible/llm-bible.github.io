---
layout: publication
title: 'Stabilizing Transformers For Reinforcement Learning'
authors: Parisotto Emilio, Song H. Francis, Rae Jack W., Pascanu Razvan, Gulcehre Caglar, Jayakumar Siddhant M., Jaderberg Max, Kaufman Raphael Lopez, Clark Aidan, Noury Seb, Botvinick Matthew M., Heess Nicolas, Hadsell Raia
conference: "Arxiv"
year: 2019
bibkey: parisotto2019stabilizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1910.06764"}
tags: ['Agentic', 'Applications', 'Attention Mechanism', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Transformer']
---
Owing to their ability to both effectively integrate information over long
time horizons and scale to massive amounts of data, self-attention
architectures have recently shown breakthrough success in natural language
processing (NLP), achieving state-of-the-art results in domains such as
language modeling and machine translation. Harnessing the transformer's ability
to process long time horizons of information could provide a similar
performance boost in partially observable reinforcement learning (RL) domains,
but the large-scale transformers used in NLP have yet to be successfully
applied to the RL setting. In this work we demonstrate that the standard
transformer architecture is difficult to optimize, which was previously
observed in the supervised learning setting but becomes especially pronounced
with RL objectives. We propose architectural modifications that substantially
improve the stability and learning speed of the original Transformer and XL
variant. The proposed architecture, the Gated Transformer-XL (GTrXL), surpasses
LSTMs on challenging memory environments and achieves state-of-the-art results
on the multi-task DMLab-30 benchmark suite, exceeding the performance of an
external memory architecture. We show that the GTrXL, trained using the same
losses, has stability and performance that consistently matches or exceeds a
competitive LSTM baseline, including on more reactive tasks where memory is
less critical. GTrXL offers an easy-to-train, simple-to-implement but
substantially more expressive architectural alternative to the standard
multi-layer LSTM ubiquitously used for RL agents in partially observable
environments.
