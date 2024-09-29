---
layout: publication
title: Generative Negative Text Replay For Continual Vision45;language Pretraining
authors: Yan Shipeng, Hong Lanqing, Xu Hang, Han Jianhua, Tuytelaars Tinne, Li Zhenguo, He Xuming
conference: "Arxiv"
year: 2022
bibkey: yan2022generative
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.17322"}
tags: ['Applications', 'Attention Mechanism', 'Distillation', 'Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
Vision45;language pre45;training (VLP) has attracted increasing attention recently. With a large amount of image45;text pairs VLP models trained with contrastive loss have achieved impressive performance in various tasks especially the zero45;shot generalization on downstream datasets. In practical applications however massive data are usually collected in a streaming fashion requiring VLP models to continuously integrate novel knowledge from incoming data and retain learned knowledge. In this work we focus on learning a VLP model with sequential chunks of image45;text pair data. To tackle the catastrophic forgetting issue in this multi45;modal continual learning setting we first introduce pseudo text replay that generates hard negative texts conditioned on the training images in memory which not only better preserves learned knowledge but also improves the diversity of negative samples in the contrastive loss. Moreover we propose multi45;modal knowledge distillation between images and texts to align the instance45;wise prediction between old and new models. We incrementally pre45;train our model on both the instance and class incremental splits of the Conceptual Caption dataset and evaluate the model on zero45;shot image classification and image45;text retrieval tasks. Our method consistently outperforms the existing baselines with a large margin which demonstrates its superiority. Notably we realize an average performance boost of 4.6037; on image45;classification downstream datasets for the class incremental split.
