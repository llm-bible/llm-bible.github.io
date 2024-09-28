---
layout: publication
title: On the Sub-Layer Functionalities of Transformer Decoder
authors: Yang Yilin, Wang Longyue, Shi Shuming, Tadepalli Prasad, Lee Stefan, Tu Zhaopeng
conference: "Arxiv"
year: 2020
bibkey: yang2020sub
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2010.02648"}
tags: ['ARXIV', 'Model Architecture', 'Transformer', 'WMT']
---
There have been significant efforts to interpret the encoder of Transformer-based encoder-decoder architectures for neural machine translation (NMT); meanwhile the decoder remains largely unexamined despite its critical role. During translation the decoder must predict output tokens by considering both the source-language text from the encoder and the target-language prefix produced in previous steps. In this work we study how Transformer-based decoders leverage information from the source and target languages -- developing a universal probe task to assess how information is propagated through each module of each decoder layer. We perform extensive experiments on three major translation datasets (WMT En-De En-Fr and En-Zh). Our analysis provides insight on when and where decoders leverage different sources. Based on these insights we demonstrate that the residual feed-forward module in each Transformer decoder layer can be dropped with minimal loss of performance -- a significant reduction in computation and number of parameters and consequently a significant boost to both training and inference speed.
