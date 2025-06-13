---
layout: publication
title: 'Redundancylens: Revealing And Exploiting Visual Token Processing Redundancy For Efficient Decoder-only Mllms'
authors: Hongliang Li, Jiaxin Zhang, Wenhui Liao, Dezhi Peng, Kai Ding, Lianwen Jin
conference: "Arxiv"
year: 2025
bibkey: li2025revealing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.19036"}
  - {name: "Code", url: "https://github.com/L-Hugh/RedundancyLens"}
tags: ['Transformer', 'Tools', 'Efficiency and Optimization', 'RAG', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Has Code', 'Multimodal Models']
---
Current Multimodal Large Language Model (MLLM) architectures face a critical tradeoff between performance and efficiency: decoder-only architectures achieve higher performance but lower efficiency, while cross-attention-based architectures offer greater efficiency but lower performance. The key distinction lies in how visual tokens are processed. Decoder-only architectures apply self-attention and FFN operations on visual tokens, while cross-attention architectures skip these computations. To investigate whether redundancy exists in this computationally expensive process, we propose a training-free framework for analyzing trained MLLMs. It consists of Probe-Activated Dynamic FFN and Hollow Attention, which enable adjustable reductions in computations for visual tokens, as well as a Layer Ranking Algorithm that prioritizes layers for these reductions. Extensive experiments demonstrate substantial, structured, and clustered redundancy unique to decoder-only MLLMs, offering valuable insights for future MLLM architecture design. Furthermore, by leveraging our reduction framework as a training-free inference acceleration approach, we achieve performance comparable to or better than state-of-the-art methods while remaining compatible with them. Code will be publicly available at https://github.com/L-Hugh/RedundancyLens.
