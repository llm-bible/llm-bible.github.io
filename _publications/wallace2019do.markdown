---
layout: publication
title: Do NLP Models Know Numbers Probing Numeracy In Embeddings
authors: Wallace Eric, Wang Yizhong, Li Sujian, Singh Sameer, Gardner Matt
conference: "Arxiv"
year: 2019
bibkey: wallace2019do
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1909.07940"}
tags: ['Applications', 'BERT', 'Model Architecture']
---
The ability to understand and work with numbers (numeracy) is critical for many complex reasoning tasks. Currently most NLP models treat numbers in text in the same way as other tokens45;45;45;they embed them as distributed vectors. Is this enough to capture numeracy We begin by investigating the numerical reasoning capabilities of a state45;of45;the45;art question answering model on the DROP dataset. We find this model excels on questions that require numerical reasoning i.e. it already captures numeracy. To understand how this capability emerges we probe token embedding methods (e.g. BERT GloVe) on synthetic list maximum number decoding and addition tasks. A surprising degree of numeracy is naturally present in standard embeddings. For example GloVe and word2vec accurately encode magnitude for numbers up to 1000. Furthermore character45;level embeddings are even more precise45;45;45;ELMo captures numeracy the best for all pre45;trained methods45;45;45;but BERT which uses sub45;word units is less exact.
