---
layout: publication
title: 'Unlocking Personalized Knowledge In Federated Large Language Model: The Power Of Mixture Of Experts'
authors: Fan Liu, Bikang Pan, Zhongyi Wang, Xi Yao, Xiaoying Tang, Jingya Wang, Ye Shi
conference: "Arxiv"
year: 2025
bibkey: liu2025unlocking
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2506.00965'}
  - {name: "Code", url: 'https://anonymous.4open.science/r/FLEx-8F12'}
tags: ['Has Code', 'RAG', 'Efficiency and Optimization', 'Model Architecture', 'Tools', 'Pruning']
---
The Mixture of Experts (MoE) architecture has emerged as a prominent strategy for scaling large language models (LLMs), effectively leveraging sparse activation and facilitating task-specific personalization. However, current federated learning (FL) approaches are primarily designed for dense models, making them unable to directly exploit the sparsity inherent in MoE architectures. Treating MoE models as dense networks in federated scenarios results in excessive communication overhead and computational costs, undermining the potential for personalized knowledge sharing. To address these challenges, we propose FLEx (Federated LLMs with Personalized Experts), a novel federated learning framework explicitly tailored for MoE-based LLMs. FLEx efficiently personalizes by pruning the global MoE model to keep only one expert per client, and employs an adaptive gating mechanism to reintegrate these personalized experts into the pre-trained MoE layers, ensuring the original backbone architecture remains unchanged. These personalized experts are trained with local data and stored locally on each client, while the shared modules are aggregated globally. Extensive evaluations on diverse instruction-based datasets under non-IID conditions consistently demonstrate that FLEx outperforms existing federated baselines. Our code is available at https://anonymous.4open.science/r/FLEx-8F12.
