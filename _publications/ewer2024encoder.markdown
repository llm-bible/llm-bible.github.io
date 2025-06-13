---
layout: publication
title: 'ENTP: Encoder-only Next Token Prediction'
authors: Ethan Ewer, Daewon Chae, Thomas Zeng, Jinkyu Kim, Kangwook Lee
conference: "Arxiv"
year: 2024
bibkey: ewer2024encoder
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.01600"}
tags: ['Model Architecture', 'Language Modeling', 'Attention Mechanism', 'Pretraining Methods', 'Transformer', 'Prompting', 'In-Context Learning']
---
Next-token prediction is conventionally done using decoder-only Transformers
with causal attention, as this approach allows for efficient reuse of keys and
values. What if we were not compute-limited, should we still use decoder-only
Transformers? In this work, we introduce Encoder-only Next Token Prediction
(ENTP). We explore the differences between ENTP and decoder-only Transformers
in expressive power and complexity, highlighting potential advantages of ENTP
in settings with unbounded compute. We introduce the \\(\operatorname\{Count3\}\\)
task and show, both theoretically and experimentally, that while ENTP can
perform this task easily, a decoder-only Transformer cannot. Finally, we
empirically demonstrate the superior performance of ENTP across representative
tasks where next-token prediction based Transformers can be evaluated,
including addition, in-context learning, and language modeling.
