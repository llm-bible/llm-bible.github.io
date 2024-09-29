---
layout: publication
title: M645;rec Generative Pretrained Language Models Are Open45;ended Recommender Systems
authors: Cui Zeyu, Ma Jianxin, Zhou Chang, Zhou Jingren, Yang Hongxia
conference: "Arxiv"
year: 2022
bibkey: cui2022generative
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2205.08084"}
tags: ['Efficiency And Optimization', 'GPT', 'Interpretability And Explainability', 'Model Architecture', 'Prompting', 'Pruning', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Industrial recommender systems have been growing increasingly complex may involve emph123;diverse domains125; such as e45;commerce products and user45;generated contents and can comprise emph123;a myriad of tasks125; such as retrieval ranking explanation generation and even AI45;assisted content production. The mainstream approach so far is to develop individual algorithms for each domain and each task. In this paper we explore the possibility of developing a unified foundation model to support emph123;open45;ended domains and tasks125; in an industrial recommender system which may reduce the demand on downstream settings data and can minimize the carbon footprint by avoiding training a separate model from scratch for every task. Deriving a unified foundation is challenging due to (i) the potentially unlimited set of downstream domains and tasks and (ii) the real45;world systems emphasis on computational efficiency. We thus build our foundation upon M6 an existing large45;scale industrial pretrained language model similar to GPT45;3 and T5 and leverage M6s pretrained ability for sample45;efficient downstream adaptation by representing user behavior data as plain texts and converting the tasks to either language understanding or generation. To deal with a tight hardware budget we propose an improved version of prompt tuning that outperforms fine45;tuning with negligible 137; task45;specific parameters and employ techniques such as late interaction early exiting parameter sharing and pruning to further reduce the inference time and the model size. We demonstrate the foundation models versatility on a wide range of tasks such as retrieval ranking zero45;shot recommendation explanation generation personalized content creation and conversational recommendation and manage to deploy it on both cloud servers and mobile devices.
