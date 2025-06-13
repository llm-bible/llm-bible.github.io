---
layout: publication
title: 'CDLM: Cross-document Language Modeling'
authors: Avi Caciularu, Arman Cohan, Iz Beltagy, Matthew E. Peters, Arie Cattan, Ido Dagan
conference: "Arxiv"
year: 2021
bibkey: caciularu2021cross
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2101.00406'}
  - {name: "Code", url: 'https://github.com/aviclu/CDLM'}
tags: ['Attention Mechanism', 'Masked Language Model', 'Has Code', 'Language Modeling', 'Transformer', 'RAG', 'Training Techniques', 'BERT', 'Model Architecture', 'Pretraining Methods']
---
We introduce a new pretraining approach geared for multi-document language
modeling, incorporating two key ideas into the masked language modeling
self-supervised objective. First, instead of considering documents in
isolation, we pretrain over sets of multiple related documents, encouraging the
model to learn cross-document relationships. Second, we improve over recent
long-range transformers by introducing dynamic global attention that has access
to the entire input to predict masked tokens. We release CDLM (Cross-Document
Language Model), a new general language model for multi-document setting that
can be easily applied to downstream tasks. Our extensive analysis shows that
both ideas are essential for the success of CDLM, and work in synergy to set
new state-of-the-art results for several multi-text tasks. Code and models are
available at https://github.com/aviclu/CDLM.
