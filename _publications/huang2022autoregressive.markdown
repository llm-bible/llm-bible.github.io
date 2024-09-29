---
layout: publication
title: Autoregressive Entity Generation For End45;to45;end Task45;oriented Dialog
authors: Huang Guanhuan, Quan Xiaojun, Wang Qifan
conference: "Arxiv"
year: 2022
bibkey: huang2022autoregressive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2209.08708"}
tags: ['Efficiency And Optimization', 'GPT', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Task45;oriented dialog (TOD) systems often require interaction with an external knowledge base to retrieve necessary entity (e.g. restaurant) information to support the response generation. Most current end45;to45;end TOD systems either retrieve the KB information explicitly or embed it into model parameters for implicit access.~While the former approach demands scanning the KB at each turn of response generation which is inefficient when the KB scales up the latter approach shows higher flexibility and efficiency. In either approach the systems may generate a response with conflicting entity information. To address this issue we propose to generate the entity autoregressively first and leverage it to guide the response generation in an end45;to45;end system. To ensure entity consistency we impose a trie constraint on entity generation. We also introduce a logit concatenation strategy to facilitate gradient backpropagation for end45;to45;end training. Experiments on MultiWOZ 2.1 single and CAMREST show that our system can generate more high45;quality and entity45;consistent responses.
