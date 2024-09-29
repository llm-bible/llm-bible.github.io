---
layout: publication
title: "Editing Personality For Large Language Models"
authors: Mao Shengyu, Wang Xiaohan, Wang Mengru, Jiang Yong, Xie Pengjun, Huang Fei, Zhang Ningyu
conference: "Arxiv"
year: 2023
bibkey: mao2023editing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.02168"}
  - {name: "Code", url: "https://github.com/zjunlp/EasyEdit"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods']
---
This paper introduces an innovative task focused on editing the personality traits of Large Language Models (LLMs). This task seeks to adjust the models responses to opinion-related questions on specified topics since an individuals personality often manifests in the form of their expressed opinions thereby showcasing different personality traits. Specifically we construct PersonalityEdit a new benchmark dataset to address this task. Drawing on the theory in Social Psychology we isolate three representative traits namely Neuroticism Extraversion and Agreeableness as the foundation for our benchmark. We then gather data using GPT-4 generating responses that align with a specified topic and embody the targeted personality trait. We conduct comprehensive experiments involving various baselines and discuss the representation of personality behavior in LLMs. Our findings uncover potential challenges of the proposed task illustrating several remaining issues. We anticipate that our work can stimulate further annotation in model editing and personality-related research. Code is available at https://github.com/zjunlp/EasyEdit."
