---
layout: publication
title: Eliciting the Translation Ability of Large Language Models via Multilingual Finetuning with Translation Instructions
authors: Li Jiahuan, Zhou Hao, Huang Shujian, Cheng Shanbo, Chen Jiajun
conference: "Arxiv"
year: 2023
bibkey: li2023eliciting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.15083"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
Large-scale Pretrained Language Models (LLMs) such as ChatGPT and GPT4 have shown strong abilities in multilingual translations without being explicitly trained on parallel corpora. It is interesting how the LLMs obtain their ability to carry out translation instructions for different languages. In this paper we present a detailed analysis by finetuning a multilingual pretrained language model XGLM-7B to perform multilingual translation following given instructions. Firstly we show that multilingual LLMs have stronger translation abilities than previously demonstrated. For a certain language the performance depends on its similarity to English and the amount of data used in the pretraining phase. Secondly we find that LLMs ability to carry out translation instructions relies on the understanding of translation instructions and the alignment among different languages. With multilingual finetuning LLMs could learn to perform the translation task well even for those language pairs unseen during the instruction tuning phase.
