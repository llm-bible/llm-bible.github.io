---
layout: publication
title: 'In-context Learning Can Re-learn Forbidden Tasks'
authors: Xhonneux Sophie, Dobre David, Tang Jian, Gidel Gauthier, Sridhar Dhanya
conference: "Arxiv"
year: 2024
bibkey: xhonneux2024learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.05723"}
tags: ['Fine Tuning', 'In Context Learning', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Responsible AI', 'Security', 'Training Techniques']
---
'Despite significant investment into safety training, large language models (LLMs) deployed in the real world still suffer from numerous vulnerabilities. One perspective on LLM safety training is that it algorithmically forbids the model from answering toxic or harmful queries. To assess the effectiveness of safety training, in this work, we study forbidden tasks, i.e., tasks the model is designed to refuse to answer. Specifically, we investigate whether in-context learning (ICL) can be used to re-learn forbidden tasks despite the explicit fine-tuning of the model to refuse them. We first examine a toy example of refusing sentiment classification to demonstrate the problem. Then, we use ICL on a model fine-tuned to refuse to summarise made-up news articles. Finally, we investigate whether ICL can undo safety training, which could represent a major security risk. For the safety task, we look at Vicuna-7B, Starling-7B, and Llama2-7B. We show that the attack works out-of-the-box on Starling-7B and Vicuna-7B but fails on Llama2-7B. Finally, we propose an ICL attack that uses the chat template tokens like a prompt injection attack to achieve a better attack success rate on Vicuna-7B and Starling-7B. Trigger Warning: the appendix contains LLM-generated text with violence, suicide, and misinformation.'
