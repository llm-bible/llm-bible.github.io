---
layout: publication
title: Representation Deficiency In Masked Language Modeling
authors: Meng Yu, Krishnan Jitin, Wang Sinong, Wang Qifan, Mao Yuning, Fang Han, Ghazvininejad Marjan, Han Jiawei, Zettlemoyer Luke
conference: "Arxiv"
year: 2023
bibkey: meng2023representation
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2302.02060"}
tags: ['BERT', 'Language Modeling', 'Masked Language Model', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
Masked Language Modeling (MLM) has been one of the most prominent approaches for pretraining bidirectional text encoders due to its simplicity and effectiveness. One notable concern about MLM is that the special texttt123;MASK125; symbol causes a discrepancy between pretraining data and downstream data as it is present only in pretraining but not in fine45;tuning. In this work we offer a new perspective on the consequence of such a discrepancy We demonstrate empirically and theoretically that MLM pretraining allocates some model dimensions exclusively for representing texttt123;MASK125; tokens resulting in a representation deficiency for real tokens and limiting the pretrained models expressiveness when it is adapted to downstream data without texttt123;MASK125; tokens. Motivated by the identified issue we propose MAE45;LM which pretrains the Masked Autoencoder architecture with MLM where texttt123;MASK125; tokens are excluded from the encoder. Empirically we show that MAE45;LM improves the utilization of model dimensions for real token representations and MAE45;LM consistently outperforms MLM45;pretrained models across different pretraining settings and model sizes when fine45;tuned on the GLUE and SQuAD benchmarks.
