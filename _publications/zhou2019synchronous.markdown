---
layout: publication
title: Synchronous Bidirectional Neural Machine Translation
authors: Zhou Long, Zhang Jiajun, Zong Chengqing
conference: "Arxiv"
year: 2019
bibkey: zhou2019synchronous
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1905.04847"}
tags: ['Applications', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Tools', 'Transformer']
---
Existing approaches to neural machine translation (NMT) generate the target language sequence token by token from left to right. However this kind of unidirectional decoding framework cannot make full use of the target45;side future contexts which can be produced in a right45;to45;left decoding direction and thus suffers from the issue of unbalanced outputs. In this paper we introduce a synchronous bidirectional neural machine translation (SB45;NMT) that predicts its outputs using left45;to45;right and right45;to45;left decoding simultaneously and interactively in order to leverage both of the history and future information at the same time. Specifically we first propose a new algorithm that enables synchronous bidirectional decoding in a single model. Then we present an interactive decoding model in which left45;to45;right (right45;to45;left) generation does not only depend on its previously generated outputs but also relies on future contexts predicted by right45;to45;left (left45;to45;right) decoding. We extensively evaluate the proposed SB45;NMT model on large45;scale NIST Chinese45;English WMT14 English45;German and WMT18 Russian45;English translation tasks. Experimental results demonstrate that our model achieves significant improvements over the strong Transformer model by 3.92 1.49 and 1.04 BLEU points respectively and obtains the state45;of45;the45;art performance on Chinese45;English and English45;German translation tasks.
