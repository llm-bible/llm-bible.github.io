---
layout: publication
title: An Empirical Analysis Of Compute45;optimal Inference For Problem45;solving With Language Models
authors: Yangzhen Wu, Zhiqing Sun, Shanda Li, Sean Welleck, Yiming Yang
conference: "Arxiv"
year: 2024
bibkey: wu2024empirical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2408.00724v1"}
tags: ['Efficiency And Optimization', 'Pretraining Methods', 'Training Techniques']
---
The optimal training configurations of large language models (LLMs) with respect to model sizes and compute budgets have been extensively studied. But how to optimally configure LLMs during inference has not been explored in sufficient depth. We study compute45;optimal inference designing models and inference strategies that optimally trade off additional inference45;time compute for improved performance. As a first step towards understanding and designing compute45;optimal inference methods we assessed the effectiveness and computational efficiency of multiple inference strategies such as Greedy Search Majority Voting Best45;of45;N Weighted Voting and their variants on two different Tree Search algorithms involving different model sizes and computational budgets. We found that a smaller language model with a novel tree search algorithm typically achieves a Pareto45;optimal trade45;off. These results highlight the potential benefits of deploying smaller models equipped with more sophisticated decoding algorithms in budget45;constrained scenarios e.g. on end45;devices to enhance problem45;solving accuracy. For instance we show that the Llemma45;7B model can achieve competitive accuracy to a Llemma45;34B model on MATH500 while using 2× less FLOPs. Our findings could potentially apply to any generation task with a well45;defined measure of success.
