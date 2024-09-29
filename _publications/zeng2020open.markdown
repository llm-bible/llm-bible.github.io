---
layout: publication
title: Open45;domain Dialogue Generation Based On Pre45;trained Language Models
authors: Zeng Yan, Nie Jian-yun
conference: "Arxiv"
year: 2020
bibkey: zeng2020open
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2010.12780"}
tags: ['Attention Mechanism', 'BERT', 'Masked Language Model', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Tools', 'Transformer']
---
Pre45;trained language models have been successfully used in response generation for open45;domain dialogue. Four main frameworks have been proposed (1) Transformer45;ED using Transformer encoder and decoder separately for source and target sentences; (2) Transformer45;Dec using Transformer decoder for both source and target sentences; (3) Transformer45;MLM using Transformer decoder that applies bi45;directional attention on the source side and left45;to45;right attention on the target side with masked language model objective; and (4) Transformer45;AR that uses auto45;regressive objective instead. In this study we compare these frameworks on 3 datasets and our comparison reveals that the best framework uses bidirectional attention on the source side and does not separate encoder and decoder. We also examine model discrepancy and our experiments confirm that the performance of a model is directly impacted by the underlying discrepancies. We then propose two correction methods to reduce the discrepancies and both improve the model performance. These results show that discrepancies is an important factor to consider when we use a pre45;trained model and a reduction in discrepancies can lead to improved performance.
