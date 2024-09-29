---
layout: publication
title: Task-oriented Conversation Generation Using Heterogeneous Memory Networks
authors: Lin Zehao, Huang Xinjing, Ji Feng, Chen Haiqing, Zhang Ying
conference: "Arxiv"
year: 2019
bibkey: lin2019task
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1909.11287"}
tags: ['Applications', 'RAG', 'Reinforcement Learning']
---
How to incorporate external knowledge into a neural dialogue model is critically important for dialogue systems to behave like real humans. To handle this problem memory networks are usually a great choice and a promising way. However existing memory networks do not perform well when leveraging heterogeneous information from different sources. In this paper we propose a novel and versatile external memory networks called Heterogeneous Memory Networks (HMNs) to simultaneously utilize user utterances dialogue history and background knowledge tuples. In our method historical sequential dialogues are encoded and stored into the context-aware memory enhanced by gating mechanism while grounding knowledge tuples are encoded and stored into the context-free memory. During decoding the decoder augmented with HMNs recurrently selects each word in one response utterance from these two memories and a general vocabulary. Experimental results on multiple real-world datasets show that HMNs significantly outperform the state-of-the-art data-driven task-oriented dialogue models in most domains.
