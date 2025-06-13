---
layout: publication
title: 'ENCONTER: Entity Constrained Progressive Sequence Generation Via Insertion-based Transformer'
authors: Lee-hsun Hsieh, Yang-yin Lee, Ee-peng Lim
conference: "Arxiv"
year: 2021
bibkey: hsieh2021entity
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2103.09548'}
  - {name: "Code", url: 'https://github.com/LARC-CMU-SMU/Enconter'}
tags: ['Has Code', 'Transformer', 'Efficiency and Optimization', 'Training Techniques', 'Applications', 'Model Architecture', 'GPT', 'Reinforcement Learning', 'Pretraining Methods']
---
Pretrained using large amount of data, autoregressive language models are
able to generate high quality sequences. However, these models do not perform
well under hard lexical constraints as they lack fine control of content
generation process. Progressive insertion-based transformers can overcome the
above limitation and efficiently generate a sequence in parallel given some
input tokens as constraint. These transformers however may fail to support hard
lexical constraints as their generation process is more likely to terminate
prematurely. The paper analyses such early termination problems and proposes
the Entity-constrained insertion transformer (ENCONTER), a new insertion
transformer that addresses the above pitfall without compromising much
generation efficiency. We introduce a new training strategy that considers
predefined hard lexical constraints (e.g., entities to be included in the
generated sequence). Our experiments show that ENCONTER outperforms other
baseline models in several performance metrics rendering it more suitable in
practical applications. Our code is available at
https://github.com/LARC-CMU-SMU/Enconter
