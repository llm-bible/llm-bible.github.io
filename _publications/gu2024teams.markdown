---
layout: publication
title: Teams45;rl Teaching Llms To Generate Better Instruction Datasets Via Reinforcement Learning
authors: Gu Shangding, Knoll Alois, Jin Ming
conference: "Arxiv"
year: 2024
bibkey: gu2024teams
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.08694"}
  - {name: "Code", url: "https://github.com/SafeRL&#45;Lab/TeaMs&#45;RL"}
tags: ['Agentic', 'Has Code', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
The development of Large Language Models (LLMs) often confronts challenges stemming from the heavy reliance on human annotators in the reinforcement learning with human feedback (RLHF) framework or the frequent and costly external queries tied to the self45;instruct paradigm. In this work we pivot to Reinforcement Learning (RL) 45;45; but with a twist. Diverging from the typical RLHF which refines LLMs following instruction data training we use RL to directly generate the foundational instruction dataset that alone suffices for fine45;tuning. Our method TeaMs45;RL uses a suite of textual operations and rules prioritizing the diversification of training datasets. It facilitates the generation of high45;quality data without excessive reliance on external advanced models paving the way for a single fine45;tuning step and negating the need for subsequent RLHF stages. Our findings highlight key advantages of our approach reduced need for human involvement and fewer model queries (only 5.7337; of the strong baselines total) along with enhanced capabilities of LLMs in crafting and comprehending complex instructions compared to strong baselines and substantially improved model privacy protection. Code is available at the link https://github.com/SafeRL&#45;Lab/TeaMs&#45;RL
