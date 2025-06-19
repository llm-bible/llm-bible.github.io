---
layout: publication
title: 'Single Headed Attention RNN: Stop Thinking With Your Head'
authors: Stephen Merity
conference: Arxiv
year: 2019
citations: 58
bibkey: merity2019single
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1911.11423'}]
tags: [Language Modeling, Efficiency and Optimization, Attention Mechanism]
---
The leading approaches in language modeling are all obsessed with TV shows of
my youth - namely Transformers and Sesame Street. Transformers this,
Transformers that, and over here a bonfire worth of GPU-TPU-neuromorphic wafer
scale silicon. We opt for the lazy path of old and proven techniques with a
fancy crypto inspired acronym: the Single Headed Attention RNN (SHA-RNN). The
author's lone goal is to show that the entire field might have evolved a
different direction if we had instead been obsessed with a slightly different
acronym and slightly different result. We take a previously strong language
model based only on boring LSTMs and get it to within a stone's throw of a
stone's throw of state-of-the-art byte level language model results on enwik8.
This work has undergone no intensive hyperparameter optimization and lived
entirely on a commodity desktop machine that made the author's small studio
apartment far too warm in the midst of a San Franciscan summer. The final
results are achievable in plus or minus 24 hours on a single GPU as the author
is impatient. The attention mechanism is also readily extended to large
contexts with minimal computation. Take that Sesame Street.