---
layout: publication
title: Training Compute45;optimal Large Language Models
authors: Jordan Hoffmann, Sebastian Borgeaud, Arthur Mensch, Elena Buchatskaya, Trevor Cai, Eliza Rutherford, Diego De Las Casas, Lisa Anne Hendricks, Johannes Welbl, Aidan Clark, Tom Hennigan, Eric Noland, Katie Millican, George Van Den Driessche, Bogdan Damoc, Aurelia Guy, Simon Osindero, Karen Simonyan, Erich Elsen, Jack W. Rae, Oriol Vinyals, Laurent Sifre
conference: "Arxiv"
year: 2022
bibkey: hoffmann2022training
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2203.15556v1"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Training Techniques', 'Transformer']
---
We investigate the optimal model size and number of tokens for training a transformer language model under a given compute budget. We find that current large language models are significantly undertrained a consequence of the recent focus on scaling language models whilst keeping the amount of training data constant. By training over 400 language models ranging from 70 million to over 16 billion parameters on 5 to 500 billion tokens we find that for compute45;optimal training the model size and the number of training tokens should be scaled equally for every doubling of model size the number of training tokens should also be doubled. We test this hypothesis by training a predicted compute45;optimal model Chinchilla that uses the same compute budget as Gopher but with 70B parameters and 4× more more data. Chinchilla uniformly and significantly outperforms Gopher (280B) GPT45;3 (175B) Jurassic45;1 (178B) and Megatron45;Turing NLG (530B) on a large range of downstream evaluation tasks. This also means that Chinchilla uses substantially less compute for fine45;tuning and inference greatly facilitating downstream usage. As a highlight Chinchilla reaches a state45;of45;the45;art average accuracy of 67.537; on the MMLU benchmark greater than a 737; improvement over Gopher.
