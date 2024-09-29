---
layout: publication
title: Large Language Models Are Competitive Near Cold45;start Recommenders For Language45; And Item45;based Preferences
authors: Sanner Scott, Balog Krisztian, Radlinski Filip, Wedin Ben, Dixon Lucas
conference: "Arxiv"
year: 2023
bibkey: sanner2023large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.14225"}
tags: ['Ethics And Bias', 'Prompting', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Traditional recommender systems leverage users item preference history to recommend novel content that users may like. However modern dialog interfaces that allow users to express language45;based preferences offer a fundamentally different modality for preference input. Inspired by recent successes of prompting paradigms for large language models (LLMs) we study their use for making recommendations from both item45;based and language45;based preferences in comparison to state45;of45;the45;art item45;based collaborative filtering (CF) methods. To support this investigation we collect a new dataset consisting of both item45;based and language45;based preferences elicited from users along with their ratings on a variety of (biased) recommended items and (unbiased) random items. Among numerous experimental results we find that LLMs provide competitive recommendation performance for pure language45;based preferences (no item preferences) in the near cold45;start case in comparison to item45;based CF methods despite having no supervised training for this specific task (zero45;shot) or only a few labels (few45;shot). This is particularly promising as language45;based preference representations are more explainable and scrutable than item45;based or vector45;based representations.
