---
layout: publication
title: PIP Parse45;instructed Prefix For Syntactically Controlled Paraphrase Generation
authors: Wan Yixin, Huang Kuan-hao, Chang Kai-wei
conference: "Arxiv"
year: 2023
bibkey: wan2023parse
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.16701"}
tags: ['Applications', 'Efficiency And Optimization', 'Training Techniques']
---
Syntactically controlled paraphrase generation requires language models to generate paraphrases for sentences according to specific syntactic structures. Existing fine45;tuning methods for this task are costly as all the parameters of the model need to be updated during the training process. Inspired by recent studies on parameter45;efficient learning we propose Parse45;Instructed Prefix (PIP) a novel adaptation of prefix45;tuning to tune large pre45;trained language models on syntactically controlled paraphrase generation task in a low45;data setting with significantly less training cost. We introduce two methods to instruct a models encoder prefix to capture syntax45;related knowledge direct initiation (PIP45;Direct) and indirect optimization (PIP45;Indirect). In contrast to traditional fine45;tuning methods for this task PIP is a compute45;efficient alternative with 10 times less learnable parameters. Compared to existing prefix45;tuning methods PIP excels at capturing syntax control information achieving significantly higher performance at the same level of learnable parameter count.
