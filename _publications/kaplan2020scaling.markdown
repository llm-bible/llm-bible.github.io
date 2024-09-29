---
layout: publication
title: Scaling Laws For Neural Language Models
authors: Jared Kaplan, Sam Mccandlish, Tom Henighan, Tom B. Brown, Benjamin Chess, Rewon Child, Scott Gray, Alec Radford, Jeffrey Wu, Dario Amodei
conference: "Arxiv"
year: 2020
bibkey: kaplan2020scaling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2001.08361v1"}
tags: ['Efficiency And Optimization', 'Large Scale Training', 'Model Architecture', 'Scaling Laws', 'Training Techniques']
---
We study empirical scaling laws for language model performance on the cross45;entropy loss. The loss scales as a power45;law with model size dataset size and the amount of compute used for training with some trends spanning more than seven orders of magnitude. Other architectural details such as network width or depth have minimal effects within a wide range. Simple equations govern the dependence of overfitting on model/dataset size and the dependence of training speed on model size. These relationships allow us to determine the optimal allocation of a fixed compute budget. Larger models are significantly more sample45;efficient such that optimally compute45;efficient training involves training very large models on a relatively modest amount of data and stopping significantly before convergence.
