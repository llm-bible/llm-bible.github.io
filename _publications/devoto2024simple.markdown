---
layout: publication
title: 'A Simple And Effective \(L_2\) Norm-based Strategy For KV Cache Compression'
authors: Devoto Alessio, Zhao Yu, Scardapane Simone, Minervini Pasquale
conference: "Arxiv"
year: 2024
bibkey: devoto2024simple
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.11430"}
tags: ['Attention Mechanism', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Training Techniques', 'Transformer']
---
The deployment of large language models (LLMs) is often hindered by the extensive memory requirements of the Key-Value (KV) cache especially as context lengths increase. Existing approaches to reduce the KV cache size involve either fine-tuning the model to learn a compression strategy or leveraging attention scores to reduce the sequence length. We analyse the attention distributions in decoder-only Transformers-based models and observe that attention allocation patterns stay consistent across most layers. Surprisingly we find a clear correlation between the (L_2) and the attention scores over cached KV pairs where a low (L_2) of a key embedding usually leads to a high attention score during decoding. This finding indicates that the influence of a KV pair is potentially determined by the key embedding itself before being queried. Based on this observation we compress the KV cache based on the (L_2) of key embeddings. Our experimental results show that this simple strategy can reduce the KV cache size by 5037; on language modelling and needle-in-a-haystack tasks and 9037; on passkey retrieval tasks without losing accuracy.
