---
layout: publication
title: Distantly Supervised Transformers For E-commerce Product QA
authors: Mittal Happy, Chakrabarti Aniket, Bayar Belhassen, Sharma Animesh Anant, Rasiwasia Nikhil
conference: "Arxiv"
year: 2021
bibkey: mittal2021distantly
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2104.02947"}
tags: ['Applications', 'Model Architecture', 'Pretraining Methods', 'Tools', 'Training Techniques', 'Transformer']
---
We propose a practical instant question answering (QA) system on product pages of ecommerce services where for each user query relevant community question answer (CQA) pairs are retrieved. User queries and CQA pairs differ significantly in language characteristics making relevance learning difficult. Our proposed transformer-based model learns a robust relevance function by jointly learning unified syntactic and semantic representations without the need for human labeled data. This is achieved by distantly supervising our model by distilling from predictions of a syntactic matching system on user queries and simultaneously training with CQA pairs. Training with CQA pairs helps our model learning semantic QA relevance and distant supervision enables learning of syntactic features as well as the nuances of user querying language. Additionally our model encodes queries and candidate responses independently allowing offline candidate embedding generation thereby minimizing the need for real-time transformer model execution. Consequently our framework is able to scale to large e-commerce QA traffic. Extensive evaluation on user queries shows that our framework significantly outperforms both syntactic and semantic baselines in offline as well as large scale online A/B setups of a popular e-commerce service.
