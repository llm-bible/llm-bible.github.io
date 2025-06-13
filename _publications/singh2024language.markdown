---
layout: publication
title: 'LGR2: Language Guided Reward Relabeling For Accelerating Hierarchical Reinforcement Learning'
authors: Utsav Singh, Pramit Bhattacharyya, Vinay P. Namboodiri
conference: "Arxiv"
year: 2024
bibkey: singh2024language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.05881"}
tags: ['Fine-Tuning', 'Agentic', 'Tools', 'Applications', 'Reinforcement Learning', 'Prompting', 'In-Context Learning']
---
Developing interactive systems that utilize natural language instructions to
solve complex robotic control tasks has long been a goal of the robotics
community. While Large Language Models (LLMs) excel at logical reasoning,
in-context learning, and code generation, translating high-level instructions
into low-level robotic actions still remains challenging. Furthermore, solving
such tasks often requires acquiring policies to execute diverse subtasks and
integrating them to achieve the final objective. Hierarchical Reinforcement
Learning (HRL) offers a promising solution for solving such tasks by enabling
temporal abstraction and improved exploration. However, HRL suffers from
non-stationarity caused by the changing lower-level behaviour, which hinders
effective policy learning. We propose LGR2, a novel HRL framework that
mitigates non-stationarity in HRL by using language-guided higher-level rewards
that remain unaffected by the changing lower-level policy behaviour. To analyze
the efficacy of our approach, we perform empirical analysis to demonstrate that
LGR2 effectively mitigates non-stationarity in HRL and attains success rates
exceeding 70% in challenging, sparsely-rewarded robotic navigation and
manipulation environments, where other baselines typically fail to show
significant progress. Finally, we perform real-world robotic experiments on
complex tasks and demonstrate that LGR2 consistently outperforms the baselines.
