---
layout: publication
title: 'PAIR: Planning And Iterative Refinement In Pre-trained Transformers For Long Text Generation'
authors: Xinyu Hua, Lu Wang
conference: "Arxiv"
year: 2020
citations: 43
bibkey: hua2020planning
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2010.02301'}
tags: ['Language Modeling', 'Transformer', 'RAG', 'Model Architecture', 'BERT', 'Tools', 'Applications', 'Pretraining Methods']
---
Pre-trained Transformers have enabled impressive breakthroughs in generating
long and fluent text, yet their outputs are often "rambling" without coherently
arranged content. In this work, we present a novel content-controlled text
generation framework, PAIR, with planning and iterative refinement, which is
built upon a large model, BART. We first adapt the BERT model to automatically
construct the content plans, consisting of keyphrase assignments and their
corresponding sentence-level positions. The BART model is employed for
generation without modifying its structure. We then propose a refinement
algorithm to gradually enhance the generation quality within the
sequence-to-sequence framework. Evaluation with automatic metrics shows that
adding planning consistently improves the generation quality on three distinct
domains, with an average of 20 BLEU points and 12 METEOR points improvements.
In addition, human judges rate our system outputs to be more relevant and
coherent than comparisons without planning.
