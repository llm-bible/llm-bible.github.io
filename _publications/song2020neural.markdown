---
layout: publication
title: 'Neural Machine Translation With Error Correction'
authors: Song Kaitao, Tan Xu, Lu Jianfeng
conference: "Arxiv"
year: 2020
bibkey: song2020neural
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2007.10681"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Training Techniques', 'Transformer']
---
Neural machine translation (NMT) generates the next target token given as
input the previous ground truth target tokens during training while the
previous generated target tokens during inference, which causes discrepancy
between training and inference as well as error propagation, and affects the
translation accuracy. In this paper, we introduce an error correction mechanism
into NMT, which corrects the error information in the previous generated tokens
to better predict the next token. Specifically, we introduce two-stream
self-attention from XLNet into NMT decoder, where the query stream is used to
predict the next token, and meanwhile the content stream is used to correct the
error information from the previous predicted tokens. We leverage scheduled
sampling to simulate the prediction errors during training. Experiments on
three IWSLT translation datasets and two WMT translation datasets demonstrate
that our method achieves improvements over Transformer baseline and scheduled
sampling. Further experimental analyses also verify the effectiveness of our
proposed error correction mechanism to improve the translation quality.
