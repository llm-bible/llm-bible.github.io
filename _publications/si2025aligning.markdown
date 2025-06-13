---
layout: publication
title: 'Aligning Large Language Models To Follow Instructions And Hallucinate Less Via Effective Data Filtering'
authors: Shuzheng Si, Haozhe Zhao, Gang Chen, Cheng Gao, Yuzhuo Bai, Zhitong Wang, Kaikai An, Kangyang Luo, Chen Qian, Fanchao Qi, Baobao Chang, Maosong Sun
conference: "Arxiv"
year: 2025
bibkey: si2025aligning
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.07340'}
tags: ['Reinforcement Learning', 'RAG', 'Training Techniques', 'Tools']
---
Training LLMs on data containing unfamiliar knowledge during the instruction tuning stage can encourage hallucinations. To address this challenge, we introduce NOVA, a novel framework designed to identify high-quality data that aligns well with the LLM's learned knowledge to reduce hallucinations. NOVA includes Internal Consistency Probing (ICP) and Semantic Equivalence Identification (SEI) to measure how familiar the LLM is with instruction data. Specifically, ICP evaluates the LLM's understanding of the given instruction by calculating the tailored consistency among multiple self-generated responses. SEI further assesses the familiarity of the LLM with the target response by comparing it to the generated responses, using the proposed semantic clustering and well-designed voting strategy. Finally, to ensure the quality of selected samples, we introduce an expert-aligned reward model, considering characteristics beyond just familiarity. By considering data quality and avoiding unfamiliar data, we can utilize the selected data to effectively align LLMs to follow instructions and hallucinate less.
