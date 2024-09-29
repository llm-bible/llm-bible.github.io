---
layout: publication
title: Leveraging Large Language Models in Conversational Recommender Systems
authors: Friedman Luke, Ahuja Sameer, Allen David, Tan Zhenning, Sidahmed Hakim, Long Changbo, Xie Jun, Schubiner Gabriel, Patel Ajay, Lara Harsh, Chu Brian, Chen Zexi, Tiwari Manoj
conference: "Arxiv"
year: 2023
bibkey: friedman2023leveraging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.07961"}
tags: ['Ethics And Bias', 'Model Architecture', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
A Conversational Recommender System (CRS) offers increased transparency and control to users by enabling them to engage with the system through a real-time multi-turn dialogue. Recently Large Language Models (LLMs) have exhibited an unprecedented ability to converse naturally and incorporate world knowledge and common-sense reasoning into language understanding unlocking the potential of this paradigm. However effectively leveraging LLMs within a CRS introduces new technical challenges including properly understanding and controlling a complex conversation and retrieving from external sources of information. These issues are exacerbated by a large evolving item corpus and a lack of conversational data for training. In this paper we provide a roadmap for building an end-to-end large-scale CRS using LLMs. In particular we propose new implementations for user preference understanding flexible dialogue management and explainable recommendations as part of an integrated architecture powered by LLMs. For improved personalization we describe how an LLM can consume interpretable natural language user profiles and use them to modulate session-level context. To overcome conversational data limitations in the absence of an existing production CRS we propose techniques for building a controllable LLM-based user simulator to generate synthetic conversations. As a proof of concept we introduce RecLLM a large-scale CRS for YouTube videos built on LaMDA and demonstrate its fluency and diverse functionality through some illustrative example conversations.
