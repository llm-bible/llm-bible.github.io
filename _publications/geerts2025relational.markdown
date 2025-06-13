---
layout: publication
title: 'Relational Reasoning And Inductive Bias In Transformers Trained On A Transitive Inference Task'
authors: Jesse Geerts, Stephanie Chan, Claudia Clopath, Kimberly Stachenfeld
conference: "Arxiv"
year: 2025
bibkey: geerts2025relational
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.04289"}
tags: ['Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'Ethics and Bias', 'Pretraining Methods', 'Transformer', 'Prompting', 'Pre-Training', 'In-Context Learning']
---
Transformer-based models have demonstrated remarkable reasoning abilities, but the mechanisms underlying relational reasoning in different learning regimes remain poorly understood. In this work, we investigate how transformers perform a classic relational reasoning task from the Psychology literature, \textit\{transitive inference\}, which requires inference about indirectly related items by integrating information across observed adjacent item pairs (e.g., if A>B and B>C, then A>C). We compare transitive inference behavior across two distinct learning regimes: in-weights learning (IWL), where models store information in network parameters, and in-context learning (ICL), where models flexibly utilize information presented within the input sequence. Our findings reveal that IWL naturally induces a generalization bias towards transitive inference, despite being trained only on adjacent items, whereas ICL models trained solely on adjacent items do not generalize transitively. Mechanistic analysis shows that ICL models develop induction circuits that implement a simple match-and-copy strategy that performs well at relating adjacent pairs, but does not encoding hierarchical relationships among indirectly related items. Interestingly, when pre-trained on in-context linear regression tasks, transformers successfully exhibit in-context generalizable transitive inference. Moreover, like IWL, they display both \textit\{symbolic distance\} and \textit\{terminal item effects\} characteristic of human and animal performance, without forming induction circuits. These results suggest that pre-training on tasks with underlying structure promotes the development of representations that can scaffold in-context relational reasoning.
