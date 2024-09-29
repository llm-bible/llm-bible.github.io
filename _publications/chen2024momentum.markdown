---
layout: publication
title: Mofo Momentum45;filtered Optimizer For Mitigating Forgetting In LLM Fine45;tuning
authors: Chen Yupeng, Wang Senmiao, Lin Zhihang, Qin Zeyu, Zhang Yushun, Ding Tian, Sun Ruoyu
conference: "Arxiv"
year: 2024
bibkey: chen2024momentum
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.20999"}
tags: ['Efficiency And Optimization', 'Reinforcement Learning', 'Training Techniques']
---
Recently large language models (LLMs) have demonstrated remarkable capabilities in a wide range of tasks. Typically an LLM is pre45;trained on large corpora and subsequently fine45;tuned on task45;specific datasets. However during fine45;tuning LLMs may forget the knowledge acquired in the pre45;training stage leading to a decline in general capabilities. To address this issue we propose a new fine45;tuning algorithm termed Momentum45;Filtered Optimizer (MoFO). The key idea of MoFO is to iteratively select and update the model parameters with the largest momentum magnitudes. Compared to full45;parameter training MoFO achieves similar fine45;tuning performance while keeping parameters closer to the pre45;trained model thereby mitigating knowledge forgetting. Unlike most existing methods for forgetting mitigation MoFO combines the following two advantages. First MoFO does not require access to pre45;training data. This makes MoFO particularly suitable for fine45;tuning scenarios where pre45;training data is unavailable such as fine45;tuning checkpoint45;only open45;source LLMs. Second MoFO does not alter the original loss function. This could avoid impairing the model performance on the fine45;tuning tasks. We validate MoFO through rigorous convergence analysis and extensive experiments demonstrating its superiority over existing methods in mitigating forgetting and enhancing fine45;tuning performance.
