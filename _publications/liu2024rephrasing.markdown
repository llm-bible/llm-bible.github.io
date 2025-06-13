---
layout: publication
title: 'Rephrasing Electronic Health Records For Pretraining Clinical Language Models'
authors: Jinghui Liu, Anthony Nguyen
conference: "Arxiv"
year: 2024
bibkey: liu2024rephrasing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.18940'}
tags: ['Language Modeling', 'Training Techniques', 'Applications', 'Reinforcement Learning', 'Pretraining Methods']
---
Clinical language models are important for many applications in healthcare,
but their development depends on access to extensive clinical text for
pretraining. However, obtaining clinical notes from electronic health records
(EHRs) at scale is challenging due to patient privacy concerns. In this study,
we rephrase existing clinical notes using LLMs to generate synthetic
pretraining corpora, drawing inspiration from previous work on rephrasing web
data. We examine four popular small-sized LLMs (<10B) to create synthetic
clinical text to pretrain both decoder-based and encoder-based language models.
The method yields better results in language modeling and downstream tasks than
previous synthesis approaches without referencing real clinical text. We find
that augmenting original clinical notes with synthetic corpora from different
LLMs improves performances even at a small token budget, showing the potential
of this method to support pretraining at the institutional level or be scaled
to synthesize large-scale clinical corpora.
