---
layout: publication
title: Enhancing Robustness of Vision-Language Models through Orthogonality Learning and Cross-Regularization
authors: Li Jinlong, Jie Zequn, Ricci Elisa, Ma Lin, Sebe Nicu
conference: "Arxiv"
year: 2024
bibkey: li2024enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.08374"}
tags: ['Attention Mechanism', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Prompting', 'Security', 'Training Techniques', 'Transformer']
---
Efficient finetuning of vision-language models (VLMs) like CLIP for specific downstream tasks is gaining significant attention. Previous works primarily focus on prompt learning to adapt the CLIP into a variety of downstream tasks however suffering from task overfitting when finetuned on a small data set. In this paper we introduce an orthogonal finetuning method for efficiently updating pretrained weights which enhances robustness and generalization while a cross-regularization strategy is further exploited to maintain the stability in terms of zero-shot generalization of VLMs dubbed textbftextitOrthCR. Specifically trainable orthogonal matrices are injected seamlessly into the transformer architecture and enforced with orthogonality constraint using Cayley parameterization benefiting from the norm-preserving property and thus leading to stable and faster convergence. To alleviate deviation from orthogonal constraint during training a cross-regularization strategy is further employed with initial pretrained weights within a bypass manner. In addition to enrich the sample diversity for downstream tasks we first explore Cutout data augmentation to boost the efficient finetuning and comprehend how our approach improves the specific downstream performance and maintains the generalizability in the perspective of Orthogonality Learning. Beyond existing prompt learning techniques we conduct extensive experiments to demonstrate that our method explicitly steers pretrained weight space to represent the task-specific knowledge and presents competitive generalizability under base-to-base/base-to-new cross-dataset transfer and domain generalization evaluations.
