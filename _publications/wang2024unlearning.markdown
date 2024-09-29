---
layout: publication
title: Unlearning With Control: Assessing Real-world Utility For Large Language Model Unlearning
authors: Wang Qizhou, Han Bo, Yang Puning, Zhu Jianing, Liu Tongliang, Sugiyama Masashi
conference: "Arxiv"
year: 2024
bibkey: wang2024unlearning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.09179"}
tags: ['Efficiency And Optimization', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
The compelling goal of eradicating undesirable data behaviors while preserving usual model functioning underscores the significance of machine unlearning within the domain of large language models (LLMs). Recent research has begun to approach LLM unlearning via gradient ascent (GA) -- increasing the prediction risk for those training strings targeted to be unlearned thereby erasing their parameterized responses. Despite their simplicity and efficiency we suggest that GA-based methods face the propensity towards excessive unlearning resulting in various undesirable model behaviors such as catastrophic forgetting that diminish their practical utility. In this paper we suggest a set of metrics that can capture multiple facets of real-world utility and propose several controlling methods that can regulate the extent of excessive unlearning. Accordingly we suggest a general framework to better reflect the practical efficacy of various unlearning methods -- we begin by controlling the unlearning procedures/unlearned models such that no excessive unlearning occurs and follow by the evaluation for unlearning efficacy. Our experimental analysis on established benchmarks revealed that GA-based methods are far from perfect in practice as strong unlearning is at the high cost of hindering the model utility. We conclude that there is still a long way towards practical and effective LLM unlearning and more efforts are required in this field.
