---
layout: publication
title: 'Bring Your Own KG: Self-supervised Program Synthesis For Zero-shot KGQA'
authors: Agarwal Dhruv, Das Rajarshi, Khosla Sopan, Gangadharaiah Rashmi
conference: "Arxiv"
year: 2023
bibkey: agarwal2023bring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.07850"}
tags: ['Agentic', 'Applications', 'Fine Tuning', 'In Context Learning', 'Prompting', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
We present BYOKG a universal question-answering (QA) system that can operate on any knowledge graph (KG) requires no human-annotated training data and can be ready to use within a day -- attributes that are out-of-scope for current KGQA systems. BYOKG draws inspiration from the remarkable ability of humans to comprehend information present in an unseen KG through exploration -- starting at random nodes inspecting the labels of adjacent nodes and edges and combining them with their prior world knowledge. In BYOKG exploration leverages an LLM-backed symbolic agent that generates a diverse set of query-program exemplars which are then used to ground a retrieval-augmented reasoning procedure to predict programs for arbitrary questions. BYOKG is effective over both small- and large-scale graphs showing dramatic gains in QA accuracy over a zero-shot baseline of 27.89 and 58.02 F1 on GrailQA and MetaQA respectively. On GrailQA we further show that our unsupervised BYOKG outperforms a supervised in-context learning method demonstrating the effectiveness of exploration. Lastly we find that performance of BYOKG reliably improves with continued exploration as well as improvements in the base LLM notably outperforming a state-of-the-art fine-tuned model by 7.08 F1 on a sub-sampled zero-shot split of GrailQA.
