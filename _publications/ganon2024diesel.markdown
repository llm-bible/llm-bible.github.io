---
layout: publication
title: 'DIESEL -- Dynamic Inference-guidance Via Evasion Of Semantic Embeddings In Llms'
authors: Ben Ganon, Alon Zolfi, Omer Hofman, Inderjeet Singh, Hisashi Kojima, Yuval Elovici, Asaf Shabtai
conference: "Arxiv"
year: 2024
bibkey: ganon2024diesel
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.19038'}
tags: ['Security', 'Training Techniques', 'Applications', 'GPT', 'Responsible AI', 'Pretraining Methods']
---
In recent years, large language models (LLMs) have had great success in tasks
such as casual conversation, contributing to significant advancements in
domains like virtual assistance. However, they often generate responses that
are not aligned with human values (e.g., ethical standards, safety), leading to
potentially unsafe or inappropriate outputs. While several techniques have been
proposed to address this problem, they come with a cost, requiring
computationally expensive training or dramatically increasing the inference
time. In this paper, we present DIESEL, a lightweight inference-guidance
technique that can be seamlessly integrated into any autoregressive LLM to
semantically filter undesired concepts from the response. DIESEL can function
either as a standalone safeguard or as an additional layer of defense,
enhancing response safety by reranking the LLM's proposed tokens based on their
similarity to predefined negative concepts in the latent space. Our evaluation
demonstrates DIESEL's effectiveness on state-of-the-art conversational models,
even in adversarial jailbreaking scenarios that challenge response safety. We
also highlight DIESEL's generalization capabilities, showing that it can be
used in use cases other than safety, providing general-purpose response
filtering.
