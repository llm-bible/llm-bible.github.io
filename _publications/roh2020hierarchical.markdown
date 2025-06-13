---
layout: publication
title: 'Hierarchical GPT With Congruent Transformers For Multi-sentence Language Models'
authors: Jihyeon Roh, Huiseong Gim, Soo-young Lee
conference: "Arxiv"
year: 2020
bibkey: roh2020hierarchical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2009.08636"}
tags: ['Transformer', 'GPT', 'RAG', 'Model Architecture', 'Attention Mechanism', 'Pretraining Methods']
---
We report a GPT-based multi-sentence language model for dialogue generation
and document understanding. First, we propose a hierarchical GPT which consists
of three blocks, i.e., a sentence encoding block, a sentence generating block,
and a sentence decoding block. The sentence encoding and decoding blocks are
basically the encoder-decoder blocks of the standard Transformers, which work
on each sentence independently. The sentence generating block is inserted
between the encoding and decoding blocks, and generates the next sentence
embedding vector from the previous sentence embedding vectors. We believe it is
the way human make conversation and understand paragraphs and documents. Since
each sentence may consist of fewer words, the sentence encoding and decoding
Transformers can use much smaller dimensional embedding vectors. Secondly, we
note the attention in the Transformers utilizes the inner-product similarity
measure. Therefore, to compare the two vectors in the same space, we set the
transform matrices for queries and keys to be the same. Otherwise, the
similarity concept is incongruent. We report experimental results to show that
these two modifications increase the language model performance for tasks with
multiple sentences.
