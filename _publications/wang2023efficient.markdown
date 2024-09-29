---
layout: publication
title: BERT4CTR An Efficient Framework To Combine Pre45;trained Language Model With Non45;textual Features For CTR Prediction
authors: Wang Dong, Salamatian Kavé, Xia Yunqing, Deng Weiwei, Zhiang Qi
conference: "Arxiv"
year: 2023
bibkey: wang2023efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.11527"}
tags: ['Attention Mechanism', 'BERT', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Tools', 'Training Techniques', 'Transformer']
---
Although deep pre45;trained language models have shown promising benefit in a large set of industrial scenarios including Click45;Through45;Rate (CTR) prediction how to integrate pre45;trained language models that handle only textual signals into a prediction pipeline with non45;textual features is challenging. Up to now two directions have been explored to integrate multi45;modal inputs in fine45;tuning of pre45;trained language models. One consists of fusing the outcome of language models and non45;textual features through an aggregation layer resulting into ensemble framework where the cross45;information between textual and non45;textual inputs are only learned in the aggregation layer. The second one consists of splitting non45;textual features into fine45;grained fragments and transforming the fragments to new tokens combined with textual ones so that they can be fed directly to transformer layers in language models. However this approach increases the complexity of the learning and inference because of the numerous additional tokens. To address these limitations we propose in this work a novel framework BERT4CTR with the Uni45;Attention mechanism that can benefit from the interactions between non45;textual and textual features while maintaining low time45;costs in training and inference through a dimensionality reduction. Comprehensive experiments on both public and commercial data demonstrate that BERT4CTR can outperform significantly the state45;of45;the45;art frameworks to handle multi45;modal inputs and be applicable to CTR prediction.
