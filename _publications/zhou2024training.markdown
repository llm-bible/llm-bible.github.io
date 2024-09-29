---
layout: publication
title: Archer Training Language Model Agents Via Hierarchical Multi45;turn RL
authors: Zhou Yifei, Zanette Andrea, Pan Jiayi, Levine Sergey, Kumar Aviral
conference: "Arxiv"
year: 2024
bibkey: zhou2024training
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.19446"}
tags: ['Agentic', 'Efficiency And Optimization', 'Prompting', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
A broad use case of large language models (LLMs) is in goal45;directed decision45;making tasks (or agent tasks) where an LLM needs to not just generate completions for a given prompt but rather make intelligent decisions over a multi45;turn interaction to accomplish a task (e.g. when interacting with the web using tools or providing customer support). Reinforcement learning (RL) provides a general paradigm to address such agent tasks but current RL methods for LLMs largely focus on optimizing single45;turn rewards. By construction most single45;turn RL methods cannot endow LLMs with the ability to intelligently seek information over multiple turns perform credit assignment or reason about their past actions 45;45; all of which are critical in agent tasks. This raises the question how can we design effective and efficient multi45;turn RL algorithms for LLMs In this paper we develop a framework for building multi45;turn RL algorithms for fine45;tuning LLMs that preserves the flexibility of existing single45;turn RL methods for LLMs (e.g. proximal policy optimization) while accommodating multiple turns long horizons and delayed rewards effectively. To do this our framework adopts a hierarchical RL approach and runs two RL algorithms in parallel a high45;level off45;policy value45;based RL algorithm to aggregate reward over utterances and a low45;level RL algorithm that utilizes this high45;level value function to train a token policy within each utterance or turn. Our hierarchical framework Actor45;Critic Framework with a Hierarchical Structure (ArCHer) can also give rise to other RL methods. Empirically we find that ArCHer significantly improves efficiency and performance on agent tasks attaining a sample efficiency of about 100x over existing methods while also improving with larger model capacity (upto the 7 billion scale that we tested on).
