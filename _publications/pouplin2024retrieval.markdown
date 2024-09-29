---
layout: publication
title: Retrieval Augmented Thought Process For Private Data Handling In Healthcare
authors: Pouplin Thomas, Sun Hao, Holt Samuel, Van Der Schaar Mihaela
conference: "Arxiv"
year: 2024
bibkey: pouplin2024retrieval
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.07812"}
tags: ['Applications', 'RAG', 'Reinforcement Learning', 'Security', 'Training Techniques']
---
Large Language Models (LLMs) have demonstrated the strong potential to assist both clinicians and the general public with their extensive medical knowledge. However their application in healthcare is constrained due to concerns about the privacy of data used in training which prevents the integration of private and personal information because of security and ethical issues. Moreover if their capabilities can be enhanced with information retrieval to access up-to-date knowledge the current integration of LLMs with Information retrieval lacks robustness to imperfect retrieval which can hinder their effectiveness and even reduce overall performance. In this work we address this challenge by introducing the Retrieval-Augmented Thought Process (RATP). Given access to external knowledge RATP formulates the thought generation of LLMs as a multiple-step decision process. To optimise such a thought process RATP leverages Monte-Carlo Tree Search and learns a proxy reward function that permits cost-efficient inference. On a private dataset of electronic medical records deliberately excluded from any LLM training set RATP achieves 3537; additional accuracy compared to in-context retrieval-augmented generation for the question-answering task.
