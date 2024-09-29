---
layout: publication
title: 'Parameter-efficient Tuning Helps Language Model Alignment'
authors: Xue Tianci, Wang Ziqi, Ji Heng
conference: "Arxiv"
year: 2023
bibkey: xue2023parameter
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.00819"}
tags: ['Agentic', 'Efficiency And Optimization', 'Fine Tuning', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
Aligning large language models (LLMs) with human preferences is essential for safe and useful LLMs. Previous works mainly adopt reinforcement learning (RLHF) and direct preference optimization (DPO) with human feedback for alignment. Nevertheless they have certain drawbacks. One such limitation is that they can only align models with one preference at the training time (e.g. they cannot learn to generate concise responses when the preference data prefers detailed responses) or have certain constraints for the data format (e.g. DPO only supports pairwise preference data). To this end prior works incorporate controllable generations for alignment to make language models learn multiple preferences and provide outputs with different preferences during inference if asked. Controllable generation also offers more flexibility with regard to data format (e.g. it supports pointwise preference data). Specifically it uses different control tokens for different preferences during training and inference making LLMs behave differently when required. Current controllable generation methods either use a special token or hand-crafted prompts as control tokens and optimize them together with LLMs. As control tokens are typically much lighter than LLMs this optimization strategy may not effectively optimize control tokens. To this end we first use parameter-efficient tuning (e.g. prompting tuning and low-rank adaptation) to optimize control tokens and then fine-tune models for controllable generations similar to prior works. Our approach alignMEnt with parameter-Efficient Tuning (MEET) improves the quality of control tokens thus improving controllable generation quality consistently by an apparent margin on two well-recognized datasets compared with prior works.
