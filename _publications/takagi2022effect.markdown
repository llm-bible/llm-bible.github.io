---
layout: publication
title: On The Effect Of Pre45;training For Transformer In Different Modality On Offline Reinforcement Learning
authors: Takagi Shiro
conference: "Advances in Neural Information Processing Systems"
year: 2022
bibkey: takagi2022effect
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2211.09817"}
tags: ['Agentic', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
We empirically investigate how pre45;training on data of different modalities such as language and vision affects fine45;tuning of Transformer45;based models to Mujoco offline reinforcement learning tasks. Analysis of the internal representation reveals that the pre45;trained Transformers acquire largely different representations before and after pre45;training but acquire less information of data in fine45;tuning than the randomly initialized one. A closer look at the parameter changes of the pre45;trained Transformers reveals that their parameters do not change that much and that the bad performance of the model pre45;trained with image data could partially come from large gradients and gradient clipping. To study what information the Transformer pre45;trained with language data utilizes we fine45;tune this model with no context provided finding that the model learns efficiently even without context information. Subsequent follow45;up analysis supports the hypothesis that pre45;training with language data is likely to make the Transformer get context45;like information and utilize it to solve the downstream task.
