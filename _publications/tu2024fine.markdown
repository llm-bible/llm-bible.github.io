---
layout: publication
title: 'Resofilter: Fine-grained Synthetic Data Filtering For Large Language Models Through Data-parameter Resonance Analysis'
authors: Zeao Tu, Xiangdi Meng, Yu He, Zihan Yao, Tianyu Qi, Jun Liu, Ming Li
conference: "Arxiv"
year: 2024
bibkey: tu2024fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.14809"}
tags: ['Training Techniques', 'Model Architecture', 'RAG', 'GPT', 'Pretraining Methods', 'Fine-Tuning', 'Interpretability and Explainability']
---
Large language models (LLMs) have shown remarkable effectiveness across
various domains, with data augmentation methods utilizing GPT for synthetic
data generation becoming prevalent. However, the quality and utility of
augmented data remain questionable, and current methods lack clear metrics for
evaluating data characteristics. To address these challenges, we propose
ResoFilter, a novel method that integrates models, data, and tasks to refine
datasets. ResoFilter leverages the fine-tuning process to obtain Data-Parameter
features for data selection, offering improved interpretability by representing
data characteristics through model weights. Our experiments demonstrate that
ResoFilter achieves comparable results to full-scale fine-tuning using only
half the data in mathematical tasks and exhibits strong generalization across
different models and domains. This method provides valuable insights for
constructing synthetic datasets and evaluating high-quality data, offering a
promising solution for enhancing data augmentation techniques and improving
training dataset quality for LLMs. For reproducibility, we will release our
code and data upon acceptance.
