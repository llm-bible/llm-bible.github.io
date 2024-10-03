---
layout: publication
title: 'Masked Mixers For Language Generation And Retrieval'
authors: Badger Benjamin L.
conference: "Arxiv"
year: 2024
bibkey: badger2024masked
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.01482"}
tags: ['Attention Mechanism', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Attention mechanisms that confer selective focus on a strict subset of input elements are nearly ubiquitous in language models today. We posit there to be downside to the use of attention: most information present in the input is necessarily lost. In support of this idea we observe poor input representation accuracy in transformers, but find more accurate representation in what we term masked mixers which replace self-attention with masked convolutions. Applied to TinyStories the masked mixer learns causal language tasks more efficiently than early transformer implementations and somewhat less efficiently than optimized, current implementations. The most efficient learning algorithm observed for this dataset is a transformer-masked mixer hybrid, suggesting that these models learn in an orthogonal manner. We hypothesized that the information loss exhibited by transformers would be much more detrimental to retrieval than generation, and to test this we introduce an efficient training approach for retrieval models based on existing generative model embeddings. With this method, embeddings from masked mixers are found to result in far better summary-to-story retrieval compared to embeddings from transformers.
