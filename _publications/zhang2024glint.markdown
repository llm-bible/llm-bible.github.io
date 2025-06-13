---
layout: publication
title: 'GLINT-RU: Gated Lightweight Intelligent Recurrent Units For Sequential Recommender Systems'
authors: Sheng Zhang, Maolin Wang, Wanyu Wang, Jingtong Gao, Xiangyu Zhao, Yu Yang, Xuetao Wei, Zitao Liu, Tong Xu
conference: "Arxiv"
year: 2024
bibkey: zhang2024glint
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.10244"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'RAG', 'RecSys', 'Pretraining Methods', 'Transformer']
---
Transformer-based models have gained significant traction in sequential
recommender systems (SRSs) for their ability to capture user-item interactions
effectively. However, these models often suffer from high computational costs
and slow inference. Meanwhile, existing efficient SRS approaches struggle to
embed high-quality semantic and positional information into latent
representations. To tackle these challenges, this paper introduces GLINT-RU, a
lightweight and efficient SRS leveraging a single-layer dense selective Gated
Recurrent Units (GRU) module to accelerate inference. By incorporating a dense
selective gate, GLINT-RU adaptively captures temporal dependencies and
fine-grained positional information, generating high-quality latent
representations. Additionally, a parallel mixing block infuses fine-grained
positional features into user-item interactions, enhancing both recommendation
quality and efficiency. Extensive experiments on three datasets demonstrate
that GLINT-RU achieves superior prediction accuracy and inference speed,
outperforming baselines based on RNNs, Transformers, MLPs, and SSMs. These
results establish GLINT-RU as a powerful and efficient solution for SRSs.
