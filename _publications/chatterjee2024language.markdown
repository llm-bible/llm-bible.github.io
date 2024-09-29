---
layout: publication
title: Language Models Can Exploit Cross45;task In45;context Learning For Data45;scarce Novel Tasks
authors: Chatterjee Anwoy, Tanwar Eshaan, Dutta Subhabrata, Chakraborty Tanmoy
conference: "Arxiv"
year: 2024
bibkey: chatterjee2024language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.10548"}
tags: ['Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Transformer']
---
Large Language Models (LLMs) have transformed NLP with their remarkable In45;context Learning (ICL) capabilities. Automated assistants based on LLMs are gaining popularity; however adapting them to novel tasks is still challenging. While colossal models excel in zero45;shot performance their computational demands limit widespread use and smaller language models struggle without context. This paper investigates whether LLMs can generalize from labeled examples of predefined tasks to novel tasks. Drawing inspiration from biological neurons and the mechanistic interpretation of the Transformer architecture we explore the potential for information sharing across tasks. We design a cross45;task prompting setup with three LLMs and show that LLMs achieve significant performance improvements despite no examples from the target task in the context. Cross45;task prompting leads to a remarkable performance boost of 10737; for LLaMA45;2 7B 18.637; for LLaMA45;2 13B and 3.237; for GPT 3.5 on average over zero45;shot prompting and performs comparable to standard in45;context learning. The effectiveness of generating pseudo45;labels for in45;task examples is demonstrated and our analyses reveal a strong correlation between the effect of cross45;task examples and model activation similarities in source and target input tokens. This paper offers a first45;of45;its45;kind exploration of LLMs ability to solve novel tasks based on contextual signals from different task examples.
