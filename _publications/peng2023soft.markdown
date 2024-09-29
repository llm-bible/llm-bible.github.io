---
layout: publication
title: Soft Prompt Tuning For Augmenting Dense Retrieval With Large Language Models
authors: Peng Zhiyuan, Wu Xuyang, Wang Qifan, Fang Yi
conference: "Arxiv"
year: 2023
bibkey: peng2023soft
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.08303"}
tags: ['Fine Tuning', 'Prompting', 'RAG', 'Training Techniques']
---
Dense retrieval (DR) converts queries and documents into dense embeddings and measures the similarity between queries and documents in vector space. One of the challenges in DR is the lack of domain45;specific training data. While DR models can learn from large45;scale public datasets like MS MARCO through transfer learning evidence shows that not all DR models and domains can benefit from transfer learning equally. Recently some researchers have resorted to large language models (LLMs) to improve the zero45;shot and few45;shot DR models. However the hard prompts or human45;written prompts utilized in these works cannot guarantee the good quality of generated weak queries. To tackle this we propose soft prompt tuning for augmenting DR (SPTAR) For each task we leverage soft prompt45;tuning to optimize a task45;specific soft prompt on limited ground truth data and then prompt the LLMs to tag unlabeled documents with weak queries yielding enough weak document45;query pairs to train task45;specific dense retrievers. We design a filter to select high45;quality example document45;query pairs in the prompt to further improve the quality of weak tagged queries. To the best of our knowledge there is no prior work utilizing soft prompt tuning to augment DR models. The experiments demonstrate that SPTAR outperforms the unsupervised baselines BM25 and the recently proposed LLMs45;based augmentation method for DR.
