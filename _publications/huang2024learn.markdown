---
layout: publication
title: 'Learn When (not) To Trust Language Models: A Privacy-centric Adaptive Model-aware Approach'
authors: Huang Chengkai, Wang Rui, Xie Kaige, Yu Tong, Yao Lina
conference: "Arxiv"
year: 2024
bibkey: huang2024learn
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.03514"}
tags: ['Fine Tuning', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
Retrieval-augmented large language models (LLMs) have been remarkably competent in various NLP tasks. Despite their great success the knowledge provided by the retrieval process is not always useful for improving the model prediction since in some samples LLMs may already be quite knowledgeable and thus be able to answer the question correctly without retrieval. Aiming to save the cost of retrieval previous work has proposed to determine when to do/skip the retrieval in a data-aware manner by analyzing the LLMs pretraining data. However these data-aware methods pose privacy risks and memory limitations especially when requiring access to sensitive or extensive pretraining data. Moreover these methods offer limited adaptability under fine-tuning or continual learning settings. We hypothesize that token embeddings are able to capture the models intrinsic knowledge which offers a safer and more straightforward way to judge the need for retrieval without the privacy risks associated with accessing pre-training data. Moreover it alleviates the need to retain all the data utilized during model pre-training necessitating only the upkeep of the token embeddings. Extensive experiments and in-depth analyses demonstrate the superiority of our model-aware approach.
