---
layout: publication
title: Text Infilling
authors: Wanrong Zhu, Zhiting Hu, Eric Xing
conference: Arxiv
year: 2019
citations: 25
bibkey: zhu2019text
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1901.00158'}]
tags: [Transformer, Language Modeling, RAG, Attention Mechanism]
---
Recent years have seen remarkable progress of text generation in different
contexts, such as the most common setting of generating text from scratch, and
the emerging paradigm of retrieval-and-rewriting. Text infilling, which fills
missing text portions of a sentence or paragraph, is also of numerous use in
real life, yet is under-explored. Previous work has focused on restricted
settings by either assuming single word per missing portion or limiting to a
single missing portion to the end of the text. This paper studies the general
task of text infilling, where the input text can have an arbitrary number of
portions to be filled, each of which may require an arbitrary unknown number of
tokens. We study various approaches for the task, including a self-attention
model with segment-aware position encoding and bidirectional context modeling.
We create extensive supervised data by masking out text with varying
strategies. Experiments show the self-attention model greatly outperforms
others, creating a strong baseline for future research.