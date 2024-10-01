---
layout: publication
title: 'Deploying And Evaluating Llms To Program Service Mobile Robots'
authors: Hu Zichao, Lucchetti Francesca, Schlesinger Claire, Saxena Yash, Freeman Anders, Modak Sadanand, Guha Arjun, Biswas Joydeep
conference: "IEEE Robotics and Automation Letters vol."
year: 2023
bibkey: hu2023deploying
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.11183"}
  - {name: "Code", url: "https://amrl.cs.utexas.edu/codebotler/"}
tags: ['Few Shot', 'Has Code', 'In Context Learning', 'Prompting', 'RAG', 'Reinforcement Learning', 'Security']
---
"Recent advancements in large language models (LLMs) have spurred interest in using them for generating robot programs from natural language, with promising initial results. We investigate the use of LLMs to generate programs for service mobile robots leveraging mobility, perception, and human interaction skills, and where accurate sequencing and ordering of actions is crucial for success. We contribute CodeBotler, an open-source robot-agnostic tool to program service mobile robots from natural language, and RoboEval, a benchmark for evaluating LLMs' capabilities of generating programs to complete service robot tasks. CodeBotler performs program generation via few-shot prompting of LLMs with an embedded domain-specific language (eDSL) in Python, and leverages skill abstractions to deploy generated programs on any general-purpose mobile robot. RoboEval evaluates the correctness of generated programs by checking execution traces starting with multiple initial states, and checking whether the traces satisfy temporal logic properties that encode correctness for each task. RoboEval also includes multiple prompts per task to test for the robustness of program generation. We evaluate several popular state-of-the-art LLMs with the RoboEval benchmark, and perform a thorough analysis of the modes of failures, resulting in a taxonomy that highlights common pitfalls of LLMs at generating robot programs. We release our code and benchmark at https://amrl.cs.utexas.edu/codebotler/."
