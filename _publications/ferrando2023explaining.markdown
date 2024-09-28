---
layout: publication
title: Explaining How Transformers Use Context to Build Predictions
authors: Ferrando Javier, Gállego Gerard I., Tsiamas Ioannis, Costa-jussà Marta R.
conference: "Arxiv"
year: 2023
bibkey: ferrando2023explaining
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.12535"}
tags: ['ARXIV', 'Applications', 'Interpretability', 'Interpretability And Explainability', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Transformer']
---
Language Generation Models produce words based on the previous context. Although existing methods offer input attributions as explanations for a models prediction it is still unclear how prior words affect the models decision throughout the layers. In this work we leverage recent advances in explainability of the Transformer and present a procedure to analyze models for language generation. Using contrastive examples we compare the alignment of our explanations with evidence of the linguistic phenomena and show that our method consistently aligns better than gradient-based and perturbation-based baselines. Then we investigate the role of MLPs inside the Transformer and show that they learn features that help the model predict words that are grammatically acceptable. Lastly we apply our method to Neural Machine Translation models and demonstrate that they generate human-like source-target alignments for building predictions.
