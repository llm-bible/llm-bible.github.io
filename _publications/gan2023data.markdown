---
layout: publication
title: Ziya2: Data-centric Learning Is All Llms Need
authors: Gan Ruyi, Wu Ziwei, Sun Renliang, Lu Junyu, Wu Xiaojun, Zhang Dixiang, Pan Kunhao, He Junqing, Tian Yuanhe, Yang Ping, Yang Qi, Wang Hao, Zhang Jiaxing, Song Yan
conference: "Arxiv"
year: 2023
bibkey: gan2023data
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.03301"}
tags: ['Efficiency And Optimization', 'Large Scale Training', 'Model Architecture', 'RAG', 'Reinforcement Learning', 'Scaling Laws', 'Training Techniques']
---
Various large language models (LLMs) have been proposed in recent years including closed- and open-source ones continually setting new records on multiple benchmarks. However the development of LLMs still faces several issues such as high cost of training models from scratch and continual pre-training leading to catastrophic forgetting etc. Although many such issues are addressed along the line of research on LLMs an important yet practical limitation is that many studies overly pursue enlarging model sizes without comprehensively analyzing and optimizing the use of pre-training data in their learning process as well as appropriate organization and leveraging of such data in training LLMs under cost-effective settings. In this work we propose Ziya2 a model with 13 billion parameters adopting LLaMA2 as the foundation model and further pre-trained on 700 billion tokens where we focus on pre-training techniques and use data-centric optimization to enhance the learning process of Ziya2 on different stages. We define three data attributes and firstly establish data-centric scaling laws to illustrate how different data impacts LLMs. Experiments show that Ziya2 significantly outperforms other models in multiple benchmarks especially with promising results compared to representative open-source ones. Ziya2 (Base) is released at https://huggingface.co/IDEA-CCNL/Ziya2-13B-Base and https://modelscope.cn/models/Fengshenbang/Ziya2-13B-Base/summary."
