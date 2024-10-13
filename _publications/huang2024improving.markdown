---
layout: publication
title: 'Improving Llms For Recommendation With Out-of-vocabulary Tokens'
authors: Huang Ting-ji, Yang Jia-qi, Shen Chunxu, Liu Kai-qi, Zhan De-chuan, Ye Han-jia
conference: "Arxiv"
year: 2024
bibkey: huang2024improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.08477"}
tags: ['Fine Tuning', 'Pretraining Methods', 'Tools', 'Training Techniques']
---
Characterizing users and items through vector representations is crucial for
various tasks in recommender systems. Recent approaches attempt to apply Large
Language Models (LLMs) in recommendation through a question and answer format,
where real users and items (e.g., Item No.2024) are represented with
in-vocabulary tokens (e.g., "item", "20", "24"). However, since LLMs are
typically pretrained on natural language tasks, these in-vocabulary tokens lack
the expressive power for distinctive users and items, thereby weakening the
recommendation ability even after fine-tuning on recommendation tasks. In this
paper, we explore how to effectively tokenize users and items in LLM-based
recommender systems. We emphasize the role of out-of-vocabulary (OOV) tokens in
addition to the in-vocabulary ones and claim the memorization of OOV tokens
that capture correlations of users/items as well as diversity of OOV tokens. By
clustering the learned representations from historical user-item interactions,
we make the representations of user/item combinations share the same OOV tokens
if they have similar properties. Furthermore, integrating these OOV tokens into
the LLM's vocabulary allows for better distinction between users and items and
enhanced capture of user-item relationships during fine-tuning on downstream
tasks. Our proposed framework outperforms existing state-of-the-art methods
across various downstream recommendation tasks.
