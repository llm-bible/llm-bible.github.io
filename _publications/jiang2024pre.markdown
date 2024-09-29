---
layout: publication
title: Pre45;training Cross45;lingual Open Domain Question Answering With Large45;scale Synthetic Supervision
authors: Jiang Fan, Drummond Tom, Cohn Trevor
conference: "Arxiv"
year: 2024
bibkey: jiang2024pre
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.16508"}
tags: ['Applications', 'Training Techniques']
---
Cross45;lingual open domain question answering (CLQA) is a complex problem comprising cross45;lingual retrieval from a multilingual knowledge base followed by answer generation in the query language. Both steps are usually tackled by separate models requiring substantial annotated datasets and typically auxiliary resources like machine translation systems to bridge between languages. In this paper we show that CLQA can be addressed using a single encoder45;decoder model. To effectively train this model we propose a self45;supervised method based on exploiting the cross45;lingual link structure within Wikipedia. We demonstrate how linked Wikipedia pages can be used to synthesise supervisory signals for cross45;lingual retrieval through a form of cloze query and generate more natural questions to supervise answer generation. Together we show our approach texttt123;CLASS125; outperforms comparable methods on both supervised and zero45;shot language adaptation settings including those using machine translation.
