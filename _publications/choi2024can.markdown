---
layout: publication
title: Can only LLMs do Reasoning Potential of Small Language Models in Task Planning
authors: Choi Gawon, Ahn Hyemin
conference: "Arxiv"
year: 2024
bibkey: choi2024can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.03891"}
  - {name: "Code", url: "https://github.com/Gawon-Choi/small-LMs-Task-Planning"}
tags: ['ARXIV', 'Has Code', 'Pretraining Methods', 'Prompt', 'Tools']
---
In robotics the use of Large Language Models (LLMs) is becoming prevalent especially for understanding human commands. In particular LLMs are utilized as domain-agnostic task planners for high-level human commands. LLMs are capable of Chain-of-Thought (CoT) reasoning and this allows LLMs to be task planners. However we need to consider that modern robots still struggle to perform complex actions and the domains where robots can be deployed are limited in practice. This leads us to pose a question If small LMs can be trained to reason in chains within a single domain would even small LMs be good task planners for the robots To train smaller LMs to reason in chains we build COmmand-STeps datasets (COST) consisting of high-level commands along with corresponding actionable low-level steps via LLMs. We release not only our datasets but also the prompt templates used to generate them to allow anyone to build datasets for their domain. We compare GPT3.5 and GPT4 with the finetuned GPT2 for task domains in tabletop and kitchen environments and the result shows that GPT2-medium is comparable to GPT3.5 for task planning in a specific domain. Our dataset code and more output samples can be found in https://github.com/Gawon-Choi/small-LMs-Task-Planning
