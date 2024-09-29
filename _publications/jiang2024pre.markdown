---
layout: publication
title: Pre-training Cross-lingual Open Domain Question Answering with Large-scale Synthetic Supervision
authors: Jiang Fan, Drummond Tom, Cohn Trevor
conference: "Arxiv"
year: 2024
bibkey: jiang2024pre
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.16508"}
tags: ['Applications', 'Training Techniques']
---
Cross-lingual open domain question answering (CLQA) is a complex problem comprising cross-lingual retrieval from a multilingual knowledge base followed by answer generation in the query language. Both steps are usually tackled by separate models requiring substantial annotated datasets and typically auxiliary resources like machine translation systems to bridge between languages. In this paper we show that CLQA can be addressed using a single encoder-decoder model. To effectively train this model we propose a self-supervised method based on exploiting the cross-lingual link structure within Wikipedia. We demonstrate how linked Wikipedia pages can be used to synthesise supervisory signals for cross-lingual retrieval through a form of cloze query and generate more natural questions to supervise answer generation. Together we show our approach textttCLASS outperforms comparable methods on both supervised and zero-shot language adaptation settings including those using machine translation.
