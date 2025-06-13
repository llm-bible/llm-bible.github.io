---
layout: publication
title: 'A Practice-friendly Llm-enhanced Paradigm With Preference Parsing For Sequential Recommendation'
authors: Dugang Liu, Shenxian Xian, Xiaolin Lin, Xiaolian Zhang, Hong Zhu, Yuan Fang, Zhen Chen, Zhong Ming
conference: "Arxiv"
year: 2024
bibkey: liu2024practice
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.00333'}
tags: ['LREC', 'Efficiency and Optimization', 'Applications', 'Training Techniques', 'Tools', 'Fine-Tuning', 'RecSys', 'Pretraining Methods']
---
The training paradigm integrating large language models (LLM) is gradually
reshaping sequential recommender systems (SRS) and has shown promising results.
However, most existing LLM-enhanced methods rely on rich textual information on
the item side and instance-level supervised fine-tuning (SFT) to inject
collaborative information into LLM, which is inefficient and limited in many
applications. To alleviate these problems, this paper proposes a
practice-friendly LLM-enhanced paradigm with preference parsing (P2Rec) for
SRS. Specifically, in the information reconstruction stage, we design a new
user-level SFT task for collaborative information injection with the assistance
of a pre-trained SRS model, which is more efficient and compatible with limited
text information. Our goal is to let LLM learn to reconstruct a corresponding
prior preference distribution from each user's interaction sequence, where LLM
needs to effectively parse the latent category of each item and the
relationship between different items to accomplish this task. In the
information augmentation stage, we feed each item into LLM to obtain a set of
enhanced embeddings that combine collaborative information and LLM inference
capabilities. These embeddings can then be used to help train various future
SRS models. Finally, we verify the effectiveness and efficiency of our TSLRec
on three SRS benchmark datasets.
