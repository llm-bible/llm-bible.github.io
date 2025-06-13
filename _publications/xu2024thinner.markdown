---
layout: publication
title: 'Think: Thinner Key Cache By Query-driven Pruning'
authors: Yuhui Xu, Zhanming Jie, Hanze Dong, Lei Wang, Xudong Lu, Aojun Zhou, Amrita Saha, Caiming Xiong, Doyen Sahoo
conference: "Arxiv"
year: 2024
bibkey: xu2024thinner
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.21018"}
  - {name: "Code", url: "https://github.com/SalesforceAIResearch/ThinK"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Reinforcement Learning', 'Pruning', 'Quantization', 'Has Code', 'Applications', 'Attention Mechanism']
---
Large Language Models (LLMs) have revolutionized the field of natural
language processing, achieving unprecedented performance across a variety of
applications. However, their increased computational and memory demands present
significant challenges, especially when handling long sequences. This paper
focuses on the long-context scenario, addressing the inefficiencies in KV cache
memory consumption during inference. Unlike existing approaches that optimize
the memory based on the sequence length, we identify substantial redundancy in
the channel dimension of the KV cache, as indicated by an uneven magnitude
distribution and a low-rank structure in the attention weights. In response, we
propose ThinK, a novel query-dependent KV cache pruning method designed to
minimize attention weight loss while selectively pruning the least significant
channels. Our approach not only maintains or enhances model accuracy but also
achieves a reduction in KV cache memory costs by over 20% compared with vanilla
KV cache eviction and quantization methods. For instance, ThinK integrated with
KIVI can achieve a 2.8x reduction in peak memory usage while maintaining nearly
the same quality, enabling up to a 5x increase in batch size when using a
single GPU. Extensive evaluations on the LLaMA and Mistral models across
various long-sequence datasets verified the efficiency of ThinK, establishing a
new baseline algorithm for efficient LLM deployment without compromising
performance. Our code has been made available at
https://github.com/SalesforceAIResearch/ThinK.
