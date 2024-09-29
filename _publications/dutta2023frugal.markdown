---
layout: publication
title: Frugal Lms Trained To Invoke Symbolic Solvers Achieve Parameter45;efficient Arithmetic Reasoning
authors: Dutta Subhabrata, Singh Joykirat, Pandey Ishan, Manchanda Sunny, Chakrabarti Soumen, Chakraborty Tanmoy
conference: "Arxiv"
year: 2023
bibkey: dutta2023frugal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.05571"}
tags: ['Agentic', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'Tools']
---
Large Language Models (LLM) exhibit zero45;shot mathematical reasoning capacity as a behavior emergent with scale commonly manifesting as chain45;of45;thoughts (CoT) reasoning. However multiple empirical findings suggest that this prowess is exclusive to LLMs with exorbitant sizes (beyond 50 billion parameters). Meanwhile educational neuroscientists suggest that symbolic algebraic manipulation be introduced around the same time as arithmetic word problems to modularize language45;to45;formulation symbolic manipulation of the formulation and endgame arithmetic. In this paper we start with the hypothesis that much smaller LMs which are weak at multi45;step reasoning can achieve reasonable arithmetic reasoning if arithmetic word problems are posed as a formalize45;then45;solve task. In our architecture which we call SYRELM the LM serves the role of a translator to map natural language arithmetic questions into a formal language (FL) description. A symbolic solver then evaluates the FL expression to obtain the answer. A small frozen LM equipped with an efficient low45;rank adapter is capable of generating FL expressions that incorporate natural language descriptions of the arithmetic problem (e.g. variable names and their purposes formal expressions combining variables etc.). We adopt policy45;gradient reinforcement learning to train the adapted LM informed by the non45;differentiable symbolic solver. This marks a sharp departure from the recent development in tool45;augmented LLMs in which the external tools (e.g. calculator Web search etc.) are essentially detached from the learning phase of the LM. SYRELM shows massive improvements (e.g. +30.65 absolute point improvement in accuracy on the SVAMP dataset using GPT45;J 6B model) over base LMs while keeping our testbed easy to diagnose interpret and within reach of most researchers.
