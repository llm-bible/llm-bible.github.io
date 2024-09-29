---
layout: publication
title: "E2S2: Encoding-enhanced Sequence-to-sequence Pretraining For Language Understanding And Generation"
authors: Zhong Qihuang, Ding Liang, Liu Juhua, Du Bo, Tao Dacheng
conference: "Arxiv"
year: 2022
bibkey: zhong2022encoding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2205.14912"}
tags: ['Applications', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
Sequence-to-sequence (seq2seq) learning is a popular fashion for large-scale pretraining language models. However the prior seq2seq pretraining models generally focus on reconstructive objectives on the decoder side and neglect the effect of encoder-side supervision which we argue may lead to sub-optimal performance. To verify our hypothesis we first empirically study the functionalities of the encoder and decoder in seq2seq pretrained language models and find that the encoder takes an important but under-exploitation role than the decoder regarding the downstream performance and neuron activation. Therefore we propose an encoding-enhanced seq2seq pretraining strategy namely E2S2 which improves the seq2seq models via integrating more efficient self-supervised information into the encoders. Specifically E2S2 adopts two self-supervised objectives on the encoder side from two aspects 1) locally denoising the corrupted sentence (denoising objective); and 2) globally learning better sentence representations (contrastive objective). With the help of both objectives the encoder can effectively distinguish the noise tokens and capture high-level (i.e. syntactic and semantic) knowledge thus strengthening the ability of seq2seq model to accurately achieve the conditional generation. On a large diversity of downstream natural language understanding and generation tasks E2S2 dominantly improves the performance of its powerful backbone models e.g. BART and T5. For example upon BART backbone we achieve +1.137; averaged gain on the general language understanding evaluation (GLUE) benchmark and +1.7537; F_0.5 score improvement on CoNLL2014 dataset. We also provide in-depth analyses to show the improvement stems from better linguistic representation. We hope that our work will foster future self-supervision research on seq2seq language model pretraining.
