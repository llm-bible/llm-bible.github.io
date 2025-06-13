---
layout: publication
title: 'Sliding Window Attention Training For Efficient Large Language Models'
authors: Zichuan Fu, Wentao Song, Yejing Wang, Xian Wu, Yefeng Zheng, Yingying Zhang, Derong Xu, Xuetao Wei, Tong Xu, Xiangyu Zhao
conference: "Arxiv"
year: 2025
bibkey: fu2025sliding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.18845"}
  - {name: "Code", url: "https://github.com/Fzkuji/swat-attention"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Pretraining Methods', 'Transformer', 'Has Code', 'Attention Mechanism']
---
Recent advances in transformer-based Large Language Models (LLMs) have demonstrated remarkable capabilities across various tasks. However, their quadratic computational complexity concerning sequence length remains a significant bottleneck for processing long documents. As a result, many efforts like sparse attention and state space models have been proposed to improve the efficiency of LLMs over long sequences. Though effective, these approaches compromise the performance or introduce structural complexity. This calls for a simple yet efficient model that preserves the fundamental Transformer architecture. To this end, we introduce SWAT, which enables efficient long-context handling via Sliding Window Attention Training. This paper first attributes the inefficiency of Transformers to the attention sink phenomenon resulting from the high variance of softmax operation. Then, we replace softmax with the sigmoid function and utilize a balanced ALiBi and Rotary Position Embedding for efficient information compression and retention. Experiments demonstrate that SWAT achieves SOTA performance compared with state-of-the-art linear recurrent architectures on eight benchmarks. Code is available at https://github.com/Fzkuji/swat-attention.
