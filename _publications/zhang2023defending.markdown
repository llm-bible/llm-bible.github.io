---
layout: publication
title: Defending Large Language Models Against Jailbreaking Attacks Through Goal Prioritization
authors: Zhang Zhexin, Yang Junxiao, Ke Pei, Mi Fei, Wang Hongning, Huang Minlie
conference: "Arxiv"
year: 2023
bibkey: zhang2023defending
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.09096"}
  - {name: "Code", url: "https://github.com/thu-coai/JailbreakDefense_GoalPriority"}
tags: ['Attention Mechanism', 'GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Responsible AI', 'Security', 'Training Techniques']
---
While significant attention has been dedicated to exploiting weaknesses in LLMs through jailbreaking attacks there remains a paucity of effort in defending against these attacks. We point out a pivotal factor contributing to the success of jailbreaks the intrinsic conflict between the goals of being helpful and ensuring safety. Accordingly we propose to integrate goal prioritization at both training and inference stages to counteract. Implementing goal prioritization during inference substantially diminishes the Attack Success Rate (ASR) of jailbreaking from 66.4 to 3.6 for ChatGPT. And integrating goal prioritization into model training reduces the ASR from 71.0 to 6.6 for Llama2-13B. Remarkably even in scenarios where no jailbreaking samples are included during training our approach slashes the ASR by half. Additionally our findings reveal that while stronger LLMs face greater safety risks they also possess a greater capacity to be steered towards defending against such attacks both because of their stronger ability in instruction following. Our work thus contributes to the comprehension of jailbreaking attacks and defenses and sheds light on the relationship between LLMs capability and safety. Our code is available at url https://github.com/thu-coai/JailbreakDefense_GoalPriority.
