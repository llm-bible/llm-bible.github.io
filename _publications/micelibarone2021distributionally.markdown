---
layout: publication
title: 'Distributionally Robust Recurrent Decoders With Random Network Distillation'
authors: Antonio Valerio Miceli-barone, Alexandra Birch, Rico Sennrich
conference: "Arxiv"
year: 2021
bibkey: micelibarone2021distributionally
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2110.13229"}
tags: ['Efficiency and Optimization', 'GPT', 'Applications', 'Language Modeling', 'Model Architecture', 'Training Techniques', 'Pretraining Methods', 'Distillation']
---
Neural machine learning models can successfully model language that is
similar to their training distribution, but they are highly susceptible to
degradation under distribution shift, which occurs in many practical
applications when processing out-of-domain (OOD) text. This has been attributed
to "shortcut learning": relying on weak correlations over arbitrary large
contexts.
  We propose a method based on OOD detection with Random Network Distillation
to allow an autoregressive language model to automatically disregard OOD
context during inference, smoothly transitioning towards a less expressive but
more robust model as the data becomes more OOD while retaining its full context
capability when operating in-distribution. We apply our method to a GRU
architecture, demonstrating improvements on multiple language modeling (LM)
datasets.
