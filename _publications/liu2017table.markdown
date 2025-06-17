---
layout: publication
title: Table-to-text Generation By Structure-aware Seq2seq Learning
authors: Tianyu Liu, Kexiang Wang, Lei Sha, Baobao Chang, Zhifang Sui
conference: Arxiv
year: 2017
citations: 71
bibkey: liu2017table
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1711.09724'}, {name: Code,
    url: 'https://github.com/tyliupku/wiki2bio'}]
tags: [Transformer, Language Modeling, Attention Mechanism]
---
Table-to-text generation aims to generate a description for a factual table
which can be viewed as a set of field-value records. To encode both the content
and the structure of a table, we propose a novel structure-aware seq2seq
architecture which consists of field-gating encoder and description generator
with dual attention. In the encoding phase, we update the cell memory of the
LSTM unit by a field gate and its corresponding field value in order to
incorporate field information into table representation. In the decoding phase,
dual attention mechanism which contains word level attention and field level
attention is proposed to model the semantic relevance between the generated
description and the table. We conduct experiments on the \texttt\{WIKIBIO\}
dataset which contains over 700k biographies and corresponding infoboxes from
Wikipedia. The attention visualizations and case studies show that our model is
capable of generating coherent and informative descriptions based on the
comprehensive understanding of both the content and the structure of a table.
Automatic evaluations also show our model outperforms the baselines by a great
margin. Code for this work is available on
https://github.com/tyliupku/wiki2bio.