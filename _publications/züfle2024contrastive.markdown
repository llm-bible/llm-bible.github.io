---
layout: publication
title: 'Contrastive Learning For Task-independent Speechllm-pretraining'
authors: Maike Züfle, Jan Niehues
conference: "Arxiv"
year: 2024
bibkey: züfle2024contrastive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.15712"}
tags: ['Pretraining Methods', 'Training Techniques', 'Applications', 'Fine-Tuning']
---
Large language models (LLMs) excel in natural language processing but adapting these LLMs to speech processing tasks efficiently is not straightforward. Direct task-specific fine-tuning is limited by overfitting risks, data requirements, and computational costs. To address these challenges, we propose a scalable, two-stage training approach: (1) A task-independent speech pretraining stage using contrastive learning to align text and speech representations over all layers, followed by (2) a task-specific fine-tuning stage requiring minimal data. This approach outperforms traditional ASR pretraining and enables the model to surpass models specialized on speech translation and question answering while being trained on only 10% of the task-specific data.
