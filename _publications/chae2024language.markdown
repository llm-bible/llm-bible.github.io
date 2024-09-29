---
layout: publication
title: 'Language Models As Compilers: Simulating Pseudocode Execution Improves Algorithmic Reasoning In Language Models'
authors: Chae Hyungjoo, Kim Yeonghyeon, Kim Seungone, Ong Kai Tzu-iunn, Kwak Beong-woo, Kim Moohyeon, Kim Seonghwan, Kwon Taeyoon, Chung Jiwan, Yu Youngjae, Yeo Jinyoung
conference: "Arxiv"
year: 2024
bibkey: chae2024language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.02575"}
tags: ['Ethics And Bias', 'Tools']
---
Algorithmic reasoning refers to the ability to understand the complex patterns behind the problem and decompose them into a sequence of reasoning steps towards the solution. Such nature of algorithmic reasoning makes it a challenge for large language models (LLMs) even though they have demonstrated promising performance in other reasoning tasks. Within this context some recent studies use programming languages (e.g. Python) to express the necessary logic for solving a given instance/question (e.g. Program-of-Thought) as inspired by their strict and precise syntaxes. However it is non-trivial to write an executable code that expresses the correct logic on the fly within a single inference call. Also the code generated specifically for an instance cannot be reused for others even if they are from the same task and might require identical logic to solve. This paper presents Think-and-Execute a novel framework that decomposes the reasoning process of language models into two steps. (1) In Think we discover a task-level logic that is shared across all instances for solving a given task and then express the logic with pseudocode; (2) In Execute we further tailor the generated pseudocode to each instance and simulate the execution of the code. With extensive experiments on seven algorithmic reasoning tasks we demonstrate the effectiveness of Think-and-Execute. Our approach better improves LMs reasoning compared to several strong baselines performing instance-specific reasoning (e.g. CoT and PoT) suggesting the helpfulness of discovering task-level logic. Also we show that compared to natural language pseudocode can better guide the reasoning of LMs even though they are trained to follow natural language instructions.
