---
layout: publication
title: 'Instruct-skillmix: A Powerful Pipeline For LLM Instruction Tuning'
authors: Kaur Simran, Park Simon, Goyal Anirudh, Arora Sanjeev
conference: "Arxiv"
year: 2024
bibkey: kaur2024instruct
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.14774"}
tags: ['Fine Tuning', 'Pretraining Methods', 'Prompting', 'RAG', 'Reinforcement Learning']
---
'We introduce Instruct-SkillMix, an automated approach for creating diverse, high quality SFT data. The Instruct-SkillMix pipeline involves two stages, each leveraging an existing powerful LLM: (1) Skill extraction: uses the LLM to extract core skills for instruction-following, either from existing datasets, or by directly prompting the model; (2) Data generation: uses the powerful LLM to generate (instruction, response) data that exhibit a randomly chosen pair of these skills. Here, the use of random skill combinations promotes diversity and difficulty. Vanilla SFT (i.e., no PPO, DPO, or RL methods) on data generated from Instruct-SkillMix leads to strong gains on instruction following benchmarks such as AlpacaEval 2.0, MT-Bench, and WildBench. With just \(4\)K examples, LLaMA-3-8B-Base achieves 42.76&#37; length-controlled win rate on AlpacaEval 2.0. To our knowledge, this achieves state-of-the-art performance among all models that have only undergone SFT (no RL methods) and competes with proprietary models such as Claude 3 Opus and LLaMA-3.1-405B-Instruct. Ablation studies also suggest plausible reasons for why creating open instruction-tuning datasets via naive crowd-sourcing has proved difficult. Introducing low quality answers (shirkers) in \(20\%\) of Instruct-SkillMix examples causes performance to plummet, sometimes catastrophically. The Instruct-SkillMix pipeline is flexible and is adaptable to other settings.'
