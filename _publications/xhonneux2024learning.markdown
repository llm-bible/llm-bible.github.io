---
layout: publication
title: In45;context Learning Can Re45;learn Forbidden Tasks
authors: Xhonneux Sophie, Dobre David, Tang Jian, Gidel Gauthier, Sridhar Dhanya
conference: "Arxiv"
year: 2024
bibkey: xhonneux2024learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.05723"}
tags: ['Prompting', 'Reinforcement Learning', 'Responsible AI', 'Security', 'Training Techniques']
---
Despite significant investment into safety training large language models (LLMs) deployed in the real world still suffer from numerous vulnerabilities. One perspective on LLM safety training is that it algorithmically forbids the model from answering toxic or harmful queries. To assess the effectiveness of safety training in this work we study forbidden tasks i.e. tasks the model is designed to refuse to answer. Specifically we investigate whether in45;context learning (ICL) can be used to re45;learn forbidden tasks despite the explicit fine45;tuning of the model to refuse them. We first examine a toy example of refusing sentiment classification to demonstrate the problem. Then we use ICL on a model fine45;tuned to refuse to summarise made45;up news articles. Finally we investigate whether ICL can undo safety training which could represent a major security risk. For the safety task we look at Vicuna45;7B Starling45;7B and Llama245;7B. We show that the attack works out45;of45;the45;box on Starling45;7B and Vicuna45;7B but fails on Llama245;7B. Finally we propose an ICL attack that uses the chat template tokens like a prompt injection attack to achieve a better attack success rate on Vicuna45;7B and Starling45;7B. Trigger Warning the appendix contains LLM45;generated text with violence suicide and misinformation.
