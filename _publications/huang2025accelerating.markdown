---
layout: publication
title: 'APB: Accelerating Distributed Long-context Inference By Passing Compressed Context Blocks Across Gpus'
authors: Yuxiang Huang, Mingye Li, Xu Han, Chaojun Xiao, Weilin Zhao, Sun Ao, Hao Zhou, Jie Zhou, Zhiyuan Liu, Maosong Sun
conference: "Arxiv"
year: 2025
bibkey: huang2025accelerating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.12085"}
  - {name: "Code", url: "https://github.com/thunlp/APB"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'RAG', 'Transformer', 'Has Code', 'Applications', 'Attention Mechanism']
---
While long-context inference is crucial for advancing large language model (LLM) applications, its prefill speed remains a significant bottleneck. Current approaches, including sequence parallelism strategies and compute reduction through approximate attention mechanisms, still fall short of delivering optimal inference efficiency. This hinders scaling the inputs to longer sequences and processing long-context queries in a timely manner. To address this, we introduce APB, an efficient long-context inference framework that leverages multi-host approximate attention to enhance prefill speed by reducing compute and enhancing parallelism simultaneously. APB introduces a communication mechanism for essential key-value pairs within a sequence parallelism framework, enabling a faster inference speed while maintaining task performance. We implement APB by incorporating a tailored FlashAttn kernel alongside optimized distribution strategies, supporting diverse models and parallelism configurations. APB achieves speedups of up to 9.2x, 4.2x, and 1.6x compared with FlashAttn, RingAttn, and StarAttn, respectively, without any observable task performance degradation. We provide the implementation and experiment code of APB in https://github.com/thunlp/APB.
