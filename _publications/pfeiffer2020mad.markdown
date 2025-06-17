---
layout: publication
title: 'MAD-X: An Adapter-based Framework For Multi-task Cross-lingual Transfer'
authors: "Jonas Pfeiffer, Ivan Vuli\u0107, Iryna Gurevych, Sebastian Ruder"
conference: Arxiv
year: 2020
citations: 121
bibkey: pfeiffer2020mad
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2005.00052'}]
tags: [Few-Shot, Applications, BERT, Pre-Training]
---
The main goal behind state-of-the-art pre-trained multilingual models such as
multilingual BERT and XLM-R is enabling and bootstrapping NLP applications in
low-resource languages through zero-shot or few-shot cross-lingual transfer.
However, due to limited model capacity, their transfer performance is the
weakest exactly on such low-resource languages and languages unseen during
pre-training. We propose MAD-X, an adapter-based framework that enables high
portability and parameter-efficient transfer to arbitrary tasks and languages
by learning modular language and task representations. In addition, we
introduce a novel invertible adapter architecture and a strong baseline method
for adapting a pre-trained multilingual model to a new language. MAD-X
outperforms the state of the art in cross-lingual transfer across a
representative set of typologically diverse languages on named entity
recognition and causal commonsense reasoning, and achieves competitive results
on question answering. Our code and adapters are available at AdapterHub.ml