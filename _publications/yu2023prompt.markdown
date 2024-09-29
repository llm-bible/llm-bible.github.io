---
layout: publication
title: Prompt45;based Monte45;carlo Tree Search For Goal45;oriented Dialogue Policy Planning
authors: Yu Xiao, Chen Maximillian, Yu Zhou
conference: "Arxiv"
year: 2023
bibkey: yu2023prompt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.13660"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
Planning for goal45;oriented dialogue often requires simulating future dialogue interactions and estimating task progress. Many approaches thus consider training neural networks to perform look45;ahead search algorithms such as A search and Monte Carlo Tree Search (MCTS). However this training often requires abundant annotated data which creates challenges when faced with noisy annotations or low45;resource settings. We introduce GDP45;Zero an approach using Open45;Loop MCTS to perform goal45;oriented dialogue policy planning without any model training. GDP45;Zero prompts a large language model to act as a policy prior value function user simulator and system model during the tree search. We evaluate GDP45;Zero on the goal45;oriented task PersuasionForGood and find that its responses are preferred over ChatGPT up to 59.3237; of the time and are rated more persuasive than ChatGPT during interactive evaluations.
