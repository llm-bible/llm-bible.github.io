---
layout: publication
title: "Adapt: As-needed Decomposition And Planning With Language Models"
authors: Prasad Archiki, Koller Alexander, Hartmann Mareike, Clark Peter, Sabharwal Ashish, Bansal Mohit, Khot Tushar
conference: "Arxiv"
year: 2023
bibkey: prasad2023as
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.05772"}
tags: ['Agentic', 'Reinforcement Learning']
---
Large Language Models (LLMs) are increasingly being used for interactive decision-making tasks requiring planning and adapting to the environment. Recent works employ LLMs-as-agents in broadly two ways iteratively determining the next action (iterative executors) or generating plans and executing sub-tasks using LLMs (plan-and-execute). However these methods struggle with task complexity as the inability to execute any sub-task may lead to task failure. To address these shortcomings we introduce As-Needed Decomposition and Planning for complex Tasks (ADaPT) an approach that explicitly plans and decomposes complex sub-tasks as-needed i.e. when the LLM is unable to execute them. ADaPT recursively decomposes sub-tasks to adapt to both task complexity and LLM capability. Our results demonstrate that ADaPT substantially outperforms established strong baselines achieving success rates up to 28.337; higher in ALFWorld 2737; in WebShop and 3337; in TextCraft -- a novel compositional dataset that we introduce. Through extensive analysis we illustrate the importance of multilevel decomposition and establish that ADaPT dynamically adjusts to the capabilities of the executor LLM as well as to task complexity.
