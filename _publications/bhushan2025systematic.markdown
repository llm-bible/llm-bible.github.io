---
layout: publication
title: 'Systematic Knowledge Injection Into Large Language Models Via Diverse Augmentation For Domain-specific RAG'
authors: Kushagra Bhushan, Yatin Nandwani, Dinesh Khandelwal, Sonam Gupta, Gaurav Pandey, Dinesh Raghu, Sachindra Joshi
conference: "Arxiv"
year: 2025
bibkey: bhushan2025systematic
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.08356'}
tags: ['RAG', 'Training Techniques', 'Tools', 'Fine-Tuning', 'Pretraining Methods']
---
Retrieval-Augmented Generation (RAG) has emerged as a prominent method for
incorporating domain knowledge into Large Language Models (LLMs). While RAG
enhances response relevance by incorporating retrieved domain knowledge in the
context, retrieval errors can still lead to hallucinations and incorrect
answers. To recover from retriever failures, domain knowledge is injected by
fine-tuning the model to generate the correct response, even in the case of
retrieval errors. However, we observe that without systematic knowledge
augmentation, fine-tuned LLMs may memorize new information but still fail to
extract relevant domain knowledge, leading to poor performance. In this work,
we present a novel framework that significantly enhances the fine-tuning
process by augmenting the training data in two ways -- context augmentation and
knowledge paraphrasing. In context augmentation, we create multiple training
samples for a given QA pair by varying the relevance of the retrieved
information, teaching the model when to ignore and when to rely on retrieved
content. In knowledge paraphrasing, we fine-tune with multiple answers to the
same question, enabling LLMs to better internalize specialized knowledge. To
mitigate catastrophic forgetting due to fine-tuning, we add a domain-specific
identifier to a question and also utilize a replay buffer containing general QA
pairs. Experimental results demonstrate the efficacy of our method over
existing techniques, achieving up to 10% relative gain in token-level recall
while preserving the LLM's generalization capabilities.
