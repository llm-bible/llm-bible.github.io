---
layout: publication
title: 'Predictable Scale: Part I -- Optimal Hyperparameter Scaling Law In Large Language Model Pretraining'
authors: Houyi Li, Wenzhen Zheng, Qiufeng Wang, Hanshan Zhang, Zili Wang, Shijie Xuyang, Yuantao Fan, Shuigeng Zhou, Xiangyu Zhang, Daxin Jiang
conference: "Arxiv"
year: 2025
bibkey: li2025predictable
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.04715'}
  - {name: "Code", url: 'https://step-law.github.io/'}
tags: ['Large-Scale Training', 'Has Code', 'Transformer', 'Efficiency and Optimization', 'Security', 'Model Architecture', 'Training Techniques', 'Scaling Laws', 'Pruning', 'Reinforcement Learning', 'Pre-Training', 'Pretraining Methods']
---
The impressive capabilities of Large Language Models (LLMs) across diverse tasks are now well-established, yet their effective deployment necessitates careful hyperparameter optimization. Through extensive empirical studies involving grid searches across diverse configurations, we discover universal scaling laws governing these hyperparameters: optimal learning rate follows a power-law relationship with both model parameters and data sizes, while optimal batch size scales primarily with data sizes. Our analysis reveals a convex optimization landscape for hyperparameters under fixed models and data size conditions. This convexity implies an optimal hyperparameter plateau. We contribute a universal, plug-and-play optimal hyperparameter tool for the community. Its estimated values on the test set are merely 0.09% away from the globally optimal LLM performance found via an exhaustive search. These laws demonstrate remarkable robustness across variations in model sparsity, training data distribution, and model shape. To our best known, this is the first work that unifies different model shapes and structures, such as Mixture-of-Experts models and dense transformers, as well as establishes optimal hyperparameter scaling laws across diverse data distributions. This exhaustive optimization process demands substantial computational resources, utilizing nearly one million NVIDIA H800 GPU hours to train 3,700 LLMs of varying sizes and hyperparameters from scratch and consuming approximately 100 trillion tokens in total. To facilitate reproducibility and further research, we will progressively release all loss measurements and model checkpoints through our designated repository https://step-law.github.io/
