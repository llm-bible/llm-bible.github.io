---
layout: publication
title: 'Tuning Language Models As Training Data Generators For Augmentation-enhanced Few-shot Learning'
authors: Meng Yu, Michalski Martin, Huang Jiaxin, Zhang Yu, Abdelzaher Tarek, Han Jiawei
conference: "Arxiv"
year: 2022
bibkey: meng2022tuning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2211.03044"}
tags: ['Few Shot', 'GPT', 'Pretraining Methods', 'Prompting', 'RAG', 'Training Techniques']
---
'Recent studies have revealed the intriguing few-shot learning ability of pretrained language models (PLMs): They can quickly adapt to a new task when fine-tuned on a small amount of labeled data formulated as prompts, without requiring abundant task-specific annotations. Despite their promising performance, most existing few-shot approaches that only learn from the small training set still underperform fully supervised training by nontrivial margins. In this work, we study few-shot learning with PLMs from a different perspective: We first tune an autoregressive PLM on the few-shot samples and then use it as a generator to synthesize a large amount of novel training samples which augment the original training set. To encourage the generator to produce label-discriminative samples, we train it via weighted maximum likelihood where the weight of each token is automatically adjusted based on a discriminative meta-learning objective. A classification PLM can then be fine-tuned on both the few-shot and the synthetic samples with regularization for better generalization and stability. Our approach FewGen achieves an overall better result across seven classification tasks of the GLUE benchmark than existing few-shot learning methods, improving no-augmentation methods by 5+ average points, and outperforming augmentation methods by 3+ average points.'
