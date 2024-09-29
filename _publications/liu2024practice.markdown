---
layout: publication
title: A Practice-Friendly Two-Stage LLM-Enhanced Paradigm in Sequential Recommendation
authors: Liu Dugang, Xian Shenxian, Lin Xiaolin, Zhang Xiaolian, Zhu Hong, Fang Yuan, Chen Zhen, Ming Zhong
conference: "Arxiv"
year: 2024
bibkey: liu2024practice
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.00333"}
tags: ['Applications', 'Efficiency And Optimization', 'Fine Tuning', 'Pretraining Methods', 'Tools', 'Training Techniques']
---
The training paradigm integrating large language models (LLM) is gradually reshaping sequential recommender systems (SRS) and has shown promising results. However most existing LLM-enhanced methods rely on rich textual information on the item side and instance-level supervised fine-tuning (SFT) to inject collaborative information into LLM which is inefficient and limited in many applications. To alleviate these problems this paper proposes a novel practice-friendly two-stage LLM-enhanced paradigm (TSLRec) for SRS. Specifically in the information reconstruction stage we design a new user-level SFT task for collaborative information injection with the assistance of a pre-trained SRS model which is more efficient and compatible with limited text information. We aim to let LLM try to infer the latent category of each item and reconstruct the corresponding users preference distribution for all categories from the users interaction sequence. In the information augmentation stage we feed each item into LLM to obtain a set of enhanced embeddings that combine collaborative information and LLM inference capabilities. These embeddings can then be used to help train various future SRS models. Finally we verify the effectiveness and efficiency of our TSLRec on three SRS benchmark datasets.
