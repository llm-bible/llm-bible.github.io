---
layout: publication
title: Pokergpt An End45;to45;end Lightweight Solver For Multi45;player Texas Holdem Via Large Language Model
authors: Huang Chenghao, Cao Yanbo, Wen Yinlong, Zhou Tao, Zhang Yanru
conference: "Arxiv"
year: 2024
bibkey: huang2024end
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.06781"}
tags: ['Agentic', 'Applications', 'GPT', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
Poker also known as Texas Holdem has always been a typical research target within imperfect information games (IIGs). IIGs have long served as a measure of artificial intelligence (AI) development. Representative prior works such as DeepStack and Libratus heavily rely on counterfactual regret minimization (CFR) to tackle heads45;up no45;limit Poker. However it is challenging for subsequent researchers to learn CFR from previous models and apply it to other real45;world applications due to the expensive computational cost of CFR iterations. Additionally CFR is difficult to apply to multi45;player games due to the exponential growth of the game tree size. In this work we introduce PokerGPT an end45;to45;end solver for playing Texas Holdem with arbitrary number of players and gaining high win rates established on a lightweight large language model (LLM). PokerGPT only requires simple textual information of Poker games for generating decision45;making advice thus guaranteeing the convenient interaction between AI and humans. We mainly transform a set of textual records acquired from real games into prompts and use them to fine45;tune a lightweight pre45;trained LLM using reinforcement learning human feedback technique. To improve fine45;tuning performance we conduct prompt engineering on raw data including filtering useful information selecting behaviors of players with high win rates and further processing them into textual instruction using multiple prompt engineering techniques. Through the experiments we demonstrate that PokerGPT outperforms previous approaches in terms of win rate model size training time and response speed indicating the great potential of LLMs in solving IIGs.
