---
layout: publication
title: Topicrefine\: Joint Topic Prediction And Dialogue Response Generation For Multi-turn End-to-end Dialogue System
authors: Wang Hongru, Cui Mingyu, Zhou Zimo, Fung Gabriel Pui Cheong, Wong Kam-fai
conference: "Arxiv"
year: 2021
bibkey: wang2021joint
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2109.05187"}
tags: ['Attention Mechanism', 'BERT', 'GPT', 'Model Architecture', 'Tools', 'Transformer']
---
A multi-turn dialogue always follows a specific topic thread and topic shift at the discourse level occurs naturally as the conversation progresses necessitating the models ability to capture different topics and generate topic-aware responses. Previous research has either predicted the topic first and then generated the relevant response or simply applied the attention mechanism to all topics ignoring the joint distribution of the topic prediction and response generation models and resulting in uncontrollable and unrelated responses. In this paper we propose a joint framework with a topic refinement mechanism to learn these two tasks simultaneously. Specifically we design a three-pass iteration mechanism to generate coarse response first then predict corresponding topics and finally generate refined response conditioned on predicted topics. Moreover we utilize GPT2DoubleHeads and BERT for the topic prediction task respectively aiming to investigate the effects of joint learning and the understanding ability of GPT model. Experimental results demonstrate that our proposed framework achieves new state-of-the-art performance at response generation task and the great potential understanding capability of GPT model.
