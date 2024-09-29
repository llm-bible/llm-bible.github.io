---
layout: publication
title: Retrieval45;augmented Code Completion For Local Projects Using Large Language Models
authors: Hostnik Marko, Robnik-šikonja Marko
conference: "Arxiv"
year: 2024
bibkey: hostnik2024retrieval
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.05026"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Tokenization', 'Transformer']
---
The use of large language models (LLMs) is becoming increasingly widespread among software developers. However privacy and computational requirements are problematic with commercial solutions and the use of LLMs. In this work we focus on using LLMs with around 160 million parameters that are suitable for local execution and augmentation with retrieval from local projects. We train two models based on the transformer architecture the generative model GPT45;2 and the retrieval45;adapted RETRO model on open45;source Python files and empirically evaluate and compare them confirming the benefits of vector embedding based retrieval. Further we improve our models performance with In45;context retrieval45;augmented generation which retrieves code snippets based on the Jaccard similarity of tokens. We evaluate In45;context retrieval45;augmented generation on larger models and conclude that despite its simplicity the approach is more suitable than using the RETRO architecture. We highlight the key role of proper tokenization in achieving the full potential of LLMs in code completion.
