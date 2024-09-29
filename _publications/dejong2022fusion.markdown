---
layout: publication
title: Fido Fusion45;in45;decoder Optimized For Stronger Performance And Faster Inference
authors: De Jong Michiel, Zemlyanskiy Yury, Ainslie Joshua, Fitzgerald Nicholas, Sanghai Sumit, Sha Fei, Cohen William
conference: "Arxiv"
year: 2022
bibkey: dejong2022fusion
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2212.08153"}
tags: ['Merging', 'Model Architecture', 'Pretraining Methods']
---
Fusion45;in45;Decoder (FiD) is a powerful retrieval45;augmented language model that sets the state45;of45;the45;art on many knowledge45;intensive NLP tasks. However the architecture used for FiD was chosen by making minimal modifications to a standard T5 model which our analysis shows to be highly suboptimal for a retrieval45;augmented model. In particular FiD allocates the bulk of FLOPs to the encoder while the majority of inference time results from memory bandwidth constraints in the decoder. We propose two simple changes to the FiD architecture to alleviate memory bandwidth constraints and speed up inference by 7x. This allows us to use a much larger decoder at modest cost. We denote FiD with the above modifications as FiDO and show that it strongly improves performance over existing FiD models for a wide range of inference budgets. For example FiDO45;Large45;XXL performs faster inference than FiD45;Base and achieves better performance than FiD45;Large.
