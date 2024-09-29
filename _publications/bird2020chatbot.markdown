---
layout: publication
title: Chatbot Interaction With Artificial Intelligence Human Data Augmentation With T5 And Language Transformer Ensemble For Text Classification
authors: Bird Jordan J., Ekárt Anikó, Faria Diego R.
conference: "Arxiv"
year: 2020
bibkey: bird2020chatbot
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2010.05990"}
tags: ['Attention Mechanism', 'BERT', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Tools', 'Training Techniques', 'Transformer']
---
In this work we present the Chatbot Interaction with Artificial Intelligence (CI45;AI) framework as an approach to the training of deep learning chatbots for task classification. The intelligent system augments human45;sourced data via artificial paraphrasing in order to generate a large set of training data for further classical attention and language transformation45;based learning approaches for Natural Language Processing. Human beings are asked to paraphrase commands and questions for task identification for further execution of a machine. The commands and questions are split into training and validation sets. A total of 483 responses were recorded. Secondly the training set is paraphrased by the T5 model in order to augment it with further data. Seven state45;of45;the45;art transformer45;based text classification algorithms (BERT DistilBERT RoBERTa DistilRoBERTa XLM XLM45;RoBERTa and XLNet) are benchmarked for both sets after fine45;tuning on the training data for two epochs. We find that all models are improved when training data is augmented by the T5 model with an average increase of classification accuracy by 4.0137;. The best result was the RoBERTa model trained on T5 augmented data which achieved 98.9637; classification accuracy. Finally we found that an ensemble of the five best45;performing transformer models via Logistic Regression of output label predictions led to an accuracy of 99.5937; on the dataset of human responses. A highly45;performing model allows the intelligent system to interpret human commands at the social45;interaction level through a chatbot45;like interface (e.g. Robot can we have a conversation) and allows for better accessibility to AI by non45;technical users.
