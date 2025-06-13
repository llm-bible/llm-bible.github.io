---
layout: publication
title: 'Personalized Text Generation With Contrastive Activation Steering'
authors: Jinghao Zhang, Yuting Liu, Wenjie Wang, Qiang Liu, Shu Wu, Liang Wang, Tat-seng Chua
conference: "Arxiv"
year: 2025
bibkey: zhang2025personalized
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.05213'}
tags: ['Language Modeling', 'RAG', 'Training Techniques', 'Applications', 'Tools', 'Fine-Tuning', 'Pretraining Methods']
---
Personalized text generation aims to infer users' writing style preferences
from their historical texts and generate outputs that faithfully reflect these
stylistic characteristics. Existing solutions primarily adopt two paradigms:
retrieval-augmented generation (RAG) and parameter-efficient fine-tuning
(PEFT). While these approaches have advanced the field, they suffer from two
critical limitations: (1) the entanglement of content semantics and stylistic
patterns in historical texts impedes accurate modeling of user-specific writing
preferences; and (2) scalability challenges arising from both RAG's inference
latency by retrieval operations and PEFT's parameter storage requirements for
per user model. To overcome these limitations, we propose StyleVector, a
training-free framework that disentangles and represents personalized writing
style as a vector in LLM's activation space, enabling style-steered generation
during inference without requiring costly retrieval or parameter storage.
Comprehensive experiments demonstrate that our framework achieves a significant
8% relative improvement in personalized generation while reducing storage
requirements by 1700 times over PEFT method.
