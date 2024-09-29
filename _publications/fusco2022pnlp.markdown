---
layout: publication
title: Pnlp-mixer: An Efficient All-mlp Architecture For Language
authors: Fusco Francesco, Pascual Damian, Staar Peter, Antognini Diego
conference: "Arxiv"
year: 2022
bibkey: fusco2022pnlp
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2202.04350"}
tags: ['Applications', 'BERT', 'Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
Large pre-trained language models based on transformer architecture have drastically changed the natural language processing (NLP) landscape. However deploying those models for on-device applications in constrained devices such as smart watches is completely impractical due to their size and inference cost. As an alternative to transformer-based architectures recent work on efficient NLP has shown that weight-efficient models can attain competitive performance for simple tasks such as slot filling and intent classification with model sizes in the order of the megabyte. This work introduces the pNLP-Mixer architecture an embedding-free MLP-Mixer model for on-device NLP that achieves high weight-efficiency thanks to a novel projection layer. We evaluate a pNLP-Mixer model of only one megabyte in size on two multi-lingual semantic parsing datasets MTOP and multiATIS. Our quantized model achieves 99.437; and 97.837; the performance of mBERT on MTOP and multi-ATIS while using 170x fewer parameters. Our model consistently beats the state-of-the-art of tiny models (pQRNN) which is twice as large by a margin up to 7.837; on MTOP.
