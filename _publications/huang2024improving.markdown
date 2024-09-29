---
layout: publication
title: Improving Llms For Recommendation With Out45;of45;vocabulary Tokens
authors: Huang Ting-ji, Yang Jia-qi, Shen Chunxu, Liu Kai-qi, Zhan De-chuan, Ye Han-jia
conference: "Arxiv"
year: 2024
bibkey: huang2024improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.08477"}
tags: ['Pretraining Methods', 'Tools']
---
Characterizing users and items through vector representations is crucial for various tasks in recommender systems. Recent approaches attempt to apply Large Language Models (LLMs) in recommendation through a question and answer format where real users and items (e.g. Item No.2024) are represented with in45;vocabulary tokens (e.g. item 20 24). However since LLMs are typically pretrained on natural language tasks these in45;vocabulary tokens lack the expressive power for distinctive users and items thereby weakening the recommendation ability even after fine45;tuning on recommendation tasks. In this paper we explore how to effectively tokenize users and items in LLM45;based recommender systems. We emphasize the role of out45;of45;vocabulary (OOV) tokens in addition to the in45;vocabulary ones and claim the memorization of OOV tokens that capture correlations of users/items as well as diversity of OOV tokens. By clustering the learned representations from historical user45;item interactions we make the representations of user/item combinations share the same OOV tokens if they have similar properties. Furthermore integrating these OOV tokens into the LLMs vocabulary allows for better distinction between users and items and enhanced capture of user45;item relationships during fine45;tuning on downstream tasks. Our proposed framework outperforms existing state45;of45;the45;art methods across various downstream recommendation tasks.
