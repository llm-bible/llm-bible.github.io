---
layout: publication
title: Mmgrec&#58; Multimodal Generative Recommendation With Transformer Model
authors: Liu Han, Wei Yinwei, Song Xuemeng, Guan Weili, Li Yuan-fang, Nie Liqiang
conference: "Arxiv"
year: 2024
bibkey: liu2024multimodal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.16555"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'GPT', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Quantization', 'Transformer']
---
Multimodal recommendation aims to recommend user-preferred candidates based on her/his historically interacted items and associated multimodal information. Previous studies commonly employ an embed-and-retrieve paradigm learning user and item representations in the same embedding space then retrieving similar candidate items for a user via embedding inner product. However this paradigm suffers from inference cost interaction modeling and false-negative issues. Toward this end we propose a new MMGRec model to introduce a generative paradigm into multimodal recommendation. Specifically we first devise a hierarchical quantization method Graph RQ-VAE to assign Rec-ID for each item from its multimodal and CF information. Consisting of a tuple of semantically meaningful tokens Rec-ID serves as the unique identifier of each item. Afterward we train a Transformer-based recommender to generate the Rec-IDs of user-preferred items based on historical interaction sequences. The generative paradigm is qualified since this model systematically predicts the tuple of tokens identifying the recommended item in an autoregressive manner. Moreover a relation-aware self-attention mechanism is devised for the Transformer to handle non-sequential interaction sequences which explores the element pairwise relation to replace absolute positional encoding. Extensive experiments evaluate MMGRecs effectiveness compared with state-of-the-art methods.
