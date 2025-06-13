---
layout: publication
title: 'Training Plug-n-play Knowledge Modules With Deep Context Distillation'
authors: Lucas Caccia, Alan Ansell, Edoardo Ponti, Ivan Vulić, Alessandro Sordoni
conference: "Arxiv"
year: 2025
bibkey: caccia2025training
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.08727"}
tags: ['Fine-Tuning', 'Pre-Training', 'Efficiency and Optimization', 'Tools', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Distillation']
---
Dynamically integrating new or rapidly evolving information after (Large)
Language Model pre-training remains challenging, particularly in low-data
scenarios or when dealing with private and specialized documents. In-context
learning and retrieval-augmented generation (RAG) face limitations, including
their high inference costs and their inability to capture global document
information. In this paper, we propose a way of modularizing knowledge by
training document-level Knowledge Modules (KMs). KMs are lightweight components
implemented as parameter-efficient LoRA modules, which are trained to store
information about new documents and can be easily plugged into models on
demand. We show that next-token prediction performs poorly as the training
objective for KMs. We instead propose Deep Context Distillation: we learn KMs
parameters such as to simulate hidden states and logits of a teacher that takes
the document in context. Our method outperforms standard next-token prediction
and pre-instruction training techniques, across two datasets. Finally, we
highlight synergies between KMs and RAG.
