---
layout: publication
title: Bridging The Preference Gap Between Retrievers And Llms
authors: Ke Zixuan, Kong Weize, Li Cheng, Zhang Mingyang, Mei Qiaozhu, Bendersky Michael
conference: "Arxiv"
year: 2024
bibkey: ke2024bridging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.06954"}
tags: ['Agentic', 'RAG', 'Reinforcement Learning', 'Tools']
---
Large Language Models (LLMs) have demonstrated superior results across a wide range of tasks and Retrieval45;augmented Generation (RAG) is an effective way to enhance the performance by locating relevant information and placing it into the context window of the LLM. However the relationship between retrievers and LLMs in a RAG is still under45;investigated. Most existing work treats the retriever and the LLM as independent components and leaves a gap between retrieving human45;friendly information and assembling a LLM45;friendly context. In this work we examine a novel bridge mechanism. We validate the ranking and selection assumptions of retrievers in the context of RAG and propose a framework that chains together supervised and reinforcement learning to train a bridge model that optimizes the connection between the retriever and the LLM. Empirical results demonstrate the effectiveness of our method in both question45;answering and personalized generation tasks.
