---
layout: publication
title: Inner Monologue Embodied Reasoning through Planning with Language Models
authors: Huang Wenlong, Xia Fei, Xiao Ted, Chan Harris, Liang Jacky, Florence Pete, Zeng Andy, Tompson Jonathan, Mordatch Igor, Chebotar Yevgen, Sermanet Pierre, Brown Noah, Jackson Tomas, Luu Linda, Levine Sergey, Hausman Karol, Ichter Brian
conference: "Arxiv"
year: 2022
bibkey: huang2022inner
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2207.05608"}
tags: ['Agentic', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Recent works have shown how the reasoning capabilities of Large Language Models (LLMs) can be applied to domains beyond natural language processing such as planning and interaction for robots. These embodied problems require an agent to understand many semantic aspects of the world the repertoire of skills available how these skills influence the world and how changes to the world map back to the language. LLMs planning in embodied environments need to consider not just what skills to do but also how and when to do them - answers that change over time in response to the agents own choices. In this work we investigate to what extent LLMs used in such embodied contexts can reason over sources of feedback provided through natural language without any additional training. We propose that by leveraging environment feedback LLMs are able to form an inner monologue that allows them to more richly process and plan in robotic control scenarios. We investigate a variety of sources of feedback such as success detection scene description and human interaction. We find that closed-loop language feedback significantly improves high-level instruction completion on three domains including simulated and real table top rearrangement tasks and long-horizon mobile manipulation tasks in a kitchen environment in the real world.
