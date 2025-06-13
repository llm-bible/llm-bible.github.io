---
layout: publication
title: 'Healing Powers Of BERT: How Task-specific Fine-tuning Recovers Corrupted Language Models'
authors: Shijie Han, Zhenyu Zhang, Andrei Arsene Simion
conference: "Arxiv"
year: 2024
bibkey: han2024healing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.14459'}
tags: ['Security', 'Training Techniques', 'BERT', 'Model Architecture', 'Fine-Tuning', 'Pre-Training', 'Pretraining Methods']
---
Language models like BERT excel at sentence classification tasks due to
extensive pre-training on general data, but their robustness to parameter
corruption is unexplored. To understand this better, we look at what happens if
a language model is "broken", in the sense that some of its parameters are
corrupted and then recovered by fine-tuning. Strategically corrupting BERT
variants at different levels, we find corrupted models struggle to fully
recover their original performance, with higher corruption causing more severe
degradation. Notably, bottom-layer corruption affecting fundamental linguistic
features is more detrimental than top-layer corruption. Our insights contribute
to understanding language model robustness and adaptability under adverse
conditions, informing strategies for developing resilient NLP systems against
parameter perturbations.
