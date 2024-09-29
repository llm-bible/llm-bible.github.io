---
layout: publication
title: Mofo Momentum-filtered Optimizer For Mitigating Forgetting In LLM Fine-tuning
authors: Chen Yupeng, Wang Senmiao, Lin Zhihang, Qin Zeyu, Zhang Yushun, Ding Tian, Sun Ruoyu
conference: "Arxiv"
year: 2024
bibkey: chen2024momentum
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.20999"}
tags: ['Fine Tuning', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
Recently large language models (LLMs) have demonstrated remarkable capabilities in a wide range of tasks. Typically an LLM is pre-trained on large corpora and subsequently fine-tuned on task-specific datasets. However during fine-tuning LLMs may forget the knowledge acquired in the pre-training stage leading to a decline in general capabilities. To address this issue we propose a new fine-tuning algorithm termed Momentum-Filtered Optimizer (MoFO). The key idea of MoFO is to iteratively select and update the model parameters with the largest momentum magnitudes. Compared to full-parameter training MoFO achieves similar fine-tuning performance while keeping parameters closer to the pre-trained model thereby mitigating knowledge forgetting. Unlike most existing methods for forgetting mitigation MoFO combines the following two advantages. First MoFO does not require access to pre-training data. This makes MoFO particularly suitable for fine-tuning scenarios where pre-training data is unavailable such as fine-tuning checkpoint-only open-source LLMs. Second MoFO does not alter the original loss function. This could avoid impairing the model performance on the fine-tuning tasks. We validate MoFO through rigorous convergence analysis and extensive experiments demonstrating its superiority over existing methods in mitigating forgetting and enhancing fine-tuning performance.
