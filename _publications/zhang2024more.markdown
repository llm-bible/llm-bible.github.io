---
layout: publication
title: 'More Tokens, Lower Precision: Towards The Optimal Token-precision Trade-off In KV Cache Compression'
authors: Jiebin Zhang, Dawei Zhu, Yifan Song, Wenhao Wu, Chuqiao Kuang, Xiaoguang Li, Lifeng Shang, Qun Liu, Sujian Li
conference: "Arxiv"
year: 2024
bibkey: zhang2024more
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.12706"}
  - {name: "Code", url: "https://github.com/zhzihao/QPruningKV"}
tags: ['Quantization', 'Efficiency and Optimization', 'Has Code', 'Pruning']
---
As large language models (LLMs) process increasing context windows, the
memory usage of KV cache has become a critical bottleneck during inference. The
mainstream KV compression methods, including KV pruning and KV quantization,
primarily focus on either token or precision dimension separately. However,
these works leaving the trade-off between these two orthogonal dimensions
largely under-explored. In this paper, we comprehensively investigate the
token-precision trade-off in KV cache compression.Experiments demonstrate that
storing more tokens in the KV cache with lower precision,a strategy we term
quantized pruning, can significantly enhance the long-context performance of
LLMs. In-depth analysis of the token-precision trade-off across key aspects
demonstrates that, quantized pruning achieves substantial improvements in
retrieval-related tasks and consistently performs well across varying input
lengths. Furthermore, quantized pruning demonstrates notable stability and
effectiveness across different KV pruning methods, quantization strategies, and
model scales. These findings offer valuable insights into optimizing KV cache
compression through balanced token-precision trade-off strategies. Our code is
available at https://github.com/zhzihao/QPruningKV.
