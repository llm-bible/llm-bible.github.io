---
layout: publication
title: 'DFA-RAG: Conversational Semantic Router For Large Language Model With Definite Finite Automaton'
authors: Sun Yiyou, Hu Junjie, Cheng Wei, Chen Haifeng
conference: "Arxiv"
year: 2024
bibkey: sun2024dfa
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.04411"}
tags: ['Agentic', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
This paper introduces the retrieval-augmented large language model with Definite Finite Automaton (DFA-RAG), a novel framework designed to enhance the capabilities of conversational agents using large language models (LLMs). Traditional LLMs face challenges in generating regulated and compliant responses in special scenarios with predetermined response guidelines, like emotional support and customer service. Our framework addresses these challenges by embedding a Definite Finite Automaton (DFA), learned from training dialogues, within the LLM. This structured approach acts as a semantic router which enables the LLM to adhere to a deterministic response pathway. The routing is achieved by the retrieval-augmentation generation (RAG) strategy, which carefully selects dialogue examples aligned with the current conversational context. The advantages of DFA-RAG include an interpretable structure through human-readable DFA, context-aware retrieval for responses in conversations, and plug-and-play compatibility with existing LLMs. Extensive benchmarks validate DFA-RAG's effectiveness, indicating its potential as a valuable contribution to the conversational agent.
