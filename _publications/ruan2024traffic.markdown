---
layout: publication
title: 'Traffic Scene Generation From Natural Language Description For Autonomous Vehicles With Large Language Model'
authors: Bo-kai Ruan, Hao-tang Tsui, Yung-hui Li, Hong-han Shuai
conference: "Arxiv"
year: 2024
bibkey: ruan2024traffic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.09575"}
tags: ['Agentic', 'Tools', 'RAG', 'Reinforcement Learning', 'Prompting']
---
Text-to-scene generation typically limits environmental diversity by
generating key scenarios along predetermined paths. To address these
constraints, we propose a novel text-to-traffic scene framework that leverages
a large language model (LLM) to autonomously generate diverse traffic scenarios
for the CARLA simulator based on natural language descriptions. Our pipeline
comprises several key stages: (1) Prompt Analysis, where natural language
inputs are decomposed; (2) Road Retrieval, selecting optimal roads from a
database; (3) Agent Planning, detailing agent types and behaviors; (4) Road
Ranking, scoring roads to match scenario requirements; and (5) Scene
Generation, rendering the planned scenarios in the simulator. This framework
supports both routine and critical traffic scenarios, enhancing its
applicability. We demonstrate that our approach not only diversifies agent
planning and road selection but also significantly reduces the average
collision rate from 8% to 3.5% in SafeBench. Additionally, our framework
improves narration and reasoning for driving captioning tasks. Our
contributions and resources are publicly available at
https://basiclab.github.io/TTSG.
