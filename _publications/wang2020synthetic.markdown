---
layout: publication
title: SRQA Synthetic Reader For Factoid Question Answering
authors: Wang Jiuniu, Xu Wenjia, Fu Xingyu, Wei Yang, Jin Li, Chen Ziyan, Xu Guangluan, Wu Yirong
conference: "Knowledge-Based Systems Volume"
year: 2020
bibkey: wang2020synthetic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2009.01630"}
tags: ['Applications', 'Attention Mechanism', 'Efficiency And Optimization', 'Model Architecture', 'Security', 'Training Techniques', 'Transformer']
---
The question answering system can answer questions from various fields and forms with deep neural networks but it still lacks effective ways when facing multiple evidences. We introduce a new model called SRQA which means Synthetic Reader for Factoid Question Answering. This model enhances the question answering system in the multi45;document scenario from three aspects model structure optimization goal and training method corresponding to Multilayer Attention (MA) Cross Evidence (CE) and Adversarial Training (AT) respectively. First we propose a multilayer attention network to obtain a better representation of the evidences. The multilayer attention mechanism conducts interaction between the question and the passage within each layer making the token representation of evidences in each layer takes the requirement of the question into account. Second we design a cross evidence strategy to choose the answer span within more evidences. We improve the optimization goal considering all the answers locations in multiple evidences as training targets which leads the model to reason among multiple evidences. Third adversarial training is employed to high45;level variables besides the word embedding in our model. A new normalization method is also proposed for adversarial perturbations so that we can jointly add perturbations to several target variables. As an effective regularization method adversarial training enhances the models ability to process noisy data. Combining these three strategies we enhance the contextual representation and locating ability of our model which could synthetically extract the answer span from several evidences. We perform SRQA on the WebQA dataset and experiments show that our model outperforms the state45;of45;the45;art models (the best fuzzy score of our model is up to 78.5637; with an improvement of about 237;).
