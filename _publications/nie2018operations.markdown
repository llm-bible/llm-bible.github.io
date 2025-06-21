---
layout: publication
title: Operations Guided Neural Networks For High Fidelity Data-to-text Generation
authors: Feng Nie, Jinpeng Wang, Jin-ge Yao, Rong Pan, Chin-yew Lin
conference: Arxiv
year: 2018
citations: 21
bibkey: nie2018operations
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1809.02735'}]
tags: [Reinforcement Learning, Efficiency and Optimization, Language Modeling, Quantization]
---
Recent neural models for data-to-text generation are mostly based on
data-driven end-to-end training over encoder-decoder networks. Even though the
generated texts are mostly fluent and informative, they often generate
descriptions that are not consistent with the input structured data. This is a
critical issue especially in domains that require inference or calculations
over raw data. In this paper, we attempt to improve the fidelity of neural
data-to-text generation by utilizing pre-executed symbolic operations. We
propose a framework called Operation-guided Attention-based
sequence-to-sequence network (OpAtt), with a specifically designed gating
mechanism as well as a quantization module for operation results to utilize
information from pre-executed operations. Experiments on two sports datasets
show our proposed method clearly improves the fidelity of the generated texts
to the input structured data.