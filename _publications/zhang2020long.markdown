---
layout: publication
title: 'Long-short Term Masking Transformer: A Simple But Effective Baseline For Document-level Neural Machine Translation'
authors: Pei Zhang, Boxing Chen, Niyu Ge, Kai Fan
conference: "Arxiv"
year: 2020
bibkey: zhang2020long
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2009.09127'}
tags: ['Attention Mechanism', 'Transformer', 'Applications', 'Model Architecture', 'Pretraining Methods']
---
Many document-level neural machine translation (NMT) systems have explored
the utility of context-aware architecture, usually requiring an increasing
number of parameters and computational complexity. However, few attention is
paid to the baseline model. In this paper, we research extensively the pros and
cons of the standard transformer in document-level translation, and find that
the auto-regressive property can simultaneously bring both the advantage of the
consistency and the disadvantage of error accumulation. Therefore, we propose a
surprisingly simple long-short term masking self-attention on top of the
standard transformer to both effectively capture the long-range dependence and
reduce the propagation of errors. We examine our approach on the two publicly
available document-level datasets. We can achieve a strong result in BLEU and
capture discourse phenomena.
