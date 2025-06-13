---
layout: publication
title: 'Training Tips For The Transformer Model'
authors: Martin Popel, Ondřej Bojar
conference: "The Prague Bulletin of Mathematical Linguistics 110 April 2018 pp. 43-70"
year: 2018
bibkey: popel2018training
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1804.00247"}
tags: ['Training Techniques', 'Model Architecture', 'Tools', 'RAG', 'Pretraining Methods', 'Transformer', 'Applications']
---
This article describes our experiments in neural machine translation using
the recent Tensor2Tensor framework and the Transformer sequence-to-sequence
model (Vaswani et al., 2017). We examine some of the critical parameters that
affect the final translation quality, memory usage, training stability and
training time, concluding each experiment with a set of recommendations for
fellow researchers. In addition to confirming the general mantra "more data and
larger models", we address scaling to multiple GPUs and provide practical tips
for improved training regarding batch size, learning rate, warmup steps,
maximum sentence length and checkpoint averaging. We hope that our observations
will allow others to get better results given their particular hardware and
data constraints.
