---
layout: publication
title: Convert&#58; Efficient And Accurate Conversational Representations From Transformers
authors: Henderson Matthew, Casanueva Iñigo, Mrkšić Nikola, Su Pei-hao, Wen Tsung-hsien, Vulić Ivan
conference: "Arxiv"
year: 2019
bibkey: henderson2019efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1911.03688"}
tags: ['Applications', 'BERT', 'Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Quantization', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques', 'Transformer']
---
General-purpose pretrained sentence encoders such as BERT are not ideal for real-world conversational AI applications; they are computationally heavy slow and expensive to train. We propose ConveRT (Conversational Representations from Transformers) a pretraining framework for conversational tasks satisfying all the following requirements it is effective affordable and quick to train. We pretrain using a retrieval-based response selection task effectively leveraging quantization and subword-level parameterization in the dual encoder to build a lightweight memory- and energy-efficient model. We show that ConveRT achieves state-of-the-art performance across widely established response selection tasks. We also demonstrate that the use of extended dialog history as context yields further performance gains. Finally we show that pretrained representations from the proposed encoder can be transferred to the intent classification task yielding strong results across three diverse data sets. ConveRT trains substantially faster than standard sentence encoders or previous state-of-the-art dual encoders. With its reduced size and superior performance we believe this model promises wider portability and scalability for Conversational AI applications.
