---
layout: publication
title: 'Controllable Dialogue Generation With Disentangled Multi-grained Style Specification And Attribute Consistency Reward'
authors: Hu Zhe, Cao Zhiwei, Chan Hou Pong, Liu Jiachen, Xiao Xinyan, Su Jinsong, Wu Hua
conference: "Arxiv"
year: 2021
bibkey: hu2021controllable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2109.06717"}
tags: ['Applications', 'Language Modeling', 'Reinforcement Learning', 'Tools']
---
Controllable text generation is an appealing but challenging task, which allows users to specify particular attributes of the generated outputs. In this paper, we propose a controllable dialogue generation model to steer response generation under multi-attribute constraints. Specifically, we define and categorize the commonly used control attributes into global and local ones, which possess different granularities of effects on response generation. Then, we significantly extend the conventional seq2seq framework by introducing a novel two-stage decoder, which first uses a multi-grained style specification layer to impose the stylistic constraints and determine word-level control states of responses based on the attributes, and then employs a response generation layer to generate final responses maintaining both semantic relevancy to the contexts and fidelity to the attributes. Furthermore, we train our model with an attribute consistency reward to promote response control with explicit supervision signals. Extensive experiments and in-depth analyses on two datasets indicate that our model can significantly outperform competitive baselines in terms of response quality, content diversity and controllability.
