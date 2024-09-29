---
layout: publication
title: LLM Critics Help Catch LLM Bugs
authors: Mcaleese Nat, Pokorny Rai Michael, Uribe Juan Felipe Ceron, Nitishinskaya Evgenia, Trebacz Maja, Leike Jan
conference: "Arxiv"
year: 2024
bibkey: mcaleese2024llm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.00215"}
tags: ['Agentic', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'Survey Paper', 'Training Techniques']
---
Reinforcement learning from human feedback (RLHF) is fundamentally limited by the capacity of humans to correctly evaluate model output. To improve human evaluation ability and overcome that limitation this work trains critic models that help humans to more accurately evaluate model45;written code. These critics are themselves LLMs trained with RLHF to write natural language feedback highlighting problems in code from real45;world assistant tasks. On code containing naturally occurring LLM errors model45;written critiques are preferred over human critiques in 6337; of cases and human evaluation finds that models catch more bugs than human contractors paid for code review. We further confirm that our fine45;tuned LLM critics can successfully identify hundreds of errors in ChatGPT training data rated as flawless even though the majority of those tasks are non45;code tasks and thus out45;of45;distribution for the critic model. Critics can have limitations of their own including hallucinated bugs that could mislead humans into making mistakes they might have otherwise avoided but human45;machine teams of critics and contractors catch similar numbers of bugs to LLM critics while hallucinating less than LLMs alone.
