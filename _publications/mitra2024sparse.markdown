---
layout: publication
title: 'Sparse Attention Vectors: Generative Multimodal Model Features Are Discriminative Vision-language Classifiers'
authors: Chancharik Mitra, Brandon Huang, Tianning Chai, Zhiqiu Lin, Assaf Arbelle, Rogerio Feris, Leonid Karlinsky, Trevor Darrell, Deva Ramanan, Roei Herzig
conference: "Arxiv"
year: 2024
bibkey: mitra2024sparse
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.00142"}
tags: ['Applications', 'RAG', 'Model Architecture', 'Attention Mechanism', 'Few-Shot', 'Multimodal Models']
---
Generative Large Multimodal Models (LMMs) like LLaVA and Qwen-VL excel at a
wide variety of vision-language (VL) tasks such as image captioning or visual
question answering. Despite strong performance, LMMs are not directly suited
for foundational discriminative vision-language tasks (i.e., tasks requiring
discrete label predictions) such as image classification and multiple-choice
VQA. One key challenge in utilizing LMMs for discriminative tasks is the
extraction of useful features from generative models. To overcome this issue,
we propose an approach for finding features in the model's latent space to more
effectively leverage LMMs for discriminative tasks. Toward this end, we present
Sparse Attention Vectors (SAVs) -- a finetuning-free method that leverages
sparse attention head activations (fewer than 1% of the heads) in LMMs as
strong features for VL tasks. With only few-shot examples, SAVs demonstrate
state-of-the-art performance compared to a variety of few-shot and finetuned
baselines on a collection of discriminative tasks. Our experiments also imply
that SAVs can scale in performance with additional examples and generalize to
similar tasks, establishing SAVs as both effective and robust multimodal
feature representations.
