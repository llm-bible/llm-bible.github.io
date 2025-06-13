---
layout: publication
title: 'Neural Knowledge Bank For Pretrained Transformers'
authors: Damai Dai, Wenbin Jiang, Qingxiu Dong, Yajuan Lyu, Qiaoqiao She, Zhifang Sui
conference: "Arxiv"
year: 2022
bibkey: dai2022neural
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2208.00399"}
tags: ['Transformer', 'Applications', 'Interpretability and Explainability', 'Language Modeling', 'Model Architecture', 'Training Techniques', 'Pretraining Methods']
---
The ability of pretrained Transformers to remember factual knowledge is
essential but still limited for existing models. Inspired by existing work that
regards Feed-Forward Networks (FFNs) in Transformers as key-value memories, we
design a Neural Knowledge Bank (NKB) and a knowledge injection strategy to
introduce extra factual knowledge for pretrained Transformers. The NKB is in
the form of additional knowledgeable memory slots to the FFN and the
memory-like architecture makes it highly interpretable and flexible. When
injecting extra knowledge with the Salient Span Masking (SSM) pretraining
objective, we fix the original pretrained model and train only the NKB. This
training strategy makes sure the general language modeling ability of the
original pretrained model is not influenced. By mounting the NKB onto the T5
model, we verify its strong ability to store extra factual knowledge based on
three closed-book question answering datasets. Also, we prove that mounting the
NKB will not degrade the general language modeling ability of T5 through two
representative tasks, summarization and machine translation. Further, we
thoroughly analyze the interpretability of the NKB and reveal the meaning of
its keys and values in a human-readable way. Finally, we show the flexibility
of the NKB by directly modifying its value vectors to update the factual
knowledge stored in it.
