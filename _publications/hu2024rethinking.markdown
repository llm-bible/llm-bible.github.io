---
layout: publication
title: Rethinking Llm-based Preference Evaluation
authors: Hu Zhengyu, Song Linxin, Zhang Jieyu, Xiao Zheyuan, Wang Jingang, Chen Zhenyu, Xiong Hui
conference: "Arxiv"
year: 2024
bibkey: hu2024rethinking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.01085"}
tags: ['Ethics And Bias', 'Reinforcement Learning', 'Training Techniques']
---
The use of large language model (LLM)-based preference evaluations has become widespread for comparing model responses but it has revealed a notable bias towards longer responses questioning the reliability of such evaluations. This paper explores the length bias in LLM evaluations from a data-centric perspective analyzing 14 commonly used preference datasets and 10 reward models. Our findings indicate that human preference labeling favors longer responses and this spurious correlation is learned by the reward model and subsequently propagated to the aligned model during training. We decompose the preference evaluation metric i.e. win rate from the perspective of human to identify the deeper factors and conclude that the win rate is affected by two axes of model response desirability and information mass where the former is length-independent and related to trustworthiness and the latter is length-dependent and can be represented by conditional entropy. Controlled experiments demonstrate that response length impacts evaluations by influencing information mass. To ensure reliable evaluation metrics that assess content quality without being confounded by response length we propose AdapAlpaca a simple yet effective adjustment to win rate measurement. Specifically by adjusting the lengths of reference answers to match the test models answers within the same interval we debias information mass relative to length ensuring a fair model evaluation. Furthermore we investigate length bias in DPO using AlpacaEval and AdapAlpaca. By testing Tulu2 and Tulu2-dpo at 7B 13B and 70B scales we found that DPO leads to higher human preference but this gain is amplified by response length with AlpacaEval showing higher win rates gain than AdapAlpaca.
