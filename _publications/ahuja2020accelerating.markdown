---
layout: publication
title: Accelerating Natural Language Understanding In Task45;oriented Dialog
authors: Ahuja Ojas, Desai Shrey
conference: "Arxiv"
year: 2020
bibkey: ahuja2020accelerating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2006.03701"}
tags: ['Applications', 'BERT', 'Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Pruning', 'RAG', 'Reinforcement Learning', 'Transformer']
---
Task45;oriented dialog models typically leverage complex neural architectures and large45;scale pre45;trained Transformers to achieve state45;of45;the45;art performance on popular natural language understanding benchmarks. However these models frequently have in excess of tens of millions of parameters making them impossible to deploy on45;device where resource45;efficiency is a major concern. In this work we show that a simple convolutional model compressed with structured pruning achieves largely comparable results to BERT on ATIS and Snips with under 100K parameters. Moreover we perform acceleration experiments on CPUs where we observe our multi45;task model predicts intents and slots nearly 63x faster than even DistilBERT.
