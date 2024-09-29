---
layout: publication
title: Hard45;coded Gaussian Attention For Neural Machine Translation
authors: You Weiqiu, Sun Simeng, Iyyer Mohit
conference: "Arxiv"
year: 2020
bibkey: you2020hard
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2005.00742"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
Recent work has questioned the importance of the Transformers multi45;headed attention for achieving high translation quality. We push further in this direction by developing a hard45;coded attention variant without any learned parameters. Surprisingly replacing all learned self45;attention heads in the encoder and decoder with fixed input45;agnostic Gaussian distributions minimally impacts BLEU scores across four different language pairs. However additionally hard45;coding cross attention (which connects the decoder to the encoder) significantly lowers BLEU suggesting that it is more important than self45;attention. Much of this BLEU drop can be recovered by adding just a single learned cross attention head to an otherwise hard45;coded Transformer. Taken as a whole our results offer insight into which components of the Transformer are actually important which we hope will guide future work into the development of simpler and more efficient attention45;based models.
