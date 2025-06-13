---
layout: publication
title: 'Remembr: Building And Reasoning Over Long-horizon Spatio-temporal Memory For Robot Navigation'
authors: Abrar Anwar, John Welsh, Joydeep Biswas, Soha Pouya, Yan Chang
conference: "Arxiv"
year: 2024
bibkey: anwar2024building
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.13682"}
  - {name: "Code", url: "https://nvidia-ai-iot.github.io/remembr"}
tags: ['RAG', 'Has Code', 'Applications']
---
Navigating and understanding complex environments over extended periods of
time is a significant challenge for robots. People interacting with the robot
may want to ask questions like where something happened, when it occurred, or
how long ago it took place, which would require the robot to reason over a long
history of their deployment. To address this problem, we introduce a
Retrieval-augmented Memory for Embodied Robots, or ReMEmbR, a system designed
for long-horizon video question answering for robot navigation. To evaluate
ReMEmbR, we introduce the NaVQA dataset where we annotate spatial, temporal,
and descriptive questions to long-horizon robot navigation videos. ReMEmbR
employs a structured approach involving a memory building and a querying phase,
leveraging temporal information, spatial information, and images to efficiently
handle continuously growing robot histories. Our experiments demonstrate that
ReMEmbR outperforms LLM and VLM baselines, allowing ReMEmbR to achieve
effective long-horizon reasoning with low latency. Additionally, we deploy
ReMEmbR on a robot and show that our approach can handle diverse queries. The
dataset, code, videos, and other material can be found at the following link:
https://nvidia-ai-iot.github.io/remembr
