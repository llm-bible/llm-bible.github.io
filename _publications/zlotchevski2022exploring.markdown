---
layout: publication
title: Exploring And Evaluating Personalized Models For Code Generation
authors: Zlotchevski Andrei, Drain Dawn, Svyatkovskiy Alexey, Clement Colin, Sundaresan Neel, Tufano Michele
conference: "Arxiv"
year: 2022
bibkey: zlotchevski2022exploring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2208.13928"}
tags: ['Applications', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Large Transformer models achieved the state45;of45;the45;art status for Natural Language Understanding tasks and are increasingly becoming the baseline model architecture for modeling source code. Transformers are usually pre45;trained on large unsupervised corpora learning token representations and transformations relevant to modeling generally available text and are then fine45;tuned on a particular downstream task of interest. While fine45;tuning is a tried45;and45;true method for adapting a model to a new domain 45;45; for example question45;answering on a given topic 45;45; generalization remains an on45;going challenge. In this paper we explore and evaluate transformer model fine45;tuning for personalization. In the context of generating unit tests for Java methods we evaluate learning to personalize to a specific software project using several personalization techniques. We consider three key approaches (i) custom fine45;tuning which allows all the model parameters to be tuned; (ii) lightweight fine45;tuning which freezes most of the models parameters allowing tuning of the token embeddings and softmax layer only or the final layer alone; (iii) prefix tuning which keeps model parameters frozen but optimizes a small project45;specific prefix vector. Each of these techniques offers a trade45;off in total compute cost and predictive performance which we evaluate by code and task45;specific metrics training time and total computational operations. We compare these fine45;tuning strategies for code generation and discuss the potential generalization and cost benefits of each in various deployment scenarios.
