---
layout: publication
title: Unveiling Transformers With LEGO: A Synthetic Reasoning Task
authors: Zhang Yi, Backurs Arturs, Bubeck Sébastien, Eldan Ronen, Gunasekar Suriya, Wagner Tal
conference: "Arxiv"
year: 2022
bibkey: zhang2022unveiling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2206.04301"}
tags: ['Attention Mechanism', 'Model Architecture', 'Pretraining Methods', 'Security', 'Training Techniques', 'Transformer']
---
We propose a synthetic reasoning task LEGO (Learning Equality and Group Operations) that encapsulates the problem of following a chain of reasoning and we study how the Transformer architectures learn this task. We pay special attention to data effects such as pretraining (on seemingly unrelated NLP tasks) and dataset composition (e.g. differing chain length at training and test time) as well as architectural variants such as weight-tied layers or adding convolutional components. We study how the trained models eventually succeed at the task and in particular we manage to understand some of the attention heads as well as how the information flows in the network. In particular we have identified a novel (emphassociation) pattern that globally attends only to identical tokens. Based on these observations we propose a hypothesis that here pretraining helps for LEGO tasks due to certain structured attention patterns and we experimentally verify this hypothesis. We also observe that in some data regime the trained transformer finds shortcut solutions to follow the chain of reasoning which impedes the models robustness and moreover we propose ways to prevent it. Motivated by our findings on structured attention patterns we propose the LEGO attention module a drop-in replacement for vanilla attention heads. This architectural change significantly reduces Flops and maintains or even (emphimproves) the models performance at large-scale pretraining.
