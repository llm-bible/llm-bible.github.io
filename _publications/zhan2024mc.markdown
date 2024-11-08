---
layout: publication
title: 'MC-GPT: Empowering Vision-and-language Navigation With Memory Map And Reasoning Chains'
authors: Zhan Zhaohuan, Yu Lisha, Yu Sijie, Tan Guang
conference: "Arxiv"
year: 2024
bibkey: zhan2024mc
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.10620"}
tags: ['Agentic', 'GPT', 'Interpretability And Explainability', 'Model Architecture', 'RAG', 'Training Techniques']
---
In the Vision-and-Language Navigation (VLN) task, the agent is required to
navigate to a destination following a natural language instruction. While
learning-based approaches have been a major solution to the task, they suffer
from high training costs and lack of interpretability. Recently, Large Language
Models (LLMs) have emerged as a promising tool for VLN due to their strong
generalization capabilities. However, existing LLM-based methods face
limitations in memory construction and diversity of navigation strategies. To
address these challenges, we propose a suite of techniques. Firstly, we
introduce a method to maintain a topological map that stores navigation
history, retaining information about viewpoints, objects, and their spatial
relationships. This map also serves as a global action space. Additionally, we
present a Navigation Chain of Thoughts module, leveraging human navigation
examples to enrich navigation strategy diversity. Finally, we establish a
pipeline that integrates navigational memory and strategies with perception and
action prediction modules. Experimental results on the REVERIE and R2R datasets
show that our method effectively enhances the navigation ability of the LLM and
improves the interpretability of navigation reasoning.
