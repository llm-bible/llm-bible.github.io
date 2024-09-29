---
layout: publication
title: 'LM-CPPF: Paraphrasing-guided Data Augmentation For Contrastive Prompt-based Few-shot Fine-tuning'
authors: Abaskohi Amirhossein, Rothe Sascha, Yaghoobzadeh Yadollah
conference: "https://aclanthology.org/"
year: 2023
bibkey: abaskohi2023lm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.18169"}
tags: ['Few Shot', 'Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Training Techniques']
---
In recent years there has been significant progress in developing pre-trained language models for NLP. However these models often struggle when fine-tuned on small datasets. To address this issue researchers have proposed various adaptation approaches. Prompt-based tuning is arguably the most common way especially for larger models. Previous research shows that adding contrastive learning to prompt-based fine-tuning is effective as it helps the model generate embeddings that are more distinguishable between classes and it can also be more sample-efficient as the model learns from positive and negative examples simultaneously. One of the most important components of contrastive learning is data augmentation but unlike computer vision effective data augmentation for NLP is still challenging. This paper proposes LM-CPPF Contrastive Paraphrasing-guided Prompt-based Fine-tuning of Language Models which leverages prompt-based few-shot paraphrasing using generative language models especially large language models such as GPT-3 and OPT-175B for data augmentation. Our experiments on multiple text classification benchmarks show that this augmentation method outperforms other methods such as easy data augmentation back translation and multiple templates.
