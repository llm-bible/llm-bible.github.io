---
layout: publication
title: Triplenet&#58; Triple Attention Network For Multi-turn Response Selection In Retrieval-based Chatbots
authors: Ma Wentao, Cui Yiming, Shao Nan, He Su, Zhang Wei-nan, Liu Ting, Wang Shijin, Hu Guoping
conference: "CoNLL"
year: 2019
bibkey: ma2019triple
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1909.10666"}
  - {name: "Code", url: "https://github.com/wtma/TripleNet"}
tags: ['Attention Mechanism', 'Has Code', 'Model Architecture', 'Transformer']
---
We consider the importance of different utterances in the context for selecting the response usually depends on the current query. In this paper we propose the model TripleNet to fully model the task with the triple <context query response instead of <context response in previous works. The heart of TripleNet is a novel attention mechanism named triple attention to model the relationships within the triple at four levels. The new mechanism updates the representation for each element based on the attention with the other two concurrently and symmetrically. We match the triple <C Q R centered on the response from char to context level for prediction. Experimental results on two large-scale multi-turn response selection datasets show that the proposed model can significantly outperform the state-of-the-art methods. TripleNet source code is available at https://github.com/wtma/TripleNet"
