---
layout: publication
title: 'Addressing Token Uniformity In Transformers Via Singular Value Transformation'
authors: Hanqi Yan, Lin Gui, Wenjie Li, Yulan He
conference: "Arxiv"
year: 2022
bibkey: yan2022addressing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2208.11790'}
  - {name: "Code", url: 'https://github.com/hanqi-qi/tokenUni.git'}
tags: ['Attention Mechanism', 'Has Code', 'Transformer', 'BERT', 'Model Architecture', 'Pretraining Methods']
---
Token uniformity is commonly observed in transformer-based models, in which
different tokens share a large proportion of similar information after going
through stacked multiple self-attention layers in a transformer. In this paper,
we propose to use the distribution of singular values of outputs of each
transformer layer to characterise the phenomenon of token uniformity and
empirically illustrate that a less skewed singular value distribution can
alleviate the `token uniformity' problem. Base on our observations, we define
several desirable properties of singular value distributions and propose a
novel transformation function for updating the singular values. We show that
apart from alleviating token uniformity, the transformation function should
preserve the local neighbourhood structure in the original embedding space. Our
proposed singular value transformation function is applied to a range of
transformer-based language models such as BERT, ALBERT, RoBERTa and DistilBERT,
and improved performance is observed in semantic textual similarity evaluation
and a range of GLUE tasks. Our source code is available at
https://github.com/hanqi-qi/tokenUni.git.
