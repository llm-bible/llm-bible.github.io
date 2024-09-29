---
layout: publication
title: TensorGPT Efficient Compression of the Embedding Layer in LLMs based on the Tensor-Train Decomposition
authors: Xu Mingxue, Xu Yao Lei, Mandic Danilo P.
conference: "Arxiv"
year: 2023
bibkey: xu2023tensorgpt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.00526"}
tags: ['Ethics And Bias', 'GPT', 'Model Architecture', 'RAG']
---
High-dimensional token embeddings underpin Large Language Models (LLMs) as they can capture subtle semantic information and significantly enhance the modelling of complex language patterns. However the associated high dimensionality also introduces considerable model parameters and a prohibitively high model storage. To address this issue this work proposes an approach based on the Tensor-Train Decomposition (TTD) where each token embedding is treated as a Matrix Product State (MPS) that can be efficiently computed in a distributed manner. The experimental results on GPT-2 demonstrate that through our approach the embedding layer can be compressed by a factor of up to 38.40 times and when the compression factor is 3.31 times even produced a better performance than the original GPT-2 model.
