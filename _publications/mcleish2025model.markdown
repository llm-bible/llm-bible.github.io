---
layout: publication
title: 'Gemstones: A Model Suite For Multi-faceted Scaling Laws'
authors: Sean Mcleish, John Kirchenbauer, David Yu Miller, Siddharth Singh, Abhinav Bhatele, Micah Goldblum, Ashwinee Panda, Tom Goldstein
conference: "Arxiv"
year: 2025
bibkey: mcleish2025model
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.06857"}
  - {name: "Code", url: "https://github.com/mcleish7/gemstone-scaling-laws"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Scaling Laws', 'Language Modeling', 'Pretraining Methods', 'Large-Scale Training', 'Transformer', 'Has Code', 'Pre-Training']
---
Scaling laws are typically fit using a family of models with a narrow range
of frozen hyper-parameter choices. In this work we study scaling laws using a
wide range of architecture and hyper-parameter choices, and highlight their
impact on resulting prescriptions. As a primary artifact of our research, we
release the Gemstones: the most comprehensive open-source scaling law dataset
to date, consisting of over 4000 checkpoints from transformers with up to 2
billion parameters; these models have been trained with different learning
rates, cooldown schedules, and architectural shapes. Our checkpoints enable
more complex studies of scaling, such as a law that predicts language modeling
performance as a function of model width and depth. By examining the various
facets of our model suite, we find that the prescriptions of scaling laws can
be highly sensitive to the experimental design process and the specific model
checkpoints used during fitting. Code:
https://github.com/mcleish7/gemstone-scaling-laws
