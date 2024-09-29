---
layout: publication
title: On The Role Of Attention In Prompt45;tuning
authors: Oymak Samet, Rawat Ankit Singh, Soltanolkotabi Mahdi, Thrampoulidis Christos
conference: "Arxiv"
year: 2023
bibkey: oymak2023role
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.03435"}
tags: ['Attention Mechanism', 'Merging', 'Model Architecture', 'Prompting', 'Training Techniques', 'Transformer']
---
Prompt45;tuning is an emerging strategy to adapt large language models (LLM) to downstream tasks by learning a (soft45;)prompt parameter from data. Despite its success in LLMs there is limited theoretical understanding of the power of prompt45;tuning and the role of the attention mechanism in prompting. In this work we explore prompt45;tuning for one45;layer attention architectures and study contextual mixture45;models where each input token belongs to a context45;relevant or 45;irrelevant set. We isolate the role of prompt45;tuning through a self45;contained prompt45;attention model. Our contributions are as follows (1) We show that softmax45;prompt45;attention is provably more expressive than softmax45;self45;attention and linear45;prompt45;attention under our contextual data model. (2) We analyze the initial trajectory of gradient descent and show that it learns the prompt and prediction head with near45;optimal sample complexity and demonstrate how prompt can provably attend to sparse context45;relevant tokens. (3) Assuming a known prompt but an unknown prediction head we characterize the exact finite sample performance of prompt45;attention which reveals the fundamental performance limits and the precise benefit of the context information. We also provide experiments that verify our theoretical insights on real datasets and demonstrate how prompt45;tuning enables the model to attend to context45;relevant information.
