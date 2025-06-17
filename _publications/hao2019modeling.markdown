---
layout: publication
title: Modeling Recurrence For Transformer
authors: Jie Hao et al.
conference: Arxiv
year: 2019
citations: 33
bibkey: hao2019modeling
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1904.03092'}]
tags: [Transformer, Attention Mechanism]
---
Recently, the Transformer model that is based solely on attention mechanisms,
has advanced the state-of-the-art on various machine translation tasks.
However, recent studies reveal that the lack of recurrence hinders its further
improvement of translation capacity. In response to this problem, we propose to
directly model recurrence for Transformer with an additional recurrence
encoder. In addition to the standard recurrent neural network, we introduce a
novel attentive recurrent network to leverage the strengths of both attention
and recurrent networks. Experimental results on the widely-used WMT14
English-German and WMT17 Chinese-English translation tasks demonstrate the
effectiveness of the proposed approach. Our studies also reveal that the
proposed model benefits from a short-cut that bridges the source and target
sequences with a single recurrent layer, which outperforms its deep
counterpart.