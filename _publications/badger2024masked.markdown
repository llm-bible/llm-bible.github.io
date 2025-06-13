---
layout: publication
title: 'Masked Mixers For Language Generation And Retrieval'
authors: Benjamin L. Badger
conference: "Arxiv"
year: 2024
bibkey: badger2024masked
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.01482"}
tags: ['Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'Language Modeling', 'Pretraining Methods', 'Transformer', 'Attention Mechanism']
---
Attention mechanisms that confer selective focus on a strict subset of input
elements are nearly ubiquitous in language models today. We posit there to be
downside to the use of attention: most input information is lost. In support of
this idea we observe poor input representation accuracy in transformers and
more accurate representation in what we term masked mixers, which replace
self-attention with masked convolutions. The masked mixer learns causal
language modeling more efficiently than early transformer implementations and
even outperforms optimized, current transformers when training on small
(\\(n_\{ctx\}<512\\)) but not larger context windows. Evidence is presented for the
hypothesis that differences in transformer and masked mixer training
efficiencies for various tasks are best predicted by input representation
accuracy, or equivalently global invertibility. We hypothesize that the
information loss exhibited by transformers would be more detrimental to
retrieval than generation, as the former is more closely approximated by a
bijective and thus invertible function. We find that masked mixers are more
effective retrieval models both when the pretrained embedding model is
unchanged as well as when the embedding model is modified via cosine
similarity-based InfoNCE loss minimization. A small masked mixer is shown to
outperform a large and near state-of-the-art transformer-based retrieval model,
despite the latter being trained with many orders of magnitude more data and
compute.
