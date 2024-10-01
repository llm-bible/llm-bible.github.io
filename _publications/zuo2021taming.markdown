---
layout: publication
title: 'Taming Sparsely Activated Transformer With Stochastic Experts'
authors: Zuo Simiao, Liu Xiaodong, Jiao Jian, Kim Young Jin, Hassan Hany, Zhang Ruofei, Zhao Tuo, Gao Jianfeng
conference: "Arxiv"
year: 2021
bibkey: zuo2021taming
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2110.04260"}
  - {name: "Code", url: "https://github.com/microsoft/Stochastic-Mixture-of-Experts"}
tags: ['Applications', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Training Techniques', 'Transformer']
---
Sparsely activated models (SAMs), such as Mixture-of-Experts (MoE), can easily scale to have outrageously large amounts of parameters without significant increase in computational cost. However, SAMs are reported to be parameter inefficient such that larger models do not always lead to better performance. While most on-going research focuses on improving SAMs models by exploring methods of routing inputs to experts, our analysis reveals that such research might not lead to the solution we expect, i.e., the commonly-used routing methods based on gating mechanisms do not work better than randomly routing inputs to experts. In this paper, we propose a new expert-based model, THOR (Transformer witH StOchastic ExpeRts). Unlike classic expert-based models, such as the Switch Transformer, experts in THOR are randomly activated for each input during training and inference. THOR models are trained using a consistency regularized loss, where experts learn not only from training data but also from other experts as teachers, such that all the experts make consistent predictions. We validate the effectiveness of THOR on machine translation tasks. Results show that THOR models are more parameter efficient in that they significantly outperform the Transformer and MoE models across various settings. For example, in multilingual translation, THOR outperforms the Switch Transformer by 2 BLEU scores, and obtains the same BLEU score as that of a state-of-the-art MoE model that is 18 times larger. Our code is publicly available at: https://github.com/microsoft/Stochastic-Mixture-of-Experts.
