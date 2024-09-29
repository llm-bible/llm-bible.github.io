---
layout: publication
title: Language Models With Transformers
authors: Wang Chenguang, Li Mu, Smola Alexander J.
conference: "Arxiv"
year: 2019
bibkey: wang2019language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1904.09408"}
tags: ['Attention Mechanism', 'BERT', 'Efficiency And Optimization', 'GPT', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Transformer']
---
The Transformer architecture is superior to RNN45;based models in computational efficiency. Recently GPT and BERT demonstrate the efficacy of Transformer models on various NLP tasks using pre45;trained language models on large45;scale corpora. Surprisingly these Transformer architectures are suboptimal for language model itself. Neither self45;attention nor the positional encoding in the Transformer is able to efficiently incorporate the word45;level sequential context crucial to language modeling. In this paper we explore effective Transformer architectures for language model including adding additional LSTM layers to better capture the sequential context while still keeping the computation efficient. We propose Coordinate Architecture Search (CAS) to find an effective architecture through iterative refinement of the model. Experimental results on the PTB WikiText45;2 and WikiText45;103 show that CAS achieves perplexities between 20.42 and 34.11 on all problems i.e. on average an improvement of 12.0 perplexity units compared to state45;of45;the45;art LSTMs. The source code is publicly available.
