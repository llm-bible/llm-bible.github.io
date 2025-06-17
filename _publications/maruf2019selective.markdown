---
layout: publication
title: Selective Attention For Context-aware Neural Machine Translation
authors: "Sameen Maruf, Andr\xE9 F. T. Martins, Gholamreza Haffari"
conference: Arxiv
year: 2019
citations: 52
bibkey: maruf2019selective
additional_links:
- name: Paper
  url: https://arxiv.org/abs/1903.08788
tags:
- Transformer
- Attention Mechanism
- Model Architecture
---
Despite the progress made in sentence-level NMT, current systems still fall
short at achieving fluent, good quality translation for a full document. Recent
works in context-aware NMT consider only a few previous sentences as context
and may not scale to entire documents. To this end, we propose a novel and
scalable top-down approach to hierarchical attention for context-aware NMT
which uses sparse attention to selectively focus on relevant sentences in the
document context and then attends to key words in those sentences. We also
propose single-level attention approaches based on sentence or word-level
information in the context. The document-level context representation, produced
from these attention modules, is integrated into the encoder or decoder of the
Transformer model depending on whether we use monolingual or bilingual context.
Our experiments and evaluation on English-German datasets in different document
MT settings show that our selective attention approach not only significantly
outperforms context-agnostic baselines but also surpasses context-aware
baselines in most cases.