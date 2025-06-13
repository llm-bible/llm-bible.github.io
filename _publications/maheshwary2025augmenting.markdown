---
layout: publication
title: 'Augmenting LLM Reasoning With Dynamic Notes Writing For Complex QA'
authors: Rishabh Maheshwary, Masoud Hashemi, Khyati Mahajan, Shiva Krishna Reddy Malay, Sai Rajeswar, Sathwik Tejaswi Madhusudhan, Spandana Gella, Vikas Yadav
conference: "Arxiv"
year: 2025
bibkey: maheshwary2025augmenting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.16293"}
tags: ['RAG', 'Applications', 'Tools']
---
Iterative RAG for multi-hop question answering faces challenges with lengthy contexts and the buildup of irrelevant information. This hinders a model's capacity to process and reason over retrieved content and limits performance. While recent methods focus on compressing retrieved information, they are either restricted to single-round RAG, require finetuning or lack scalability in iterative RAG. To address these challenges, we propose Notes Writing, a method that generates concise and relevant notes from retrieved documents at each step, thereby reducing noise and retaining only essential information. This indirectly increases the effective context length of Large Language Models (LLMs), enabling them to reason and plan more effectively while processing larger volumes of input text. Notes Writing is framework agnostic and can be integrated with different iterative RAG methods. We demonstrate its effectiveness with three iterative RAG methods, across two models and four evaluation datasets. Notes writing yields an average improvement of 15.6 percentage points overall, with minimal increase in output tokens.
