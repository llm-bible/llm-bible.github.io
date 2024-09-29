---
layout: publication
title: MEGABYTE Predicting Million45;byte Sequences With Multiscale Transformers
authors: Yu Lili, Simig Dániel, Flaherty Colin, Aghajanyan Armen, Zettlemoyer Luke, Lewis Mike
conference: "Arxiv"
year: 2023
bibkey: yu2023predicting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.07185"}
tags: ['Attention Mechanism', 'GPT', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Tokenization', 'Training Techniques', 'Transformer']
---
Autoregressive transformers are spectacular models for short sequences but scale poorly to long sequences such as high45;resolution images podcasts code or books. We proposed Megabyte a multi45;scale decoder architecture that enables end45;to45;end differentiable modeling of sequences of over one million bytes. Megabyte segments sequences into patches and uses a local submodel within patches and a global model between patches. This enables sub45;quadratic self45;attention much larger feedforward layers for the same compute and improved parallelism during decoding 45;45; unlocking better performance at reduced cost for both training and generation. Extensive experiments show that Megabyte allows byte45;level models to perform competitively with subword models on long context language modeling achieve state45;of45;the45;art density estimation on ImageNet and model audio from raw files. Together these results establish the viability of tokenization45;free autoregressive sequence modeling at scale.
