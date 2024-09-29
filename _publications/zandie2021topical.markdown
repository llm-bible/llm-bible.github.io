---
layout: publication
title: Topical Language Generation Using Transformers
authors: Zandie Rohola, Mahoor Mohammad H.
conference: "Arxiv"
year: 2021
bibkey: zandie2021topical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2103.06434"}
tags: ['Applications', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Large45;scale transformer45;based language models (LMs) demonstrate impressive capabilities in open text generation. However controlling the generated texts properties such as the topic style and sentiment is challenging and often requires significant changes to the model architecture or retraining and fine45;tuning the model on new supervised data. This paper presents a novel approach for Topical Language Generation (TLG) by combining a pre45;trained LM with topic modeling information. We cast the problem using Bayesian probability formulation with topic probabilities as a prior LM probabilities as the likelihood and topical language generation probability as the posterior. In learning the model we derive the topic probability distribution from the user45;provided documents natural structure. Furthermore we extend our model by introducing new parameters and functions to influence the quantity of the topical features presented in the generated text. This feature would allow us to easily control the topical properties of the generated text. Our experimental results demonstrate that our model outperforms the state45;of45;the45;art results on coherency diversity and fluency while being faster in decoding.
