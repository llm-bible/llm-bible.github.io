---
layout: publication
title: Self-generated Replay Memories for Continual Neural Machine Translation
authors: Resta Michele, Bacciu Davide
conference: "Arxiv"
year: 2024
bibkey: resta2024self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.13130"}
  - {name: "Code", url: "https://github.com/m-resta/sg-rep"}
tags: ['Applications', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Training Techniques', 'Transformer']
---
Modern Neural Machine Translation systems exhibit strong performance in several different languages and are constantly improving. Their ability to learn continuously is however still severely limited by the catastrophic forgetting issue. In this work we leverage a key property of encoder-decoder Transformers i.e. their generative ability to propose a novel approach to continually learning Neural Machine Translation systems. We show how this can effectively learn on a stream of experiences comprising different languages by leveraging a replay memory populated by using the model itself as a generator of parallel sentences. We empirically demonstrate that our approach can counteract catastrophic forgetting without requiring explicit memorization of training data. Code will be publicly available upon publication. Code https://github.com/m-resta/sg-rep
