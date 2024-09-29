---
layout: publication
title: CO3: Low-resource Contrastive Co-training For Generative Conversational Query Rewrite
authors: Yuan Yifei, Shi Chen, Wang Runze, Chen Liyi, Hu Renjun, Zhang Zengming, Jiang Feijun, Lam Wai
conference: "Arxiv"
year: 2024
bibkey: yuan2024low
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.11873"}
tags: ['Attention Mechanism', 'Few Shot', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
Generative query rewrite generates reconstructed query rewrites using the conversation history while rely heavily on gold rewrite pairs that are expensive to obtain. Recently few-shot learning is gaining increasing popularity for this task whereas these methods are sensitive to the inherent noise due to limited data size. Besides both attempts face performance degradation when there exists language style shift between training and testing cases. To this end we study low-resource generative conversational query rewrite that is robust to both noise and language style shift. The core idea is to utilize massive unlabeled data to make further improvements via a contrastive co-training paradigm. Specifically we co-train two dual models (namely Rewriter and Simplifier) such that each of them provides extra guidance through pseudo-labeling for enhancing the other in an iterative manner. We also leverage contrastive learning with data augmentation which enables our model pay more attention on the truly valuable information than the noise. Extensive experiments demonstrate the superiority of our model under both few-shot and zero-shot scenarios. We also verify the better generalization ability of our model when encountering language style shift.
