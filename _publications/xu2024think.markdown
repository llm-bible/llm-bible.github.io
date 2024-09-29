---
layout: publication
title: Think Thinner Key Cache By Query-driven Pruning
authors: Xu Yuhui, Jie Zhanming, Dong Hanze, Wang Lei, Lu Xudong, Zhou Aojun, Saha Amrita, Xiong Caiming, Sahoo Doyen
conference: "Arxiv"
year: 2024
bibkey: xu2024think
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.21018"}
tags: ['Applications', 'Attention Mechanism', 'Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Pruning', 'RAG', 'Reinforcement Learning', 'Transformer']
---
Large Language Models (LLMs) have revolutionized the field of natural language processing achieving unprecedented performance across a variety of applications by leveraging increased model sizes and sequence lengths. However the associated rise in computational and memory costs poses significant challenges particularly in managing long sequences due to the quadratic complexity of the transformer attention mechanism. This paper focuses on the long-context scenario addressing the inefficiencies in KV cache memory consumption during inference. Unlike existing approaches that optimize the memory based on the sequence lengths we uncover that the channel dimension of the KV cache exhibits significant redundancy characterized by unbalanced magnitude distribution and low-rank structure in attention weights. Based on these observations we propose ThinK a novel query-dependent KV cache pruning method designed to minimize attention weight loss while selectively pruning the least significant channels. Our approach not only maintains or enhances model accuracy but also achieves a reduction in memory costs by over 2037; compared with vanilla KV cache eviction methods. Extensive evaluations on the LLaMA3 and Mistral models across various long-sequence datasets confirm the efficacy of ThinK setting a new precedent for efficient LLM deployment without compromising performance. We also outline the potential of extending our method to value cache pruning demonstrating ThinKs versatility and broad applicability in reducing both memory and computational overheads.
