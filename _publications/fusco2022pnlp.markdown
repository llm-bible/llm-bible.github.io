---
layout: publication
title: Pnlp45;mixer An Efficient All45;mlp Architecture For Language
authors: Fusco Francesco, Pascual Damian, Staar Peter, Antognini Diego
conference: "Arxiv"
year: 2022
bibkey: fusco2022pnlp
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2202.04350"}
tags: ['Applications', 'BERT', 'Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
Large pre45;trained language models based on transformer architecture have drastically changed the natural language processing (NLP) landscape. However deploying those models for on45;device applications in constrained devices such as smart watches is completely impractical due to their size and inference cost. As an alternative to transformer45;based architectures recent work on efficient NLP has shown that weight45;efficient models can attain competitive performance for simple tasks such as slot filling and intent classification with model sizes in the order of the megabyte. This work introduces the pNLP45;Mixer architecture an embedding45;free MLP45;Mixer model for on45;device NLP that achieves high weight45;efficiency thanks to a novel projection layer. We evaluate a pNLP45;Mixer model of only one megabyte in size on two multi45;lingual semantic parsing datasets MTOP and multiATIS. Our quantized model achieves 99.437; and 97.837; the performance of mBERT on MTOP and multi45;ATIS while using 170x fewer parameters. Our model consistently beats the state45;of45;the45;art of tiny models (pQRNN) which is twice as large by a margin up to 7.837; on MTOP.
