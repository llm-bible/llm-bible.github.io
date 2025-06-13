---
layout: publication
title: 'DACBERT: Leveraging Dependency Agreement For Cost-efficient Bert Pretraining'
authors: Martin Kuo, Jianyi Zhang, Yiran Chen
conference: "Arxiv"
year: 2023
bibkey: kuo2023leveraging
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2311.04799'}
tags: ['Interpretability and Explainability', 'RAG', 'Training Techniques', 'Model Architecture', 'Tools', 'BERT', 'Applications', 'Pretraining Methods']
---
Building on the cost-efficient pretraining advancements brought about by
Crammed BERT, we enhance its performance and interpretability further by
introducing a novel pretrained model Dependency Agreement Crammed BERT
(DACBERT) and its two-stage pretraining framework - Dependency Agreement
Pretraining. This framework, grounded by linguistic theories, seamlessly weaves
syntax and semantic information into the pretraining process. The first stage
employs four dedicated submodels to capture representative dependency
agreements at the chunk level, effectively converting these agreements into
embeddings. The second stage uses these refined embeddings, in tandem with
conventional BERT embeddings, to guide the pretraining of the rest of the
model. Evaluated on the GLUE benchmark, our DACBERT demonstrates notable
improvement across various tasks, surpassing Crammed BERT by 3.13% in the RTE
task and by 2.26% in the MRPC task. Furthermore, our method boosts the average
GLUE score by 0.83%, underscoring its significant potential. The pretraining
process can be efficiently executed on a single GPU within a 24-hour cycle,
necessitating no supplementary computational resources or extending the
pretraining duration compared with the Crammed BERT. Extensive studies further
illuminate our approach's instrumental role in bolstering the interpretability
of pretrained language models for natural language understanding tasks.
