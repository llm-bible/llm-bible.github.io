---
layout: publication
title: Memory Attentive Fusion External Language Model Integration for Transformer-based Sequence-to-Sequence Model
authors: Ihori Mana, Masumura Ryo, Makishima Naoki, Tanaka Tomohiro, Takashima Akihiko, Orihashi Shota
conference: "Arxiv"
year: 2020
bibkey: ihori2020memory
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2010.15437"}
tags: ['Attention Mechanism', 'Merging', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Transformer']
---
This paper presents a novel fusion method for integrating an external language model (LM) into the Transformer based sequence-to-sequence (seq2seq) model. While paired data are basically required to train the seq2seq model the external LM can be trained with only unpaired data. Thus it is important to leverage memorized knowledge in the external LM for building the seq2seq model since it is hard to prepare a large amount of paired data. However the existing fusion methods assume that the LM is integrated with recurrent neural network-based seq2seq models instead of the Transformer. Therefore this paper proposes a fusion method that can explicitly utilize network structures in the Transformer. The proposed method called memory attentive fusion leverages the Transformer-style attention mechanism that repeats source-target attention in a multi-hop manner for reading the memorized knowledge in the LM. Our experiments on two text-style conversion tasks demonstrate that the proposed method performs better than conventional fusion methods.
