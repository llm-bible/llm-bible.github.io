---
layout: publication
title: 'The Refinedweb Dataset For Falcon LLM: Outperforming Curated Corpora With Web Data, And Web Data Only'
authors: Guilherme Penedo et al.
conference: "Arxiv"
year: 2023
citations: 118
bibkey: penedo2023refinedweb
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2306.01116'}
tags: ['Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
Large language models are commonly trained on a mixture of filtered web data
and curated high-quality corpora, such as social media conversations, books, or
technical papers. This curation process is believed to be necessary to produce
performant models with broad zero-shot generalization abilities. However, as
larger models requiring pretraining on trillions of tokens are considered, it
is unclear how scalable is curation and whether we will run out of unique
high-quality data soon. At variance with previous beliefs, we show that
properly filtered and deduplicated web data alone can lead to powerful models;
even significantly outperforming models from the state-of-the-art trained on
The Pile. Despite extensive filtering, the high-quality data we extract from
the web is still plentiful, and we are able to obtain five trillion tokens from
CommonCrawl. We publicly release an extract of 600 billion tokens from our
RefinedWeb dataset, and 1.3/7.5B parameters language models trained on it.
