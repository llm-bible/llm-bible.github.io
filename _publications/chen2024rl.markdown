---
layout: publication
title: RL45;JACK Reinforcement Learning45;powered Black45;box Jailbreaking Attack Against Llms
authors: Chen Xuan, Nie Yuzhou, Yan Lu, Mao Yunshu, Guo Wenbo, Zhang Xiangyu
conference: "Arxiv"
year: 2024
bibkey: chen2024rl
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.08725"}
tags: ['Agentic', 'Efficiency And Optimization', 'Prompting', 'Reinforcement Learning', 'Responsible AI', 'Security', 'Training Techniques']
---
Modern large language model (LLM) developers typically conduct a safety alignment to prevent an LLM from generating unethical or harmful content. Recent studies have discovered that the safety alignment of LLMs can be bypassed by jailbreaking prompts. These prompts are designed to create specific conversation scenarios with a harmful question embedded. Querying an LLM with such prompts can mislead the model into responding to the harmful question. The stochastic and random nature of existing genetic methods largely limits the effectiveness and efficiency of state45;of45;the45;art (SOTA) jailbreaking attacks. In this paper we propose RL45;JACK a novel black45;box jailbreaking attack powered by deep reinforcement learning (DRL). We formulate the generation of jailbreaking prompts as a search problem and design a novel RL approach to solve it. Our method includes a series of customized designs to enhance the RL agents learning efficiency in the jailbreaking context. Notably we devise an LLM45;facilitated action space that enables diverse action variations while constraining the overall search space. We propose a novel reward function that provides meaningful dense rewards for the agent toward achieving successful jailbreaking. Through extensive evaluations we demonstrate that RL45;JACK is overall much more effective than existing jailbreaking attacks against six SOTA LLMs including large open45;source models and commercial models. We also show the RL45;JACKs resiliency against three SOTA defenses and its transferability across different models. Finally we validate the insensitivity of RL45;JACK to the variations in key hyper45;parameters.
