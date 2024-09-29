---
layout: publication
title: LM45;CPPF Paraphrasing45;guided Data Augmentation For Contrastive Prompt45;based Few45;shot Fine45;tuning
authors: Abaskohi Amirhossein, Rothe Sascha, Yaghoobzadeh Yadollah
conference: "https://aclanthology.org/"
year: 2023
bibkey: abaskohi2023lm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.18169"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG']
---
In recent years there has been significant progress in developing pre45;trained language models for NLP. However these models often struggle when fine45;tuned on small datasets. To address this issue researchers have proposed various adaptation approaches. Prompt45;based tuning is arguably the most common way especially for larger models. Previous research shows that adding contrastive learning to prompt45;based fine45;tuning is effective as it helps the model generate embeddings that are more distinguishable between classes and it can also be more sample45;efficient as the model learns from positive and negative examples simultaneously. One of the most important components of contrastive learning is data augmentation but unlike computer vision effective data augmentation for NLP is still challenging. This paper proposes LM45;CPPF Contrastive Paraphrasing45;guided Prompt45;based Fine45;tuning of Language Models which leverages prompt45;based few45;shot paraphrasing using generative language models especially large language models such as GPT45;3 and OPT45;175B for data augmentation. Our experiments on multiple text classification benchmarks show that this augmentation method outperforms other methods such as easy data augmentation back translation and multiple templates.
