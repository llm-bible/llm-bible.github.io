---
layout: publication
title: 'Contrastive Multi-document Question Generation'
authors: Cho Woon Sang, Zhang Yizhe, Rao Sudha, Celikyilmaz Asli, Xiong Chenyan, Gao Jianfeng, Wang Mengdi, Dolan Bill
conference: "Arxiv"
year: 2019
bibkey: cho2019contrastive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1911.03047"}
tags: ['Agentic', 'Attention Mechanism', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Tools']
---
Multi-document question generation focuses on generating a question that covers the common aspect of multiple documents. Such a model is useful in generating clarifying options. However a naive model trained only using the targeted (positive) document set may generate too generic questions that cover a larger scope than delineated by the document set. To address this challenge we introduce the contrastive learning strategy where given positive and negative sets of documents we generate a question that is closely related to the positive set but is far away from the negative set. This setting allows generated questions to be more specific and related to the target document set. To generate such specific questions we propose Multi-Source Coordinated Question Generator (MSCQG) a novel framework that includes a supervised learning (SL) stage and a reinforcement learning (RL) stage. In the SL stage a single-document question generator is trained. In the RL stage a coordinator model is trained to find optimal attention weights to align multiple single-document generators by optimizing a reward designed to promote specificity of generated questions. We also develop an effective auxiliary objective named Set-induced Contrastive Regularization (SCR) that improves the coordinators contrastive learning during the RL stage. We show that our model significantly outperforms several strong baselines as measured by automatic metrics and human evaluation. The source repository is publicly available at (urlwww.github.com/woonsangcho/contrast_qgen).
