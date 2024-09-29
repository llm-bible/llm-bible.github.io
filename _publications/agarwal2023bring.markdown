---
layout: publication
title: Bring Your Own KG Self45;supervised Program Synthesis For Zero45;shot KGQA
authors: Agarwal Dhruv, Das Rajarshi, Khosla Sopan, Gangadharaiah Rashmi
conference: "Arxiv"
year: 2023
bibkey: agarwal2023bring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.07850"}
tags: ['Agentic', 'Applications', 'Fine Tuning', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
We present BYOKG a universal question45;answering (QA) system that can operate on any knowledge graph (KG) requires no human45;annotated training data and can be ready to use within a day 45;45; attributes that are out45;of45;scope for current KGQA systems. BYOKG draws inspiration from the remarkable ability of humans to comprehend information present in an unseen KG through exploration 45;45; starting at random nodes inspecting the labels of adjacent nodes and edges and combining them with their prior world knowledge. In BYOKG exploration leverages an LLM45;backed symbolic agent that generates a diverse set of query45;program exemplars which are then used to ground a retrieval45;augmented reasoning procedure to predict programs for arbitrary questions. BYOKG is effective over both small45; and large45;scale graphs showing dramatic gains in QA accuracy over a zero45;shot baseline of 27.89 and 58.02 F1 on GrailQA and MetaQA respectively. On GrailQA we further show that our unsupervised BYOKG outperforms a supervised in45;context learning method demonstrating the effectiveness of exploration. Lastly we find that performance of BYOKG reliably improves with continued exploration as well as improvements in the base LLM notably outperforming a state45;of45;the45;art fine45;tuned model by 7.08 F1 on a sub45;sampled zero45;shot split of GrailQA.
