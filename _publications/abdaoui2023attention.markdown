---
layout: publication
title: Attention Over Pre45;trained Sentence Embeddings For Long Document Classification
authors: Abdaoui Amine, Dutta Sourav
conference: "Arxiv"
year: 2023
bibkey: abdaoui2023attention
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.09084"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Transformer']
---
Despite being the current de45;facto models in most NLP tasks transformers are often limited to short sequences due to their quadratic attention complexity on the number of tokens. Several attempts to address this issue were studied either by reducing the cost of the self45;attention computation or by modeling smaller sequences and combining them through a recurrence mechanism or using a new transformer model. In this paper we suggest to take advantage of pre45;trained sentence transformers to start from semantically meaningful embeddings of the individual sentences and then combine them through a small attention layer that scales linearly with the document length. We report the results obtained by this simple architecture on three standard document classification datasets. When compared with the current state45;of45;the45;art models using standard fine45;tuning the studied method obtains competitive results (even if there is no clear best model in this configuration). We also showcase that the studied architecture obtains better results when freezing the underlying transformers. A configuration that is useful when we need to avoid complete fine45;tuning (e.g. when the same frozen transformer is shared by different applications). Finally two additional experiments are provided to further evaluate the relevancy of the studied architecture over simpler baselines.
