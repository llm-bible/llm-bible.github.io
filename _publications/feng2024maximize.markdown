---
layout: publication
title: 'Maximize Your Data''s Potential: Enhancing LLM Accuracy With Two-phase Pretraining'
authors: Steven Feng, Shrimai Prabhumoye, Kezhi Kong, Dan Su, Mostofa Patwary, Mohammad Shoeybi, Bryan Catanzaro
conference: "Arxiv"
year: 2024
bibkey: feng2024maximize
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.15285"}
tags: ['RAG', 'Training Techniques', 'Pretraining Methods']
---
Pretraining large language models effectively requires strategic data
selection, blending and ordering. However, key details about data mixtures
especially their scalability to longer token horizons and larger model sizes
remain underexplored due to limited disclosure by model developers. To address
this, we formalize the concept of two-phase pretraining and conduct an
extensive systematic study on how to select and mix data to maximize model
accuracies for the two phases. Our findings illustrate that a two-phase
approach for pretraining outperforms random data ordering and natural
distribution of tokens by 3.4% and 17% on average accuracies. We provide
in-depth guidance on crafting optimal blends based on quality of the data
source and the number of epochs to be seen. We propose to design blends using
downsampled data at a smaller scale of 1T tokens and then demonstrate effective
scaling of our approach to larger token horizon of 15T tokens and larger model
size of 25B model size. These insights provide a series of steps practitioners
can follow to design and scale their data blends.
