---
layout: publication
title: Autoregressive Entity Generation for End-to-End Task-Oriented Dialog
authors: Huang Guanhuan, Quan Xiaojun, Wang Qifan
conference: "Arxiv"
year: 2022
bibkey: huang2022autoregressive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2209.08708"}
tags: ['Efficiency And Optimization', 'GPT', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Task-oriented dialog (TOD) systems often require interaction with an external knowledge base to retrieve necessary entity (e.g. restaurant) information to support the response generation. Most current end-to-end TOD systems either retrieve the KB information explicitly or embed it into model parameters for implicit access.~While the former approach demands scanning the KB at each turn of response generation which is inefficient when the KB scales up the latter approach shows higher flexibility and efficiency. In either approach the systems may generate a response with conflicting entity information. To address this issue we propose to generate the entity autoregressively first and leverage it to guide the response generation in an end-to-end system. To ensure entity consistency we impose a trie constraint on entity generation. We also introduce a logit concatenation strategy to facilitate gradient backpropagation for end-to-end training. Experiments on MultiWOZ 2.1 single and CAMREST show that our system can generate more high-quality and entity-consistent responses.
