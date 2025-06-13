---
layout: publication
title: 'EFIM: Efficient Serving Of Llms For Infilling Tasks With Improved KV Cache Reuse'
authors: Tianyu Guo, Hande Dong, Yichong Leng, Feng Liu, Cheater Lin, Nong Xiao, Xianwei Zhang
conference: "Arxiv"
year: 2025
bibkey: guo2025efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.21889"}
  - {name: "Code", url: "https://github.com/gty111/EFIM"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Tokenization', 'RAG', 'Has Code', 'Prompting']
---
Large language models (LLMs) are often used for infilling tasks, which involve predicting or generating missing information in a given text. These tasks typically require multiple interactions with similar context. To reduce the computation of repeated historical tokens, cross-request key-value (KV) cache reuse, a technique that stores and reuses intermediate computations, has become a crucial method in multi-round interactive services. However, in infilling tasks, the KV cache reuse is often hindered by the structure of the prompt format, which typically consists of a prefix and suffix relative to the insertion point. Specifically, the KV cache of the prefix or suffix part is frequently invalidated as the other part (suffix or prefix) is incrementally generated. To address the issue, we propose EFIM, a transformed prompt format of FIM to unleash the performance potential of KV cache reuse. Although the transformed prompt can solve the inefficiency, it exposes subtoken generation problems in current LLMs, where they have difficulty generating partial words accurately. Therefore, we introduce a fragment tokenization training method which splits text into multiple fragments before tokenization during data processing. Experiments on two representative LLMs show that LLM serving with EFIM can lower the latency by 52% and improve the throughput by 98% while maintaining the original infilling capability. EFIM's source code is publicly available at https://github.com/gty111/EFIM.
