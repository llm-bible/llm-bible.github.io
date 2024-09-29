---
layout: publication
title: Rlprompt Optimizing Discrete Text Prompts With Reinforcement Learning
authors: Deng Mingkai, Wang Jianyu, Hsieh Cheng-ping, Wang Yihan, Guo Han, Shu Tianmin, Song Meng, Xing Eric P., Hu Zhiting
conference: "Arxiv"
year: 2022
bibkey: deng2022rlprompt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2205.12548"}
tags: ['Agentic', 'BERT', 'Efficiency And Optimization', 'Few Shot', 'GPT', 'Interpretability And Explainability', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
Prompting has shown impressive success in enabling large pretrained language models (LMs) to perform diverse NLP tasks especially when only few downstream data are available. Automatically finding the optimal prompt for each task however is challenging. Most existing work resorts to tuning soft prompt (e.g. embeddings) which falls short of interpretability reusability across LMs and applicability when gradients are not accessible. Discrete prompt on the other hand is difficult to optimize and is often created by enumeration (e.g. paraphrasing)-then-selection heuristics that do not explore the prompt space systematically. This paper proposes RLPrompt an efficient discrete prompt optimization approach with reinforcement learning (RL). RLPrompt formulates a parameter-efficient policy network that generates the desired discrete prompt after training with reward. To overcome the complexity and stochasticity of reward signals by the large LM environment we incorporate effective reward stabilization that substantially enhances the training efficiency. RLPrompt is flexibly applicable to different types of LMs such as masked (e.g. BERT) and left-to-right models (e.g. GPTs) for both classification and generation tasks. Experiments on few-shot classification and unsupervised text style transfer show superior performance over a wide range of existing finetuning or prompting methods. Interestingly the resulting optimized prompts are often ungrammatical gibberish text; and surprisingly those gibberish prompts are transferrable between different LMs to retain significant performance indicating LM prompting may not follow human language patterns.
