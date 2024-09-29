---
layout: publication
title: LGR2 Language Guided Reward Relabeling For Accelerating Hierarchical Reinforcement Learning
authors: Singh Utsav, Bhattacharyya Pramit, Namboodiri Vinay P.
conference: "Arxiv"
year: 2024
bibkey: singh2024lgr2
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.05881"}
tags: ['Agentic', 'Applications', 'Fine Tuning', 'In Context Learning', 'Prompting', 'RAG', 'Reinforcement Learning', 'Tools']
---
Developing interactive systems that leverage natural language instructions to solve complex robotic control tasks has been a long-desired goal in the robotics community. Large Language Models (LLMs) have demonstrated exceptional abilities in handling complex tasks including logical reasoning in-context learning and code generation. However predicting low-level robotic actions using LLMs poses significant challenges. Additionally the complexity of such tasks usually demands the acquisition of policies to execute diverse subtasks and combine them to attain the ultimate objective. Hierarchical Reinforcement Learning (HRL) is an elegant approach for solving such tasks which provides the intuitive benefits of temporal abstraction and improved exploration. However HRL faces the recurring issue of non-stationarity due to unstable lower primitive behaviour. In this work we propose LGR2 a novel HRL framework that leverages language instructions to generate a stationary reward function for the higher-level policy. Since the language-guided reward is unaffected by the lower primitive behaviour LGR2 mitigates non-stationarity and is thus an elegant method for leveraging language instructions to solve robotic control tasks. To analyze the efficacy of our approach we perform empirical analysis and demonstrate that LGR2 effectively alleviates non-stationarity in HRL. Our approach attains success rates exceeding 7037; in challenging sparse-reward robotic navigation and manipulation environments where the baselines fail to achieve any significant progress. Additionally we conduct real-world robotic manipulation experiments and demonstrate that CRISP shows impressive generalization in real-world scenarios.
