---
layout: publication
title: Contextual Parameter Generation For Universal Neural Machine Translation
authors: Platanios Emmanouil Antonios, Sachan Mrinmaya, Neubig Graham, Mitchell Tom
conference: "Arxiv"
year: 2018
bibkey: platanios2018contextual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1808.08493"}
tags: ['Applications', 'Fine Tuning', 'Model Architecture', 'Training Techniques']
---
We propose a simple modification to existing neural machine translation (NMT) models that enables using a single universal model to translate between multiple languages while allowing for language specific parameterization and that can also be used for domain adaptation. Our approach requires no changes to the model architecture of a standard NMT system but instead introduces a new component the contextual parameter generator (CPG) that generates the parameters of the system (e.g. weights in a neural network). This parameter generator accepts source and target language embeddings as input and generates the parameters for the encoder and the decoder respectively. The rest of the model remains unchanged and is shared across all languages. We show how this simple modification enables the system to use monolingual data for training and also perform zero45;shot translation. We further show it is able to surpass state45;of45;the45;art performance for both the IWSLT45;15 and IWSLT45;17 datasets and that the learned language embeddings are able to uncover interesting relationships between languages.
