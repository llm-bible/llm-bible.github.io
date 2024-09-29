---
layout: publication
title: Theoretical Understanding Of In45;context Learning In Shallow Transformers With Unstructured Data
authors: Xing Yue, Lin Xiaofeng, Xu Chenheng, Suh Namjoon, Song Qifan, Cheng Guang
conference: "Arxiv"
year: 2024
bibkey: xing2024theoretical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.00743"}
tags: ['Attention Mechanism', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Transformer']
---
Large language models (LLMs) are powerful models that can learn concepts at the inference stage via in45;context learning (ICL). While theoretical studies e.g. cite123;zhang2023trained125; attempt to explain the mechanism of ICL they assume the input x95;i and the output y95;i of each demonstration example are in the same token (i.e. structured data). However in real practice the examples are usually text input and all words regardless of their logic relationship are stored in different tokens (i.e. unstructured data cite123;wibisono2023role125;). To understand how LLMs learn from the unstructured data in ICL this paper studies the role of each component in the transformer architecture and provides a theoretical understanding to explain the success of the architecture. In particular we consider a simple transformer with one/two attention layers and linear regression tasks for the ICL prediction. We observe that (1) a transformer with two layers of (self45;)attentions with a look45;ahead attention mask can learn from the prompt in the unstructured data and (2) positional encoding can match the x95;i and y95;i tokens to achieve a better ICL performance.
