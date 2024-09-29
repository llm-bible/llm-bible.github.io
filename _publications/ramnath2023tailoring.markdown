---
layout: publication
title: Tailoring Self45;rationalizers With Multi45;reward Distillation
authors: Ramnath Sahana, Joshi Brihi, Hallinan Skyler, Lu Ximing, Li Liunian Harold, Chan Aaron, Hessel Jack, Choi Yejin, Ren Xiang
conference: "The Twelfth International Conference on Learning Representations"
year: 2023
bibkey: ramnath2023tailoring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.02805"}
tags: ['Applications', 'Distillation', 'Efficiency And Optimization', 'Fine Tuning', 'GPT', 'Model Architecture', 'Reinforcement Learning']
---
Large language models (LMs) are capable of generating free45;text rationales to aid question answering. However prior work 1) suggests that useful self45;rationalization is emergent only at significant scales (e.g. 175B parameter GPT45;3); and 2) focuses largely on downstream performance ignoring the semantics of the rationales themselves e.g. are they faithful true and helpful for humans In this work we enable small45;scale LMs (approx. 200x smaller than GPT45;3) to generate rationales that not only improve downstream task performance but are also more plausible consistent and diverse assessed both by automatic and human evaluation. Our method MaRio (Multi45;rewArd RatIOnalization) is a multi45;reward conditioned self45;rationalization algorithm that optimizes multiple distinct properties like plausibility diversity and consistency. Results on five difficult question45;answering datasets StrategyQA QuaRel OpenBookQA NumerSense and QASC show that not only does MaRio improve task accuracy but it also improves the self45;rationalization quality of small LMs across the aforementioned axes better than a supervised fine45;tuning (SFT) baseline. Extensive human evaluations confirm that MaRio rationales are preferred vs. SFT rationales as well as qualitative improvements in plausibility and consistency.
