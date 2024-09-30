---
layout: publication
title: 'Training Multilingual Machine Translation By Alternately Freezing Language-specific Encoders-decoders'
authors: Escolano Carlos, Costa-jussà Marta R., Fonollosa José A. R., Artetxe Mikel
conference: "Arxiv"
year: 2020
bibkey: escolano2020training
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2006.01594"}
tags: ['Applications', 'Model Architecture', 'Training Techniques']
---
We propose a modular architecture of language-specific encoder-decoders that constitutes a multilingual machine translation system that can be incrementally extended to new languages without the need for retraining the existing system when adding new languages. Differently from previous works we simultaneously train (N) languages in all translation directions by alternately freezing encoder or decoder modules which indirectly forces the system to train in a common intermediate representation for all languages. Experimental results from multilingual machine translation show that we can successfully train this modular architecture improving on the initial languages while falling slightly behind when adding new languages or doing zero-shot translation. Additional comparison of the quality of sentence representation in the task of natural language inference shows that the alternately freezing training is also beneficial in this direction.
