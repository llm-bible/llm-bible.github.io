---
layout: publication
title: 'Llm-based Open-domain Integrated Task And Knowledge Assistants With Programmable Policies'
authors: Joshi Harshit, Liu Shicheng, Chen James, Weigle Robert, Lam Monica S.
conference: "Arxiv"
year: 2024
bibkey: joshi2024llm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.05674"}
tags: ['Agentic', 'GPT', 'Model Architecture', 'Tools']
---
Programming LLM-based knowledge and task assistants that faithfully conform
to developer-provided policies is challenging. These agents must retrieve and
provide consistent, accurate, and relevant information to address user's
queries and needs. Yet such agents generate unfounded responses
("hallucinate"). Traditional dialogue trees can only handle a limited number of
conversation flows, making them inherently brittle. To this end, we present
KITA - a programmable framework for creating task-oriented conversational
agents that are designed to handle complex user interactions. Unlike LLMs, KITA
provides reliable grounded responses, with controllable agent policies through
its expressive specification, KITA Worksheet. In contrast to dialog trees, it
is resilient to diverse user queries, helpful with knowledge sources, and
offers ease of programming policies through its declarative paradigm. Through a
real-user study involving 62 participants, we show that KITA beats the GPT-4
with function calling baseline by 26.1, 22.5, and 52.4 points on execution
accuracy, dialogue act accuracy, and goal completion rate, respectively. We
also release 22 real-user conversations with KITA manually corrected to ensure
accuracy.
