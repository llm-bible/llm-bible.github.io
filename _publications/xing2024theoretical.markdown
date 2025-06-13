---
layout: publication
title: 'Theoretical Understanding Of In-context Learning In Shallow Transformers With Unstructured Data'
authors: Yue Xing, Xiaofeng Lin, Chenheng Xu, Namjoon Suh, Qifan Song, Guang Cheng
conference: "Arxiv"
year: 2024
bibkey: xing2024theoretical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.00743"}
tags: ['Transformer', 'Model Architecture', 'Attention Mechanism', 'Pretraining Methods', 'Prompting', 'In-Context Learning']
---
Large language models (LLMs) are powerful models that can learn concepts at
the inference stage via in-context learning (ICL). While theoretical studies,
e.g., \cite\{zhang2023trained\}, attempt to explain the mechanism of ICL, they
assume the input \\(x_i\\) and the output \\(y_i\\) of each demonstration example are
in the same token (i.e., structured data). However, in real practice, the
examples are usually text input, and all words, regardless of their logic
relationship, are stored in different tokens (i.e., unstructured data
\cite\{wibisono2023role\}). To understand how LLMs learn from the unstructured
data in ICL, this paper studies the role of each component in the transformer
architecture and provides a theoretical understanding to explain the success of
the architecture. In particular, we consider a simple transformer with one/two
attention layers and linear regression tasks for the ICL prediction. We observe
that (1) a transformer with two layers of (self-)attentions with a look-ahead
attention mask can learn from the prompt in the unstructured data, and (2)
positional encoding can match the \\(x_i\\) and \\(y_i\\) tokens to achieve a better
ICL performance.
