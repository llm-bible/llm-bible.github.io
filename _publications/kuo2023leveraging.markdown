---
layout: publication
title: DACBERT Leveraging Dependency Agreement For Cost45;efficient Bert Pretraining
authors: Kuo Martin, Zhang Jianyi, Chen Yiran
conference: "Arxiv"
year: 2023
bibkey: kuo2023leveraging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.04799"}
tags: ['Applications', 'BERT', 'Interpretability And Explainability', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Tools', 'Training Techniques']
---
Building on the cost45;efficient pretraining advancements brought about by Crammed BERT we enhance its performance and interpretability further by introducing a novel pretrained model Dependency Agreement Crammed BERT (DACBERT) and its two45;stage pretraining framework 45; Dependency Agreement Pretraining. This framework grounded by linguistic theories seamlessly weaves syntax and semantic information into the pretraining process. The first stage employs four dedicated submodels to capture representative dependency agreements at the chunk level effectively converting these agreements into embeddings. The second stage uses these refined embeddings in tandem with conventional BERT embeddings to guide the pretraining of the rest of the model. Evaluated on the GLUE benchmark our DACBERT demonstrates notable improvement across various tasks surpassing Crammed BERT by 3.1337; in the RTE task and by 2.2637; in the MRPC task. Furthermore our method boosts the average GLUE score by 0.8337; underscoring its significant potential. The pretraining process can be efficiently executed on a single GPU within a 2445;hour cycle necessitating no supplementary computational resources or extending the pretraining duration compared with the Crammed BERT. Extensive studies further illuminate our approachs instrumental role in bolstering the interpretability of pretrained language models for natural language understanding tasks.
