---
layout: publication
title: 'Insta: Towards Internet-scale Training For Agents'
authors: Brandon Trabucco, Gunnar Sigurdsson, Robinson Piramuthu, Ruslan Salakhutdinov
conference: "Arxiv"
year: 2025
bibkey: trabucco2025towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.06776"}
  - {name: "Code", url: "https://data-for-agents.github.io"}
tags: ['Agentic', 'Training Techniques', 'Has Code', 'Tools']
---
The predominant approach for training web navigation agents is to gather human demonstrations for a set of popular websites and hand-written tasks, but it is becoming clear that human data is an inefficient resource. We develop a pipeline to facilitate internet-scale training for agents without laborious human annotations. In the first stage, an LLM annotates 150k sites with agentic tasks. In the next stage, LLM agents complete tasks and produce trajectories. In the final stage, an LLM filters trajectories by judging their success. Language models are powerful data curation tools, identifying harmful content with an accuracy of 97%, judging successful trajectories with an accuracy of 82.6%, and producing effective data. We train agents based on Qwen 3 1.7B that are competitive with frontier LLMs as web agents, while being smaller and faster. Our top agent reaches a success rate of 56.9%, outperforming the data collection policy Qwen 3 235B, a 235 times larger Llama 4 Maverick, and reaching 94.7% of the performance of Gemini 2.5 Flash. We are releasing code, models and data at: https://data-for-agents.github.io.
