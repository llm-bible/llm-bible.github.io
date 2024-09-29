---
layout: publication
title: 'NABU $\(\mathrm\){-}$ Multilingual Graph-based Neural RDF Verbalizer'
authors: Moussallem Diego, Gnaneshwar Dwaraknath, Ferreira Thiago Castro, Ngomo Axel-cyrille Ngonga
conference: "Arxiv"
year: 2020
bibkey: moussallem2020nabu
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2009.07728"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
The RDF-to-text task has recently gained substantial attention due to continuous growth of Linked Data. In contrast to traditional pipeline models recent studies have focused on neural models which are now able to convert a set of RDF triples into text in an end-to-end style with promising results. However English is the only language widely targeted. We address this research gap by presenting NABU a multilingual graph-based neural model that verbalizes RDF data to German Russian and English. NABU is based on an encoder-decoder architecture uses an encoder inspired by Graph Attention Networks and a Transformer as decoder. Our approach relies on the fact that knowledge graphs are language-agnostic and they hence can be used to generate multilingual text. We evaluate NABU in monolingual and multilingual settings on standard benchmarking WebNLG datasets. Our results show that NABU outperforms state-of-the-art approaches on English with 66.21 BLEU and achieves consistent results across all languages on the multilingual scenario with 56.04 BLEU.
