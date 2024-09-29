---
layout: publication
title: Transformer45;xl Attentive Language Models Beyond A Fixed45;length Context
authors: Dai Zihang, Yang Zhilin, Yang Yiming, Carbonell Jaime, Le Quoc V., Salakhutdinov Ruslan
conference: "Arxiv"
year: 2019
bibkey: dai2019transformer
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1901.02860"}
tags: ['Language Modeling', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Transformer']
---
Transformers have a potential of learning longer45;term dependency but are limited by a fixed45;length context in the setting of language modeling. We propose a novel neural architecture Transformer45;XL that enables learning dependency beyond a fixed length without disrupting temporal coherence. It consists of a segment45;level recurrence mechanism and a novel positional encoding scheme. Our method not only enables capturing longer45;term dependency but also resolves the context fragmentation problem. As a result Transformer45;XL learns dependency that is 8037; longer than RNNs and 45037; longer than vanilla Transformers achieves better performance on both short and long sequences and is up to 1800+ times faster than vanilla Transformers during evaluation. Notably we improve the state45;of45;the45;art results of bpc/perplexity to 0.99 on enwiki8 1.08 on text8 18.3 on WikiText45;103 21.8 on One Billion Word and 54.5 on Penn Treebank (without finetuning). When trained only on WikiText45;103 Transformer45;XL manages to generate reasonably coherent novel text articles with thousands of tokens. Our code pretrained models and hyperparameters are available in both Tensorflow and PyTorch.
