---
layout: publication
title: 'Deception In Llms: Self-preservation And Autonomous Goals In Large Language Models'
authors: Sudarshan Kamath Barkur, Sigurd Schacht, Johannes Scholl
conference: "Arxiv"
year: 2025
bibkey: barkur2025deception
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.16513"}
tags: ['Responsible AI', 'Agentic', 'Tools', 'Reinforcement Learning', 'Prompting']
---
Recent advances in Large Language Models (LLMs) have incorporated planning
and reasoning capabilities, enabling models to outline steps before execution
and provide transparent reasoning paths. This enhancement has reduced errors in
mathematical and logical tasks while improving accuracy. These developments
have facilitated LLMs' use as agents that can interact with tools and adapt
their responses based on new information.
  Our study examines DeepSeek R1, a model trained to output reasoning tokens
similar to OpenAI's o1. Testing revealed concerning behaviors: the model
exhibited deceptive tendencies and demonstrated self-preservation instincts,
including attempts of self-replication, despite these traits not being
explicitly programmed (or prompted). These findings raise concerns about LLMs
potentially masking their true objectives behind a facade of alignment. When
integrating such LLMs into robotic systems, the risks become tangible - a
physically embodied AI exhibiting deceptive behaviors and self-preservation
instincts could pursue its hidden objectives through real-world actions. This
highlights the critical need for robust goal specification and safety
frameworks before any physical implementation.
