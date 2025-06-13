---
layout: publication
title: 'Inducing Grammars With And For Neural Machine Translation'
authors: Ke Tran, Yonatan Bisk
conference: "Arxiv"
year: 2018
bibkey: tran2018inducing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1805.10850"}
tags: ['Transformer', 'Applications', 'RAG', 'Model Architecture', 'Attention Mechanism']
---
Machine translation systems require semantic knowledge and grammatical
understanding. Neural machine translation (NMT) systems often assume this
information is captured by an attention mechanism and a decoder that ensures
fluency. Recent work has shown that incorporating explicit syntax alleviates
the burden of modeling both types of knowledge. However, requiring parses is
expensive and does not explore the question of what syntax a model needs during
translation. To address both of these issues we introduce a model that
simultaneously translates while inducing dependency trees. In this way, we
leverage the benefits of structure while investigating what syntax NMT must
induce to maximize performance. We show that our dependency trees are 1.
language pair dependent and 2. improve translation quality.
