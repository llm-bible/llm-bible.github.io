---
layout: publication
title: 'On The Effect Of Pre-training For Transformer In Different Modality On Offline Reinforcement Learning'
authors: Takagi Shiro
conference: "Advances in Neural Information Processing Systems"
year: 2022
bibkey: takagi2022effect
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2211.09817"}
tags: ['Agentic', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
We empirically investigate how pre-training on data of different modalities such as language and vision affects fine-tuning of Transformer-based models to Mujoco offline reinforcement learning tasks. Analysis of the internal representation reveals that the pre-trained Transformers acquire largely different representations before and after pre-training but acquire less information of data in fine-tuning than the randomly initialized one. A closer look at the parameter changes of the pre-trained Transformers reveals that their parameters do not change that much and that the bad performance of the model pre-trained with image data could partially come from large gradients and gradient clipping. To study what information the Transformer pre-trained with language data utilizes we fine-tune this model with no context provided finding that the model learns efficiently even without context information. Subsequent follow-up analysis supports the hypothesis that pre-training with language data is likely to make the Transformer get context-like information and utilize it to solve the downstream task.
