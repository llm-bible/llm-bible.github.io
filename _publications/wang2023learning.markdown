---
layout: publication
title: Learning to Grow Pretrained Models for Efficient Transformer Training
authors: Wang Peihao, Panda Rameswar, Hennigen Lucas Torroba, Greengard Philip, Karlinsky Leonid, Feris Rogerio, Cox David Daniel, Wang Zhangyang, Kim Yoon
conference: "Arxiv"
year: 2023
bibkey: wang2023learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2303.00980"}
tags: ['ARXIV', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Scaling transformers has led to significant breakthroughs in many domains leading to a paradigm in which larger versions of existing models are trained and released on a periodic basis. New instances of such models are typically trained completely from scratch despite the fact that they are often just scaled-up versions of their smaller counterparts. How can we use the implicit knowledge in the parameters of smaller extant models to enable faster training of newer larger models This paper describes an approach for accelerating transformer training by learning to grow pretrained transformers where we learn to linearly map the parameters of the smaller model to initialize the larger model. For tractable learning we factorize the linear transformation as a composition of (linear) width- and depth-growth operators and further employ a Kronecker factorization of these growth operators to encode architectural knowledge. Extensive experiments across both language and vision transformers demonstrate that our learned Linear Growth Operator (LiGO) can save up to 50 computational cost of training from scratch while also consistently outperforming strong baselines that also reuse smaller pretrained models to initialize larger models.
