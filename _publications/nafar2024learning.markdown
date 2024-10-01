---
layout: publication
title: 'Learning Vs Retrieval: The Role Of In-context Examples In Regression With Llms'
authors: Nafar Aliakbar, Venable Kristen Brent, Kordjamshidi Parisa
conference: "Arxiv"
year: 2024
bibkey: nafar2024learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.04318"}
tags: ['In Context Learning', 'Prompting', 'RAG', 'Reinforcement Learning', 'Security', 'Tools']
---
Generative Large Language Models (LLMs) are capable of being in-context learners. However, the underlying mechanism of in-context learning (ICL) is still a major research question, and experimental research results about how models exploit ICL are not always consistent. In this work, we propose a framework for evaluating in-context learning mechanisms, which we claim are a combination of retrieving internal knowledge and learning from in-context examples by focusing on regression tasks. First, we show that LLMs can perform regression on real-world datasets and then design experiments to measure the extent to which the LLM retrieves its internal knowledge versus learning from in-context examples. We argue that this process lies on a spectrum between these two extremes. We provide an in-depth analysis of the degrees to which these mechanisms are triggered depending on various factors, such as prior knowledge about the tasks and the type and richness of the information provided by the in-context examples. We employ three LLMs and utilize multiple datasets to corroborate the robustness of our findings. Our results shed light on how to engineer prompts to leverage meta-learning from in-context examples and foster knowledge retrieval depending on the problem being addressed.
