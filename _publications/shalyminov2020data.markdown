---
layout: publication
title: Data45;efficient Methods For Dialogue Systems
authors: Shalyminov Igor
conference: "Arxiv"
year: 2020
bibkey: shalyminov2020data
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2012.02929"}
tags: ['Applications', 'Efficiency And Optimization', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Security', 'Training Techniques', 'Transformer']
---
Conversational User Interface (CUI) has become ubiquitous in everyday life in consumer45;focused products like Siri and Alexa or business45;oriented solutions. Deep learning underlies many recent breakthroughs in dialogue systems but requires very large amounts of training data often annotated by experts. Trained with smaller data these methods end up severely lacking robustness (e.g. to disfluencies and out45;of45;domain input) and often just have too little generalisation power. In this thesis we address the above issues by introducing a series of methods for training robust dialogue systems from minimal data. Firstly we study two orthogonal approaches to dialogue linguistically informed and machine learning45;based 45; from the data efficiency perspective. We outline the steps to obtain data45;efficient solutions with either approach. We then introduce two data45;efficient models for dialogue response generation the Dialogue Knowledge Transfer Network based on latent variable dialogue representations and the hybrid Generative45;Retrieval Transformer model (ranked first at the DSTC 8 Fast Domain Adaptation task). Next we address the problem of robustness given minimal data. As such propose a multitask LSTM45;based model for domain45;general disfluency detection. For the problem of out45;of45;domain input we present Turn Dropout a data augmentation technique for anomaly detection only using in45;domain data and introduce autoencoder45;augmented models for efficient training with Turn Dropout. Finally we focus on social dialogue and introduce a neural model for response ranking in social conversation used in Alana the 3rd place winner in the Amazon Alexa Prize 2017 and 2018. We employ a novel technique of predicting the dialogue length as the main ranking objective and show that this approach improves upon the ratings45;based counterpart in terms of data efficiency while matching it in performance.
