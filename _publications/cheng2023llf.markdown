---
layout: publication
title: 'Llf-bench: Benchmark For Interactive Learning From Language Feedback'
authors: Cheng Ching-an, Kolobov Andrey, Misra Dipendra, Nie Allen, Swaminathan Adith
conference: "Arxiv"
year: 2023
bibkey: cheng2023llf
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.06853"}
tags: ['Agentic', 'Applications', 'Interpretability And Explainability', 'Reinforcement Learning', 'Tools']
---
We introduce a new benchmark, LLF-Bench (Learning from Language Feedback
Benchmark; pronounced as "elf-bench"), to evaluate the ability of AI agents to
interactively learn from natural language feedback and instructions. Learning
from language feedback (LLF) is essential for people, largely because the rich
information this feedback provides can help a learner avoid much of trial and
error and thereby speed up the learning process. Large Language Models (LLMs)
have recently enabled AI agents to comprehend natural language -- and hence AI
agents can potentially benefit from language feedback during learning like
humans do. But existing interactive benchmarks do not assess this crucial
capability: they either use numeric reward feedback or require no learning at
all (only planning or information retrieval). LLF-Bench is designed to fill
this omission. LLF-Bench is a diverse collection of sequential decision-making
tasks that includes user recommendation, poem writing, navigation, and robot
control. The objective of an agent is to interactively solve these tasks based
on their natural-language instructions and the feedback received after taking
actions. Crucially, to ensure that the agent actually "learns" from the
feedback, LLF-Bench implements several randomization techniques (such as
paraphrasing and environment randomization) to ensure that the task isn't
familiar to the agent and that the agent is robust to various verbalizations.
In addition, LLF-Bench provides a unified OpenAI Gym interface for all its
tasks and allows the users to easily configure the information the feedback
conveys (among suggestion, explanation, and instantaneous performance) to study
how agents respond to different types of feedback. Together, these features
make LLF-Bench a unique research platform for developing and testing LLF
agents.
