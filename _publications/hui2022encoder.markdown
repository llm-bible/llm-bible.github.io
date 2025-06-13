---
layout: publication
title: 'ED2LM: Encoder-decoder To Language Model For Faster Document Re-ranking Inference'
authors: Kai Hui, Honglei Zhuang, Tao Chen, Zhen Qin, Jing Lu, Dara Bahri, Ji Ma, Jai Prakash Gupta, Cicero Nogueira Dos Santos, Yi Tay, Don Metzler
conference: "Arxiv"
year: 2022
bibkey: hui2022encoder
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2204.11458"}
tags: ['RAG', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'BERT']
---
State-of-the-art neural models typically encode document-query pairs using
cross-attention for re-ranking. To this end, models generally utilize an
encoder-only (like BERT) paradigm or an encoder-decoder (like T5) approach.
These paradigms, however, are not without flaws, i.e., running the model on all
query-document pairs at inference-time incurs a significant computational cost.
This paper proposes a new training and inference paradigm for re-ranking. We
propose to finetune a pretrained encoder-decoder model using in the form of
document to query generation. Subsequently, we show that this encoder-decoder
architecture can be decomposed into a decoder-only language model during
inference. This results in significant inference time speedups since the
decoder-only architecture only needs to learn to interpret static encoder
embeddings during inference. Our experiments show that this new paradigm
achieves results that are comparable to the more expensive cross-attention
ranking approaches while being up to 6.8X faster. We believe this work paves
the way for more efficient neural rankers that leverage large pretrained
models.
