---
layout: publication
title: On The Sub45;layer Functionalities Of Transformer Decoder
authors: Yang Yilin, Wang Longyue, Shi Shuming, Tadepalli Prasad, Lee Stefan, Tu Zhaopeng
conference: "Arxiv"
year: 2020
bibkey: yang2020sub
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2010.02648"}
tags: ['Applications', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Training Techniques', 'Transformer']
---
There have been significant efforts to interpret the encoder of Transformer45;based encoder45;decoder architectures for neural machine translation (NMT); meanwhile the decoder remains largely unexamined despite its critical role. During translation the decoder must predict output tokens by considering both the source45;language text from the encoder and the target45;language prefix produced in previous steps. In this work we study how Transformer45;based decoders leverage information from the source and target languages 45;45; developing a universal probe task to assess how information is propagated through each module of each decoder layer. We perform extensive experiments on three major translation datasets (WMT En45;De En45;Fr and En45;Zh). Our analysis provides insight on when and where decoders leverage different sources. Based on these insights we demonstrate that the residual feed45;forward module in each Transformer decoder layer can be dropped with minimal loss of performance 45;45; a significant reduction in computation and number of parameters and consequently a significant boost to both training and inference speed.
