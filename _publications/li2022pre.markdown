---
layout: publication
title: Pre45;trained Language Models For Interactive Decision45;making
authors: Li Shuang, Puig Xavier, Paxton Chris, Du Yilun, Wang Clinton, Fan Linxi, Chen Tao, Huang De-an, Akyürek Ekin, Anandkumar Anima, Andreas Jacob, Mordatch Igor, Torralba Antonio, Zhu Yuke
conference: "Arxiv"
year: 2022
bibkey: li2022pre
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2202.01771"}
tags: ['Agentic', 'Language Modeling', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Language model (LM) pre45;training is useful in many language processing tasks. But can pre45;trained LMs be further leveraged for more general machine learning problems We propose an approach for using LMs to scaffold learning and generalization in general sequential decision45;making problems. In this approach goals and observations are represented as a sequence of embeddings and a policy network initialized with a pre45;trained LM predicts the next action. We demonstrate that this framework enables effective combinatorial generalization across different environments and supervisory modalities. We begin by assuming access to a set of expert demonstrations and show that initializing policies with LMs and fine45;tuning them via behavior cloning improves task completion rates by 43.637; in the VirtualHome environment. Next we integrate an active data gathering procedure in which agents iteratively interact with the environment relabel past failed experiences with new goals and update their policies in a self45;supervised loop. Active data gathering further improves combinatorial generalization outperforming the best baseline by 25.137;. Finally we explain these results by investigating three possible factors underlying the effectiveness of the LM45;based policy. We find that sequential input representations (vs. fixed45;dimensional feature vectors) and LM45;based weight initialization are both important for generalization. Surprisingly however the format of the policy inputs encoding (e.g. as a natural language string vs. an arbitrary sequential encoding) has little influence. Together these results suggest that language modeling induces representations that are useful for modeling not just language but also goals and plans; these representations can aid learning and generalization even outside of language processing.
