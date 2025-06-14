---
layout: publication
title: 'Text Generation With Exemplar-based Adaptive Decoding'
authors: Hao Peng, Ankur P. Parikh, Manaal Faruqui, Bhuwan Dhingra, Dipanjan Das
conference: "Arxiv"
year: 2019
citations: 54
bibkey: peng2019text
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/1904.04428'}
tags: ['Language Modeling', 'Applications', 'Training Techniques']
---
We propose a novel conditioned text generation model. It draws inspiration
from traditional template-based text generation techniques, where the source
provides the content (i.e., what to say), and the template influences how to
say it. Building on the successful encoder-decoder paradigm, it first encodes
the content representation from the given input text; to produce the output, it
retrieves exemplar text from the training data as "soft templates," which are
then used to construct an exemplar-specific decoder. We evaluate the proposed
model on abstractive text summarization and data-to-text generation. Empirical
results show that this model achieves strong performance and outperforms
comparable baselines.
