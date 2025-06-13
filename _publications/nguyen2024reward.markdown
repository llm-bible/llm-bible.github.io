---
layout: publication
title: 'Reward-rag: Enhancing RAG With Reward Driven Supervision'
authors: Thang Nguyen, Peter Chin, Yu-wing Tai
conference: "Arxiv"
year: 2024
bibkey: nguyen2024reward
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.03780"}
tags: ['Fine-Tuning', 'GPT', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
In this paper, we introduce Reward-RAG, a novel approach designed to enhance
the Retrieval-Augmented Generation (RAG) model through Reward-Driven
Supervision. Unlike previous RAG methodologies, which focus on training
language models (LMs) to utilize external knowledge retrieved from external
sources, our method adapts retrieval information to specific domains by
employing CriticGPT to train a dedicated reward model. This reward model
generates synthesized datasets for fine-tuning the RAG encoder, aligning its
outputs more closely with human preferences. The versatility of our approach
allows it to be effectively applied across various domains through
domain-specific fine-tuning. We evaluate Reward-RAG on publicly available
benchmarks from multiple domains, comparing it to state-of-the-art methods. Our
experimental results demonstrate significant improvements in performance,
highlighting the effectiveness of Reward-RAG in improving the relevance and
quality of generated responses. These findings underscore the potential of
integrating reward models with RAG to achieve superior outcomes in natural
language generation tasks.
