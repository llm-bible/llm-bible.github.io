---
layout: publication
title: Small Llms Are Weak Tool Learners A Multi45;llm Agent
authors: Shen Weizhou, Li Chenliang, Chen Hongzhan, Yan Ming, Quan Xiaojun, Chen Hehong, Zhang Ji, Huang Fei
conference: "Arxiv"
year: 2024
bibkey: shen2024small
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.07324"}
tags: ['Agentic', 'Applications', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Large Language Model (LLM) agents significantly extend the capabilities of standalone LLMs empowering them to interact with external tools (e.g. APIs functions) and complete various tasks in a self45;directed fashion. The challenge of tool use demands that LLMs not only understand user queries and generate answers accurately but also excel in task planning tool invocation and result summarization. While traditional works focus on training a single LLM with all these capabilities performance limitations become apparent particularly with smaller models. To overcome these challenges we propose a novel approach that decomposes the aforementioned capabilities into a planner caller and summarizer. Each component is implemented by a single LLM that focuses on a specific capability and collaborates with others to accomplish the task. This modular framework facilitates individual updates and the potential use of smaller LLMs for building each capability. To effectively train this framework we introduce a two45;stage training paradigm. First we fine45;tune a backbone LLM on the entire dataset without discriminating sub45;tasks providing the model with a comprehensive understanding of the task. Second the fine45;tuned LLM is used to instantiate the planner caller and summarizer respectively which are continually fine45;tuned on respective sub45;tasks. Evaluation across various tool45;use benchmarks illustrates that our proposed multi45;LLM framework surpasses the traditional single45;LLM approach highlighting its efficacy and advantages in tool learning.
