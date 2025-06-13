---
layout: publication
title: 'TESS 2: A Large-scale Generalist Diffusion Language Model'
authors: Jaesung Tae, Hamish Ivison, Sachin Kumar, Arman Cohan
conference: "Arxiv"
year: 2025
bibkey: tae2025tess
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.13917"}
  - {name: "Code", url: "https://github.com/hamishivi/tess-2"}
tags: ['GPT', 'Merging', 'Reinforcement Learning', 'Training Techniques', 'Has Code', 'Pretraining Methods']
---
We introduce TESS 2, a general instruction-following diffusion language model that outperforms contemporary instruction-tuned diffusion models, as well as matches and sometimes exceeds strong autoregressive (AR) models. We train TESS 2 by first adapting a strong AR model via continued pretraining with the usual cross-entropy as diffusion loss, and then performing further instruction tuning. We find that adaptation training as well as the choice of the base model is crucial for training good instruction-following diffusion models. We further propose reward guidance, a novel and modular inference-time guidance procedure to align model outputs without needing to train the underlying model. Finally, we show that TESS 2 further improves with increased inference-time compute, highlighting the utility of diffusion LMs in having fine-grained controllability over the amount of compute used at inference time. Code and models are available at https://github.com/hamishivi/tess-2.
