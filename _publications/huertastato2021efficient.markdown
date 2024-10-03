---
layout: publication
title: 'SILT: Efficient Transformer Training For Inter-lingual Inference'
authors: Huertas-tato Javier, Martín Alejandro, Camacho David
conference: "Arxiv"
year: 2021
bibkey: huertastato2021efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2103.09635"}
  - {name: "Code", url: "https://github.com/jahuerta92/siamese-inter-lingual-transformer"}
tags: ['Applications', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
The ability of transformers to perform precision tasks such as question answering, Natural Language Inference (NLI) or summarising, have enabled them to be ranked as one of the best paradigm to address Natural Language Processing (NLP) tasks. NLI is one of the best scenarios to test these architectures, due to the knowledge required to understand complex sentences and established relationships between a hypothesis and a premise. Nevertheless, these models suffer from incapacity to generalise to other domains or difficulties to face multilingual and interlingual scenarios. The leading pathway in the literature to address these issues involve designing and training extremely large architectures, which leads to unpredictable behaviours and to establish barriers which impede broad access and fine tuning. In this paper, we propose a new architecture called Siamese Inter-Lingual Transformer (SILT), to efficiently align multilingual embeddings for Natural Language Inference, allowing for unmatched language pairs to be processed. SILT leverages siamese pre-trained multi-lingual transformers with frozen weights where the two input sentences attend each other to later be combined through a matrix alignment method. The experimental results carried out in this paper evidence that SILT allows to reduce drastically the number of trainable parameters while allowing for inter-lingual NLI and achieving state-of-the-art performance on common benchmarks. We make our code and dataset available at https://github.com/jahuerta92/siamese-inter-lingual-transformer.
