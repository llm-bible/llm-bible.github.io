---
layout: publication
title: Stress Test Evaluation Of Transformer45;based Models In Natural Language Understanding Tasks
authors: Aspillaga Carlos, Carvallo Andrés, Araujo Vladimir
conference: "Arxiv"
year: 2020
bibkey: aspillaga2020stress
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2002.06261"}
tags: ['Applications', 'BERT', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Security', 'Training Techniques', 'Transformer']
---
There has been significant progress in recent years in the field of Natural Language Processing thanks to the introduction of the Transformer architecture. Current state45;of45;the45;art models via a large number of parameters and pre45;training on massive text corpus have shown impressive results on several downstream tasks. Many researchers have studied previous (non45;Transformer) models to understand their actual behavior under different scenarios showing that these models are taking advantage of clues or failures of datasets and that slight perturbations on the input data can severely reduce their performance. In contrast recent models have not been systematically tested with adversarial45;examples in order to show their robustness under severe stress conditions. For that reason this work evaluates three Transformer45;based models (RoBERTa XLNet and BERT) in Natural Language Inference (NLI) and Question Answering (QA) tasks to know if they are more robust or if they have the same flaws as their predecessors. As a result our experiments reveal that RoBERTa XLNet and BERT are more robust than recurrent neural network models to stress tests for both NLI and QA tasks. Nevertheless they are still very fragile and demonstrate various unexpected behaviors thus revealing that there is still room for future improvement in this field.
