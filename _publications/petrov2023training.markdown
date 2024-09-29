---
layout: publication
title: Recjpq Training Large45;catalogue Sequential Recommenders
authors: Petrov Aleksandr V., Macdonald Craig
conference: "Arxiv"
year: 2023
bibkey: petrov2023training
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.06165"}
tags: ['Applications', 'BERT', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Sequential Recommendation is a popular recommendation task that uses the order of user45;item interaction to model evolving users interests and sequential patterns in their behaviour. Current state45;of45;the45;art Transformer45;based models for sequential recommendation such as BERT4Rec and SASRec generate sequence embeddings and compute scores for catalogue items but the increasing catalogue size makes training these models costly. The Joint Product Quantisation (JPQ) method originally proposed for passage retrieval markedly reduces the size of the retrieval index with minimal effect on model effectiveness by replacing passage embeddings with a limited number of shared sub45;embeddings. This paper introduces RecJPQ a novel adaptation of JPQ for sequential recommendations which takes the place of item embeddings tensor and replaces item embeddings with a concatenation of a limited number of shared sub45;embeddings and therefore limits the number of learnable model parameters. The main idea of RecJPQ is to split items into sub45;item entities before training the main recommendation model which is inspired by splitting words into tokens and training tokenisers in language models. We apply RecJPQ to SASRec BERT4Rec and GRU4rec models on three large45;scale sequential datasets. Our results showed that RecJPQ could notably reduce the model size (e.g. 4837; reduction for the Gowalla dataset with no effectiveness degradation). RecJPQ can also improve model performance through a regularisation effect (e.g. +0.9637; NDCG35;64;10 improvement on the Booking.com dataset). Overall RecJPQ allows the training of state45;of45;the45;art transformer recommenders in industrial applications where datasets with millions of items are common.
