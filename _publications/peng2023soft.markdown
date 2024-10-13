---
layout: publication
title: 'Soft Prompt Tuning For Augmenting Dense Retrieval With Large Language Models'
authors: Peng Zhiyuan, Wu Xuyang, Wang Qifan, Fang Yi
conference: "Arxiv"
year: 2023
bibkey: peng2023soft
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.08303"}
tags: ['Few Shot', 'Fine Tuning', 'Prompting', 'RAG', 'Training Techniques']
---
Dense retrieval (DR) converts queries and documents into dense embeddings and
measures the similarity between queries and documents in vector space. One of
the challenges in DR is the lack of domain-specific training data. While DR
models can learn from large-scale public datasets like MS MARCO through
transfer learning, evidence shows that not all DR models and domains can
benefit from transfer learning equally. Recently, some researchers have
resorted to large language models (LLMs) to improve the zero-shot and few-shot
DR models. However, the hard prompts or human-written prompts utilized in these
works cannot guarantee the good quality of generated weak queries. To tackle
this, we propose soft prompt tuning for augmenting DR (SPTAR): For each task,
we leverage soft prompt-tuning to optimize a task-specific soft prompt on
limited ground truth data and then prompt the LLMs to tag unlabeled documents
with weak queries, yielding enough weak document-query pairs to train
task-specific dense retrievers. We design a filter to select high-quality
example document-query pairs in the prompt to further improve the quality of
weak tagged queries. To the best of our knowledge, there is no prior work
utilizing soft prompt tuning to augment DR models. The experiments demonstrate
that SPTAR outperforms the unsupervised baselines BM25 and the recently
proposed LLMs-based augmentation method for DR.
