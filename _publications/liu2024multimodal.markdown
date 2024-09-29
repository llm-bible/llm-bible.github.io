---
layout: publication
title: Mmgrec Multimodal Generative Recommendation With Transformer Model
authors: Liu Han, Wei Yinwei, Song Xuemeng, Guan Weili, Li Yuan-fang, Nie Liqiang
conference: "Arxiv"
year: 2024
bibkey: liu2024multimodal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.16555"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'GPT', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Quantization', 'Transformer']
---
Multimodal recommendation aims to recommend user45;preferred candidates based on her/his historically interacted items and associated multimodal information. Previous studies commonly employ an embed45;and45;retrieve paradigm learning user and item representations in the same embedding space then retrieving similar candidate items for a user via embedding inner product. However this paradigm suffers from inference cost interaction modeling and false45;negative issues. Toward this end we propose a new MMGRec model to introduce a generative paradigm into multimodal recommendation. Specifically we first devise a hierarchical quantization method Graph RQ45;VAE to assign Rec45;ID for each item from its multimodal and CF information. Consisting of a tuple of semantically meaningful tokens Rec45;ID serves as the unique identifier of each item. Afterward we train a Transformer45;based recommender to generate the Rec45;IDs of user45;preferred items based on historical interaction sequences. The generative paradigm is qualified since this model systematically predicts the tuple of tokens identifying the recommended item in an autoregressive manner. Moreover a relation45;aware self45;attention mechanism is devised for the Transformer to handle non45;sequential interaction sequences which explores the element pairwise relation to replace absolute positional encoding. Extensive experiments evaluate MMGRecs effectiveness compared with state45;of45;the45;art methods.
