---
layout: publication
title: How Context Affects Language Models' Factual Predictions
authors: Fabio Petroni et al.
conference: Arxiv
year: 2020
citations: 85
bibkey: petroni2020how
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2005.04611'}]
tags: [Reinforcement Learning, BERT]
---
When pre-trained on large unsupervised textual corpora, language models are
able to store and retrieve factual knowledge to some extent, making it possible
to use them directly for zero-shot cloze-style question answering. However,
storing factual knowledge in a fixed number of weights of a language model
clearly has limitations. Previous approaches have successfully provided access
to information outside the model weights using supervised architectures that
combine an information retrieval system with a machine reading component. In
this paper, we go a step further and integrate information from a retrieval
system with a pre-trained language model in a purely unsupervised way. We
report that augmenting pre-trained language models in this way dramatically
improves performance and that the resulting system, despite being unsupervised,
is competitive with a supervised machine reading baseline. Furthermore,
processing query and context with different segment tokens allows BERT to
utilize its Next Sentence Prediction pre-trained classifier to determine
whether the context is relevant or not, substantially improving BERT's
zero-shot cloze-style question-answering performance and making its predictions
robust to noisy contexts.