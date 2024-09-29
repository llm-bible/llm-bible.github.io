---
layout: publication
title: Reprompt&#58; Planning By Automatic Prompt Engineering For Large Language Models Agents
authors: Chen Weizhe, Koenig Sven, Dilkina Bistra
conference: "Arxiv"
year: 2024
bibkey: chen2024planning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.11132"}
tags: ['Agentic', 'Applications', 'Prompting', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
In this past year large language models (LLMs) have had remarkable success in domains outside the traditional natural language processing and people are starting to explore the usage of LLMs in more general and close to application domains like code generation travel planning and robot controls. Connecting these LLMs with great capacity and external tools people are building the so-called LLM agents which are supposed to help people do all kinds of work in everyday life. In all these domains the prompt to the LLMs has been shown to make a big difference in what the LLM would generate and thus affect the performance of the LLM agents. Therefore automatic prompt engineering has become an important question for many researchers and users of LLMs. In this paper we propose a novel method (textscRePrompt) which does gradient descent to optimize the step-by-step instructions in the prompt of the LLM agents based on the chat history obtained from interactions with LLM agents. By optimizing the prompt the LLM will learn how to plan in specific domains. We have used experiments in PDDL generation and travel planning to show that our method could generally improve the performance for different reasoning tasks when using the updated prompt as the initial prompt.
