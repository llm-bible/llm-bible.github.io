---
layout: publication
title: Self45;attentive Residual Decoder For Neural Machine Translation
authors: Werlen Lesly Miculicich, Pappas Nikolaos, Ram Dhananjay, Popescu-belis Andrei
conference: "Arxiv"
year: 2017
bibkey: werlen2017self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1709.04849"}
tags: ['Applications', 'Attention Mechanism', 'Ethics And Bias', 'Model Architecture', 'Transformer']
---
Neural sequence45;to45;sequence networks with attention have achieved remarkable performance for machine translation. One of the reasons for their effectiveness is their ability to capture relevant source45;side contextual information at each time45;step prediction through an attention mechanism. However the target45;side context is solely based on the sequence model which in practice is prone to a recency bias and lacks the ability to capture effectively non45;sequential dependencies among words. To address this limitation we propose a target45;side45;attentive residual recurrent network for decoding where attention over previous words contributes directly to the prediction of the next word. The residual learning facilitates the flow of information from the distant past and is able to emphasize any of the previously translated words hence it gains access to a wider context. The proposed model outperforms a neural MT baseline as well as a memory and self45;attention network on three language pairs. The analysis of the attention learned by the decoder confirms that it emphasizes a wider context and that it captures syntactic45;like structures.
