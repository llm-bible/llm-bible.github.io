---
layout: publication
title: 'Resmoe: Space-efficient Compression Of Mixture Of Experts Llms Via Residual Restoration'
authors: Mengting Ai, Tianxin Wei, Yifan Chen, Zhichen Zeng, Ritchie Zhao, Girish Varatkar, Bita Darvish Rouhani, Xianfeng Tang, Hanghang Tong, Jingrui He
conference: "Arxiv"
year: 2025
bibkey: ai2025space
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.06881"}
  - {name: "Code", url: "https://github.com/iDEA-iSAIL-Lab-UIUC/ResMoE"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Tools', 'RAG', 'Pretraining Methods', 'Transformer', 'Has Code']
---
Mixture-of-Experts (MoE) Transformer, the backbone architecture of multiple
phenomenal language models, leverages sparsity by activating only a fraction of
model parameters for each input token. The sparse structure, while allowing
constant time costs, results in space inefficiency: we still need to load all
the model parameters during inference. We introduce ResMoE, an innovative MoE
approximation framework that utilizes Wasserstein barycenter to extract a
common expert (barycenter expert) and approximate the residuals between this
barycenter expert and the original ones. ResMoE enhances the space efficiency
for inference of large-scale MoE Transformers in a one-shot and data-agnostic
manner without retraining while maintaining minimal accuracy loss, thereby
paving the way for broader accessibility to large language models. We
demonstrate the effectiveness of ResMoE through extensive experiments on Switch
Transformer, Mixtral, and DeepSeekMoE models. The results show that ResMoE can
reduce the number of parameters in an expert by up to 75% while maintaining
comparable performance. The code is available at
https://github.com/iDEA-iSAIL-Lab-UIUC/ResMoE.
