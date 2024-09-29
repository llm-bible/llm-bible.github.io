---
layout: publication
title: Is Self45;repair A Silver Bullet For Code Generation
authors: Olausson Theo X., Inala Jeevana Priya, Wang Chenglong, Gao Jianfeng, Solar-lezama Armando
conference: "Arxiv"
year: 2023
bibkey: olausson2023is
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.09896"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Reinforcement Learning']
---
Large language models have shown remarkable aptitude in code generation but still struggle to perform complex tasks. Self45;repair 45;45; in which the model debugs and repairs its own code 45;45; has recently become a popular way to boost performance in these settings. However despite its increasing popularity existing studies of self45;repair have been limited in scope; in many settings its efficacy thus remains poorly understood. In this paper we analyze Code Llama GPT45;3.5 and GPT45;4s ability to perform self45;repair on problems taken from HumanEval and APPS. We find that when the cost of carrying out repair is taken into account performance gains are often modest vary a lot between subsets of the data and are sometimes not present at all. We hypothesize that this is because self45;repair is bottlenecked by the models ability to provide feedback on its own code; using a stronger model to artificially boost the quality of the feedback we observe substantially larger performance gains. Similarly a small45;scale study in which we provide GPT45;4 with feedback from human participants suggests that even for the strongest models self45;repair still lags far behind what can be achieved with human45;level debugging.
