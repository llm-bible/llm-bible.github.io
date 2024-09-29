---
layout: publication
title: The Hydra Effect Emergent Self-repair in Language Model Computations
authors: Mcgrath Thomas, Rahtz Matthew, Kramar Janos, Mikulik Vladimir, Legg Shane
conference: "Arxiv"
year: 2023
bibkey: mcgrath2023hydra
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.15771"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Model Architecture']
---
We investigate the internal structure of language model computations using causal analysis and demonstrate two motifs (1) a form of adaptive computation where ablations of one attention layer of a language model cause another layer to compensate (which we term the Hydra effect) and (2) a counterbalancing function of late MLP layers that act to downregulate the maximum-likelihood token. Our ablation studies demonstrate that language model layers are typically relatively loosely coupled (ablations to one layer only affect a small number of downstream layers). Surprisingly these effects occur even in language models trained without any form of dropout. We analyse these effects in the context of factual recall and consider their implications for circuit-level attribution in language models.
