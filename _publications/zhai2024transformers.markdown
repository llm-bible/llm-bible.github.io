---
layout: publication
title: 'Transformers Are Efficient Compilers, Provably'
authors: Xiyu Zhai, Runlong Zhou, Liao Zhang, Simon Shaolei Du
conference: "Arxiv"
year: 2024
bibkey: zhai2024transformers
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.14706"}
tags: ['Pretraining Methods', 'BERT', 'Transformer', 'Model Architecture']
---
Transformer-based large language models (LLMs) have demonstrated surprisingly
robust performance across a wide range of language-related tasks, including
programming language understanding and generation. In this paper, we take the
first steps towards a formal investigation of using transformers as compilers
from an expressive power perspective. To this end, we introduce a
representative programming language, Mini-Husky, which encapsulates key
features of modern C-like languages. We show that if the input code sequence
has a bounded depth in both the Abstract Syntax Tree (AST) and type inference
(reasonable assumptions based on the clean code principle), then the number of
parameters required by transformers depends only on the logarithm of the input
sequence length to handle compilation tasks, such as AST construction, symbol
resolution, and type analysis. A significant technical challenge stems from the
fact that transformers operate at a low level, where each layer processes the
input sequence as raw vectors without explicitly associating them with
predefined structure or meaning. In contrast, high-level compiler tasks
necessitate managing intricate relationships and structured program
information. Our primary technical contribution is the development of a
domain-specific language, Cybertron, which generates formal proofs of the
transformer's expressive power, scaling to address compiler tasks. We further
establish that recurrent neural networks (RNNs) require at least a linear
number of parameters relative to the input sequence, leading to an exponential
separation between transformers and RNNs. Finally, we empirically validate our
theoretical results by comparing transformers and RNNs on compiler tasks within
Mini-Husky.
