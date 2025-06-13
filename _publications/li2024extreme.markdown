---
layout: publication
title: 'Excp: Extreme LLM Checkpoint Compression Via Weight-momentum Joint Shrinking'
authors: Wenshuo Li, Xinghao Chen, Han Shu, Yehui Tang, Yunhe Wang
conference: "Arxiv"
year: 2024
bibkey: li2024extreme
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.11257'}
  - {name: "Code", url: 'https://github.com/Gaffey/ExCP'}
tags: ['Attention Mechanism', 'Has Code', 'RAG', 'Efficiency and Optimization', 'Model Architecture', 'Tools', 'Training Techniques', 'Quantization', 'Reinforcement Learning']
---
Large language models (LLM) have recently attracted significant attention in
the field of artificial intelligence. However, the training process of these
models poses significant challenges in terms of computational and storage
capacities, thus compressing checkpoints has become an urgent problem. In this
paper, we propose a novel Extreme Checkpoint Compression (ExCP) framework,
which significantly reduces the required storage of training checkpoints while
achieving nearly lossless performance. We first calculate the residuals of
adjacent checkpoints to obtain the essential but sparse information for higher
compression ratio. To further excavate the redundancy parameters in
checkpoints, we then propose a weight-momentum joint shrinking method to
utilize another important information during the model optimization, i.e.,
momentum. In particular, we exploit the information of both model and optimizer
to discard as many parameters as possible while preserving critical information
to ensure optimal performance. Furthermore, we utilize non-uniform quantization
to further compress the storage of checkpoints. We extensively evaluate our
proposed ExCP framework on several models ranging from 410M to 7B parameters
and demonstrate significant storage reduction while maintaining strong
performance. For instance, we achieve approximately \\(70\times\\) compression for
the Pythia-410M model, with the final performance being as accurate as the
original model on various downstream tasks. Codes will be available at
https://github.com/Gaffey/ExCP.
