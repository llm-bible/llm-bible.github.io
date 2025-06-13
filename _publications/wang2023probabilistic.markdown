---
layout: publication
title: 'Probabilistic Linguistic Knowledge And Token-level Text Augmentation'
authors: Zhengxiang Wang
conference: "Arxiv"
year: 2023
bibkey: wang2023probabilistic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.16644"}
tags: ['Model Architecture', 'RAG', 'Transformer', 'Pretraining Methods']
---
This paper investigates the effectiveness of token-level text augmentation
and the role of probabilistic linguistic knowledge within a
linguistically-motivated evaluation context. Two text augmentation programs,
REDA and REDA\\(_\{NG\}\\), were developed, both implementing five token-level text
editing operations: Synonym Replacement (SR), Random Swap (RS), Random
Insertion (RI), Random Deletion (RD), and Random Mix (RM). REDA\\(_\{NG\}\\)
leverages pretrained \\(n\\)-gram language models to select the most likely
augmented texts from REDA's output. Comprehensive and fine-grained experiments
were conducted on a binary question matching classification task in both
Chinese and English. The results strongly refute the general effectiveness of
the five token-level text augmentation techniques under investigation, whether
applied together or separately, and irrespective of various common
classification model types used, including transformers. Furthermore, the role
of probabilistic linguistic knowledge is found to be minimal.
