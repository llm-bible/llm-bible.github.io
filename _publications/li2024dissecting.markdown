---
layout: publication
title: Dissecting Human And LLM Preferences
authors: Li Junlong, Zhou Fan, Sun Shichao, Zhang Yikai, Zhao Hai, Liu Pengfei
conference: "Arxiv"
year: 2024
bibkey: li2024dissecting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.11296"}
  - {name: "Code", url: "https://huggingface.co/spaces/GAIR/Preference&#45;Dissection&#45;Visualization"}
  - {name: "Code", url: "https://huggingface.co/datasets/GAIR/preference&#45;dissection"}
  - {name: "Code", url: "https://github.com/GAIR&#45;NLP/Preference&#45;Dissection"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'Reinforcement Learning', 'Responsible AI', 'Training Techniques']
---
As a relative quality comparison of model responses human and Large Language Model (LLM) preferences serve as common alignment goals in model fine45;tuning and criteria in evaluation. Yet these preferences merely reflect broad tendencies resulting in less explainable and controllable models with potential safety risks. In this work we dissect the preferences of human and 32 different LLMs to understand their quantitative composition using annotations from real45;world user45;model conversations for a fine45;grained scenario45;wise analysis. We find that humans are less sensitive to errors favor responses that support their stances and show clear dislike when models admit their limits. On the contrary advanced LLMs like GPT45;445;Turbo emphasize correctness clarity and harmlessness more. Additionally LLMs of similar sizes tend to exhibit similar preferences regardless of their training methods and fine45;tuning for alignment does not significantly alter the preferences of pretrained45;only LLMs. Finally we show that preference45;based evaluation can be intentionally manipulated. In both training45;free and training45;based settings aligning a model with the preferences of judges boosts scores while injecting the least preferred properties lowers them. This results in notable score shifts up to 0.59 on MT45;Bench (145;10 scale) and 31.94 on AlpacaEval 2.0 (045;100 scale) highlighting the significant impact of this strategic adaptation. Interactive Demo https://huggingface.co/spaces/GAIR/Preference&#45;Dissection&#45;Visualization Dataset https://huggingface.co/datasets/GAIR/preference&#45;dissection Code https://github.com/GAIR&#45;NLP/Preference&#45;Dissection
