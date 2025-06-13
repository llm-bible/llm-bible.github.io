---
layout: publication
title: 'Efficient Transformer With Reinforced Position Embedding For Language Models'
authors: Yen-che Hsiao, Abhishek Dutta
conference: "Arxiv"
year: 2024
bibkey: hsiao2024efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.04731"}
tags: ['Transformer', 'Efficiency and Optimization', 'RAG', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods']
---
In this paper, we propose an efficient transformer architecture that uses
reinforced positional embedding to obtain superior performance with half the
number of encoder decoder layers. We demonstrate that concatenating positional
encoding with trainable token embeddings, normalizing columns in the token
embedding matrix, and using the normalized token embedding matrix as the value
of the attention layer improve the training and validation loss and the
training time in an encoder-decoder Transformer model for a Portuguese-English
translation task with 10 epochs or 12 hours of training across 10 trials. Our
method, with roughly a threefold parameter reduction compared to the baseline
model, yields a mean training loss of 1.21, a mean validation loss of 1.51, and
an average training time of 1352.27 seconds per epoch, surpassing the baseline
model with the same embedding dimension that employs addition of positional
encoding and token embeddings, which achieves a mean training loss of 1.96, a
validation loss of 2.18, and an average training time of 4297.79 seconds per
epoch. Additionally, we evaluated our proposed architecture and the baseline
across 14 diverse translation datasets from TensorFlow. The results indicate
that our method consistently achieves lower or comparable training and
validation losses, suggesting enhanced learning efficiency.
