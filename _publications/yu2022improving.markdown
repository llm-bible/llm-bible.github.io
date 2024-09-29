---
layout: publication
title: KRLS Improving End45;to45;end Response Generation In Task Oriented Dialog With Reinforced Keywords Learning
authors: Yu Xiao, Wu Qingyang, Qian Kun, Yu Zhou
conference: "Arxiv"
year: 2022
bibkey: yu2022improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2211.16773"}
tags: ['Agentic', 'Fine Tuning', 'Reinforcement Learning', 'Training Techniques']
---
In task45;oriented dialogs (TOD) reinforcement learning (RL) algorithms train a model to directly optimize response for task45;related metrics. However RL needs to perform exploration which can be time45;consuming due to the slow auto45;regressive sequence generation process. We investigate an approach to create a more efficient RL45;based algorithm to improve TOD performance in an offline setting. First we use a faster generation procedure that samples from independent next45;word distributions after training the language model (LM) with supervised learning. We then introduce a fine45;grained reward function to help the model focus on learning key information in a dialog by measuring the importance and semantic closeness of each generated token. Experiments on the MultiWoZ dataset show our new training algorithm Keywords Reinforcement Learning with Next45;word Sampling (KRLS) achieves state45;of45;the45;art performance on the end45;to45;end response generation task with a 1537; training time reduction compared to a standard RL algorithm using auto45;regressive generation.
