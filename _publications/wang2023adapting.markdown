---
layout: publication
title: Adapting LLM Agents With Universal Feedback In Communication
authors: Wang Kuan, Lu Yadong, Santacroce Michael, Gong Yeyun, Zhang Chao, Shen Yelong
conference: "Arxiv"
year: 2023
bibkey: wang2023adapting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.01444"}
tags: ['Agentic', 'Efficiency And Optimization', 'Reinforcement Learning', 'Training Techniques']
---
Recent advances in large language models (LLMs) have demonstrated potential for LLM agents. To facilitate the training for these agents with both linguistic feedback and non45;linguistic reward signals we introduce Learning through Communication (LTC). We design a universal buffer to store all the feedback and an iterative pipeline to enable an LLM agent to explore and update its policy in an given environment. To optimize agent interactions for task45;specific learning with our universal buffer and pipeline we introduce diverse communication patterns tailored for both single45;agent and multi45;agent environments. We evaluate the efficacy of our LTC approach on four diverse datasets ALFWorld (single45;agent) HotpotQA (multi45;agent collaboration) Chameleon (multi45;agent competition) and GSM8k (multi45;agent teacher45;student). On these data sets LTC outperforms the supervised instruction fine45;tuning baselines by 3.637; to 1237;. These results highlight the versatility and efficiency of LTC in facilitating online adaptation for LLM agents.
