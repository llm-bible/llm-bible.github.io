---
layout: publication
title: Generalizing Conversational Dense Retrieval Via Llm45;cognition Data Augmentation
authors: Chen Haonan, Dou Zhicheng, Mao Kelong, Liu Jiongnan, Zhao Ziliang
conference: "Arxiv"
year: 2024
bibkey: chen2024generalizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.07092"}
  - {name: "Code", url: "https://github.com/haon&#45;chen/ConvAug"}
tags: ['Has Code', 'Pretraining Methods', 'Reinforcement Learning', 'Tools']
---
Conversational search utilizes muli45;turn natural language contexts to retrieve relevant passages. Existing conversational dense retrieval models mostly view a conversation as a fixed sequence of questions and responses overlooking the severe data sparsity problem 45;45; that is users can perform a conversation in various ways and these alternate conversations are unrecorded. Consequently they often struggle to generalize to diverse conversations in real45;world scenarios. In this work we propose a framework for generalizing Conversational dense retrieval via LLM45;cognition data Augmentation (ConvAug). ConvAug first generates multi45;level augmented conversations to capture the diverse nature of conversational contexts. Inspired by human cognition we devise a cognition45;aware process to mitigate the generation of false positives false negatives and hallucinations. Moreover we develop a difficulty45;adaptive sample filter that selects challenging samples for complex conversations thereby giving the model a larger learning space. A contrastive learning objective is then employed to train a better conversational context encoder. Extensive experiments conducted on four public datasets under both normal and zero45;shot settings demonstrate the effectiveness generalizability and applicability of ConvAug. The code is released at https://github.com/haon&#45;chen/ConvAug.
