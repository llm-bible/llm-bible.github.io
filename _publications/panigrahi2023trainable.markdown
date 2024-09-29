---
layout: publication
title: Trainable Transformer In Transformer
authors: Panigrahi Abhishek, Malladi Sadhika, Xia Mengzhou, Arora Sanjeev
conference: "Arxiv"
year: 2023
bibkey: panigrahi2023trainable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.01189"}
tags: ['Efficiency And Optimization', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Transformer']
---
Recent works attribute the capability of in45;context learning (ICL) in large pre45;trained language models to implicitly simulating and fine45;tuning an internal model (e.g. linear or 245;layer MLP) during inference. However such constructions require large memory overhead which makes simulation of more sophisticated internal models intractable. In this work we propose an efficient construction Transformer in Transformer (in short TinT) that allows a transformer to simulate and fine45;tune complex models internally during inference (e.g. pre45;trained language models). In particular we introduce innovative approximation techniques that allow a TinT model with less than 2 billion parameters to simulate and fine45;tune a 125 million parameter transformer model within a single forward pass. TinT accommodates many common transformer variants and its design ideas also improve the efficiency of past instantiations of simple models inside transformers. We conduct end45;to45;end experiments to validate the internal fine45;tuning procedure of TinT on various language modeling and downstream tasks. For example even with a limited one45;step budget we observe TinT for a OPT45;125M model improves performance by 445;1637; absolute on average compared to OPT45;125M. These findings suggest that large pre45;trained language models are capable of performing intricate subroutines. To facilitate further work a modular and extensible codebase for TinT is included.
