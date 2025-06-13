---
layout: publication
title: 'Mechanistic Design And Scaling Of Hybrid Architectures'
authors: Michael Poli, Armin W Thomas, Eric Nguyen, Pragaash Ponnusamy, Björn Deiseroth, Kristian Kersting, Taiji Suzuki, Brian Hie, Stefano Ermon, Christopher Ré, Ce Zhang, Stefano Massaroli
conference: "Arxiv"
year: 2024
bibkey: poli2024mechanistic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.17844"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Scaling Laws', 'RAG', 'Pretraining Methods', 'Large-Scale Training', 'Transformer', 'Pre-Training']
---
The development of deep learning architectures is a resource-demanding
process, due to a vast design space, long prototyping times, and high compute
costs associated with at-scale model training and evaluation. We set out to
simplify this process by grounding it in an end-to-end mechanistic architecture
design (MAD) pipeline, encompassing small-scale capability unit tests
predictive of scaling laws. Through a suite of synthetic token manipulation
tasks such as compression and recall, designed to probe capabilities, we
identify and test new hybrid architectures constructed from a variety of
computational primitives. We experimentally validate the resulting
architectures via an extensive compute-optimal and a new state-optimal scaling
law analysis, training over 500 language models between 70M to 7B parameters.
Surprisingly, we find MAD synthetics to correlate with compute-optimal
perplexity, enabling accurate evaluation of new architectures via isolated
proxy tasks. The new architectures found via MAD, based on simple ideas such as
hybridization and sparsity, outperform state-of-the-art Transformer,
convolutional, and recurrent architectures (Transformer++, Hyena, Mamba) in
scaling, both at compute-optimal budgets and in overtrained regimes. Overall,
these results provide evidence that performance on curated synthetic tasks can
be predictive of scaling laws, and that an optimal architecture should leverage
specialized layers via a hybrid topology.
