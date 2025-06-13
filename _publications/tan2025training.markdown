---
layout: publication
title: 'Aurora:automated Training Framework Of Universal Process Reward Models Via Ensemble Prompting And Reverse Verification'
authors: Xiaoyu Tan, Tianchu Yao, Chao Qu, Bin Li, Minghao Yang, Dakuan Lu, Haozhe Wang, Xihe Qiu, Wei Chu, Yinghui Xu, Yuan Qi
conference: "Arxiv"
year: 2025
bibkey: tan2025training
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.11520'}
tags: ['RAG', 'Training Techniques', 'Applications', 'Tools', 'Prompting', 'Reinforcement Learning']
---
The reasoning capabilities of advanced large language models (LLMs) like o1
have revolutionized artificial intelligence applications. Nevertheless,
evaluating and optimizing complex reasoning processes remain significant
challenges due to diverse policy distributions and the inherent limitations of
human effort and accuracy. In this paper, we present AURORA, a novel automated
framework for training universal process reward models (PRMs) using ensemble
prompting and reverse verification. The framework employs a two-phase approach:
First, it uses diverse prompting strategies and ensemble methods to perform
automated annotation and evaluation of processes, ensuring robust assessments
for reward learning. Second, it leverages practical reference answers for
reverse verification, enhancing the model's ability to validate outputs and
improving training accuracy. To assess the framework's performance, we extend
beyond the existing ProcessBench benchmark by introducing UniversalBench, which
evaluates reward predictions across full trajectories under diverse policy
distribtion with long Chain-of-Thought (CoT) outputs. Experimental results
demonstrate that AURORA enhances process evaluation accuracy, improves PRMs'
accuracy for diverse policy distributions and long-CoT responses. The project
will be open-sourced at https://auroraprm.github.io/. The Universal-PRM-7B is
available at https://huggingface.co/infly/Universal-PRM-7B.
