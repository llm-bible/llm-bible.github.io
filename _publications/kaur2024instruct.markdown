---
layout: publication
title: Instruct45;skillmix A Powerful Pipeline For LLM Instruction Tuning
authors: Kaur Simran, Park Simon, Goyal Anirudh, Arora Sanjeev
conference: "Arxiv"
year: 2024
bibkey: kaur2024instruct
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.14774"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'Prompting', 'RAG', 'Reinforcement Learning']
---
We introduce Instruct45;SkillMix an automated approach for creating diverse high quality SFT data. The Instruct45;SkillMix pipeline involves two stages each leveraging an existing powerful LLM (1) Skill extraction uses the LLM to extract core skills for instruction45;following either from existing datasets or by directly prompting the model; (2) Data generation uses the powerful LLM to generate (instruction response) data that exhibit a randomly chosen pair of these skills. Here the use of random skill combinations promotes diversity and difficulty. Vanilla SFT (i.e. no PPO DPO or RL methods) on data generated from Instruct45;SkillMix leads to strong gains on instruction following benchmarks such as AlpacaEval 2.0 MT45;Bench and WildBench. With just 4K examples LLaMA45;345;8B45;Base achieves 42.7637; length45;controlled win rate on AlpacaEval 2.0. To our knowledge this achieves state45;of45;the45;art performance among all models that have only undergone SFT (no RL methods) and competes with proprietary models such as Claude 3 Opus and LLaMA45;3.145;405B45;Instruct. Ablation studies also suggest plausible reasons for why creating open instruction45;tuning datasets via naive crowd45;sourcing has proved difficult. Introducing low quality answers (shirkers) in 2037; of Instruct45;SkillMix examples causes performance to plummet sometimes catastrophically. The Instruct45;SkillMix pipeline is flexible and is adaptable to other settings.
