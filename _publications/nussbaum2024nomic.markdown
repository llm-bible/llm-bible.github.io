---
layout: publication
title: 'Nomic Embed: Training A Reproducible Long Context Text Embedder'
authors: Zach Nussbaum, John X. Morris, Brandon Duderstadt, Andriy Mulyar
conference: "Arxiv"
year: 2024
bibkey: nussbaum2024nomic
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2402.01613'}
  - {name: "Code", url: 'https://github.com/nomic-ai/contrastors'}
tags: ['Has Code', 'Training Techniques']
---
This technical report describes the training of nomic-embed-text-v1, the
first fully reproducible, open-source, open-weights, open-data, 8192 context
length English text embedding model that outperforms both OpenAI Ada-002 and
OpenAI text-embedding-3-small on the short-context MTEB benchmark and the long
context LoCo benchmark. We release the training code and model weights under an
Apache 2.0 license. In contrast with other open-source models, we release the
full curated training data and code that allows for full replication of
nomic-embed-text-v1. You can find code and data to replicate the model at
https://github.com/nomic-ai/contrastors.
