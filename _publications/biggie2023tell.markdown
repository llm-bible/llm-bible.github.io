---
layout: publication
title: Tell Me Where To Go A Composable Framework For Context-aware Embodied Robot Navigation
authors: Biggie Harel, Mopidevi Ajay Narasimha, Woods Dusty, Heckman Christoffer
conference: "Arxiv"
year: 2023
bibkey: biggie2023tell
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.09523"}
tags: ['Multimodal Models', 'Reinforcement Learning', 'Tools']
---
Humans have the remarkable ability to navigate through unfamiliar environments by solely relying on our prior knowledge and descriptions of the environment. For robots to perform the same type of navigation they need to be able to associate natural language descriptions with their associated physical environment with a limited amount of prior knowledge. Recently Large Language Models (LLMs) have been able to reason over billions of parameters and utilize them in multi-modal chat-based natural language responses. However LLMs lack real-world awareness and their outputs are not always predictable. In this work we develop NavCon a low-bandwidth framework that solves this lack of real-world generalization by creating an intermediate layer between an LLM and a robot navigation framework in the form of Python code. Our intermediate shoehorns the vast prior knowledge inherent in an LLM model into a series of input and output API instructions that a mobile robot can understand. We evaluate our method across four different environments and command classes on a mobile robot and highlight our NavCons ability to interpret contextual commands.
