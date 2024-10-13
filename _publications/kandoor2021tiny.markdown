---
layout: publication
title: 'Tiny Neural Models For Seq2seq'
authors: Kandoor Arun
conference: "Arxiv"
year: 2021
bibkey: kandoor2021tiny
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2108.03340"}
tags: ['Applications', 'BERT', 'Model Architecture', 'Quantization', 'RAG', 'Uncategorized']
---
Semantic parsing models with applications in task oriented dialog systems
require efficient sequence to sequence (seq2seq) architectures to be run
on-device. To this end, we propose a projection based encoder-decoder model
referred to as pQRNN-MAtt. Studies based on projection methods were restricted
to encoder-only models, and we believe this is the first study extending it to
seq2seq architectures. The resulting quantized models are less than 3.5MB in
size and are well suited for on-device latency critical applications. We show
that on MTOP, a challenging multilingual semantic parsing dataset, the average
model performance surpasses LSTM based seq2seq model that uses pre-trained
embeddings despite being 85x smaller. Furthermore, the model can be an
effective student for distilling large pre-trained models such as T5/BERT.
