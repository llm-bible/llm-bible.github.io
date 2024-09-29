---
layout: publication
title: Learning Reward For Robot Skills Using Large Language Models Via Self45;alignment
authors: Zeng Yuwei, Mu Yao, Shao Lin
conference: "Arxiv"
year: 2024
bibkey: zeng2024learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.07162"}
tags: ['Efficiency And Optimization', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques']
---
Learning reward functions remains the bottleneck to equip a robot with a broad repertoire of skills. Large Language Models (LLM) contain valuable task45;related knowledge that can potentially aid in the learning of reward functions. However the proposed reward function can be imprecise thus ineffective which requires to be further grounded with environment information. We proposed a method to learn rewards more efficiently in the absence of humans. Our approach consists of two components We first use the LLM to propose features and parameterization of the reward then update the parameters through an iterative self45;alignment process. In particular the process minimizes the ranking inconsistency between the LLM and the learnt reward functions based on the execution feedback. The method was validated on 9 tasks across 2 simulation environments. It demonstrates a consistent improvement over training efficacy and efficiency meanwhile consuming significantly fewer GPT tokens compared to the alternative mutation45;based method.
