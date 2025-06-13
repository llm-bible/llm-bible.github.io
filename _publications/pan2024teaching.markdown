---
layout: publication
title: 'Latentqa: Teaching Llms To Decode Activations Into Natural Language'
authors: Alexander Pan, Lijie Chen, Jacob Steinhardt
conference: "Arxiv"
year: 2024
bibkey: pan2024teaching
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.08686"}
tags: ['Prompting', 'Ethics and Bias', 'Applications', 'Interpretability and Explainability']
---
Interpretability methods seek to understand language model representations,
yet the outputs of most such methods -- circuits, vectors, scalars -- are not
immediately human-interpretable. In response, we introduce LatentQA, the task
of answering open-ended questions about model activations in natural language.
Towards solving LatentQA, we propose Latent Interpretation Tuning (LIT), which
finetunes a decoder LLM on a dataset of activations and associated
question-answer pairs, similar to how visual instruction tuning trains on
question-answer pairs associated with images. We use the decoder for diverse
reading applications, such as extracting relational knowledge from
representations or uncovering system prompts governing model behavior. Our
decoder also specifies a differentiable loss that we use to control models,
such as debiasing models on stereotyped sentences and controlling the sentiment
of generations. Finally, we extend LatentQA to reveal harmful model
capabilities, such as generating recipes for bioweapons and code for hacking.
