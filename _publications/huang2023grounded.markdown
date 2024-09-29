---
layout: publication
title: Grounded Decoding Guiding Text Generation With Grounded Models For Embodied Agents
authors: Huang Wenlong, Xia Fei, Shah Dhruv, Driess Danny, Zeng Andy, Lu Yao, Florence Pete, Mordatch Igor, Levine Sergey, Hausman Karol, Ichter Brian
conference: "Arxiv"
year: 2023
bibkey: huang2023grounded
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2303.00855"}
tags: ['Agentic', 'Applications', 'GPT', 'Language Modeling', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Responsible AI', 'Training Techniques']
---
Recent progress in large language models (LLMs) has demonstrated the ability to learn and leverage Internet45;scale knowledge through pre45;training with autoregressive models. Unfortunately applying such models to settings with embodied agents such as robots is challenging due to their lack of experience with the physical world inability to parse non45;language observations and ignorance of rewards or safety constraints that robots may require. On the other hand language45;conditioned robotic policies that learn from interaction data can provide the necessary grounding that allows the agent to be correctly situated in the real world but such policies are limited by the lack of high45;level semantic understanding due to the limited breadth of the interaction data available for training them. Thus if we want to make use of the semantic knowledge in a language model while still situating it in an embodied setting we must construct an action sequence that is both likely according to the language model and also realizable according to grounded models of the environment. We frame this as a problem similar to probabilistic filtering decode a sequence that both has high probability under the language model and high probability under a set of grounded model objectives. We demonstrate how such grounded models can be obtained across three simulation and real45;world domains and that the proposed decoding strategy is able to solve complex long45;horizon embodiment tasks in a robotic setting by leveraging the knowledge of both models. The projects website can be found at grounded45;decoding.github.io.
