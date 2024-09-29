---
layout: publication
title: On Incorporating Structural Information To Improve Dialogue Response Generation
authors: Moghe Nikita, Vijayan Priyesh, Ravindran Balaraman, Khapra Mitesh M.
conference: "Arxiv"
year: 2020
bibkey: moghe2020incorporating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2005.14315"}
tags: ['Applications', 'Attention Mechanism', 'BERT', 'Model Architecture', 'Reinforcement Learning', 'Survey Paper', 'Tools']
---
We consider the task of generating dialogue responses from background knowledge comprising of domain specific resources. Specifically given a conversation around a movie the task is to generate the next response based on background knowledge about the movie such as the plot review Reddit comments etc. This requires capturing structural sequential and semantic information from the conversation context and the background resources. This is a new task and has not received much attention from the community. We propose a new architecture that uses the ability of BERT to capture deep contextualized representations in conjunction with explicit structure and sequence information. More specifically we use (i) Graph Convolutional Networks (GCNs) to capture structural information (ii) LSTMs to capture sequential information and (iii) BERT for the deep contextualized representations that capture semantic information. We analyze the proposed architecture extensively. To this end we propose a plug45;and45;play Semantics45;Sequences45;Structures (SSS) framework which allows us to effectively combine such linguistic information. Through a series of experiments we make some interesting observations. First we observe that the popular adaptation of the GCN model for NLP tasks where structural information (GCNs) was added on top of sequential information (LSTMs) performs poorly on our task. This leads us to explore interesting ways of combining semantic and structural information to improve the performance. Second we observe that while BERT already outperforms other deep contextualized representations such as ELMo it still benefits from the additional structural information explicitly added using GCNs. This is a bit surprising given the recent claims that BERT already captures structural information. Lastly the proposed SSS framework gives an improvement of 7.9537; over the baseline.
