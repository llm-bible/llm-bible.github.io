---
layout: publication
title: 'Nmt5 -- Is Parallel Data Still Relevant For Pre-training Massively Multilingual Language Models?'
authors: Mihir Kale, Aditya Siddhant, Noah Constant, Melvin Johnson, Rami Al-rfou, Linting Xue
conference: "Arxiv"
year: 2021
bibkey: kale2021is
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2106.02171'}
tags: ['Language Modeling', 'RAG', 'Applications', 'Training Techniques', 'Pre-Training']
---
Recently, mT5 - a massively multilingual version of T5 - leveraged a unified
text-to-text format to attain state-of-the-art results on a wide variety of
multilingual NLP tasks. In this paper, we investigate the impact of
incorporating parallel data into mT5 pre-training. We find that multi-tasking
language modeling with objectives such as machine translation during
pre-training is a straightforward way to improve performance on downstream
multilingual and cross-lingual tasks. However, the gains start to diminish as
the model capacity increases, suggesting that parallel data might not be as
essential for larger models. At the same time, even at larger model sizes, we
find that pre-training with parallel data still provides benefits in the
limited labelled data regime.
