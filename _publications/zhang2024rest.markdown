---
layout: publication
title: Rest45;mcts LLM Self45;training Via Process Reward Guided Tree Search
authors: Zhang Dan, Zhoubian Sining, Hu Ziniu, Yue Yisong, Dong Yuxiao, Tang Jie
conference: "Arxiv"
year: 2024
bibkey: zhang2024rest
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.03816"}
tags: ['Agentic', 'Reinforcement Learning', 'Training Techniques']
---
Recent methodologies in LLM self45;training mostly rely on LLM generating responses and filtering those with correct output answers as training data. This approach often yields a low45;quality fine45;tuning training set (e.g. incorrect plans or intermediate reasoning). In this paper we develop a reinforced self45;training approach called ReST45;MCTS based on integrating process reward guidance with tree search MCTS for collecting higher45;quality reasoning traces as well as per45;step value to train policy and reward models. ReST45;MCTS circumvents the per45;step manual annotation typically used to train process rewards by tree45;search45;based reinforcement learning Given oracle final correct answers ReST45;MCTS is able to infer the correct process rewards by estimating the probability this step can help lead to the correct answer. These inferred rewards serve dual purposes they act as value targets for further refining the process reward model and also facilitate the selection of high45;quality traces for policy model self45;training. We first show that the tree45;search policy in ReST45;MCTS achieves higher accuracy compared with prior LLM reasoning baselines such as Best45;of45;N and Tree45;of45;Thought within the same search budget. We then show that by using traces searched by this tree45;search policy as training data we can continuously enhance the three language models for multiple iterations and outperform other self45;training algorithms such as ReST^text123;EM125; and Self45;Rewarding LM.
