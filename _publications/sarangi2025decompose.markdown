---
layout: publication
title: 'Decompose-tom: Enhancing Theory Of Mind Reasoning In Large Language Models Through Simulation And Task Decomposition'
authors: Sneheel Sarangi, Maha Elgarf, Hanan Salam
conference: "Arxiv"
year: 2025
bibkey: sarangi2025decompose
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.09056'}
tags: ['Reinforcement Learning', 'Prompting', 'Training Techniques']
---
Theory of Mind (ToM) is the ability to understand and reflect on the mental
states of others. Although this capability is crucial for human interaction,
testing on Large Language Models (LLMs) reveals that they possess only a
rudimentary understanding of it. Although the most capable closed-source LLMs
have come close to human performance on some ToM tasks, they still perform
poorly on complex variations of the task that involve more structured
reasoning. In this work, we utilize the concept of "pretend-play", or
``Simulation Theory'' from cognitive psychology to propose ``Decompose-ToM'':
an LLM-based inference algorithm that improves model performance on complex ToM
tasks. We recursively simulate user perspectives and decompose the ToM task
into a simpler set of functions: subject identification, question-reframing,
world model updation, and knowledge availability. We test the algorithm on
higher-order ToM tasks and a task testing for ToM capabilities in a
conversational setting, demonstrating that our approach shows significant
improvement across models compared to baseline methods while requiring minimal
prompt tuning across tasks and no additional model training.
