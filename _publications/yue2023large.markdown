---
layout: publication
title: Large Language Model Cascades With Mixture Of Thoughts Representations For Cost45;efficient Reasoning
authors: Yue Murong, Zhao Jie, Zhang Min, Du Liang, Yao Ziyu
conference: "Arxiv"
year: 2023
bibkey: yue2023large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.03094"}
tags: ['Ethics And Bias', 'GPT', 'Model Architecture', 'RAG', 'Reinforcement Learning', 'Tools']
---
Large language models (LLMs) such as GPT45;4 have exhibited remarkable performance in a variety of tasks but this strong performance often comes with the high expense of using paid API services. In this paper we are motivated to study building an LLM cascade to save the cost of using LLMs particularly for performing reasoning (e.g. mathematical causal) tasks. Our cascade pipeline follows the intuition that simpler questions can be addressed by a weaker but more affordable LLM whereas only the challenging questions necessitate the stronger and more expensive LLM. To realize this decision45;making we consider the answer consistency of the weaker LLM as a signal of the question difficulty and propose several methods for the answer sampling and consistency checking including one leveraging a mixture of two thought representations (i.e. Chain45;of45;Thought and Program45;of45;Thought). Through experiments on six reasoning benchmark datasets with GPT45;3.545;turbo and GPT45;4 being the weaker and stronger LLMs respectively we demonstrate that our proposed LLM cascades can achieve performance comparable to using solely the stronger LLM but require only 4037; of its cost.
