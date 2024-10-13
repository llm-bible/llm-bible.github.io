---
layout: publication
title: 'Charbert: Character-aware Pre-trained Language Model'
authors: Ma Wentao, Cui Yiming, Si Chenglei, Liu Ting, Wang Shijin, Hu Guoping
conference: "Arxiv"
year: 2020
bibkey: ma2020character
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2011.01513"}
  - {name: "Code", url: "https://github.com/wtma/CharBERT"}
tags: ['Applications', 'BERT', 'Has Code', 'Model Architecture', 'RAG', 'Security', 'Training Techniques']
---
Most pre-trained language models (PLMs) construct word representations at
subword level with Byte-Pair Encoding (BPE) or its variations, by which OOV
(out-of-vocab) words are almost avoidable. However, those methods split a word
into subword units and make the representation incomplete and fragile. In this
paper, we propose a character-aware pre-trained language model named CharBERT
improving on the previous methods (such as BERT, RoBERTa) to tackle these
problems. We first construct the contextual word embedding for each token from
the sequential character representations, then fuse the representations of
characters and the subword representations by a novel heterogeneous interaction
module. We also propose a new pre-training task named NLM (Noisy LM) for
unsupervised character representation learning. We evaluate our method on
question answering, sequence labeling, and text classification tasks, both on
the original datasets and adversarial misspelling test sets. The experimental
results show that our method can significantly improve the performance and
robustness of PLMs simultaneously. Pretrained models, evaluation sets, and code
are available at https://github.com/wtma/CharBERT
