---
layout: publication
title: Length Generalization of Causal Transformers without Position Encoding
authors: Wang Jie, Ji Tao, Wu Yuanbin, Yan Hang, Gui Tao, Zhang Qi, Huang Xuanjing, Wang Xiaoling
conference: "Arxiv"
year: 2024
bibkey: wang2024length
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.12224"}
tags: ['ARXIV', 'Language Modeling', 'Model Architecture', 'Transformer']
---
Generalizing to longer sentences is important for recent Transformer-based language models. Besides algorithms manipulating explicit position features the success of Transformers without position encodings (NoPE) provides a new way to overcome the challenge. In this paper we study the length generalization property of NoPE. We find that although NoPE can extend to longer sequences than the commonly used explicit position encodings it still has a limited context length. We identify a connection between the failure of NoPEs generalization and the distraction of attention distributions. We propose a parameter-efficient tuning for searching attention heads best temperature hyper-parameters which substantially expands NoPEs context size. Experiments on long sequence language modeling the synthetic passkey retrieval task and real-world long context tasks show that NoPE can achieve competitive performances with state-of-the-art length generalization algorithms. The source code is publicly accessible
