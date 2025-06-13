---
layout: publication
title: 'Text2world: Benchmarking Large Language Models For Symbolic World Model Generation'
authors: Mengkang Hu, Tianxing Chen, Yude Zou, Yuheng Lei, Qiguang Chen, Ming Li, Yao Mu, Hongyuan Zhang, Wenqi Shao, Ping Luo
conference: "Arxiv"
year: 2025
bibkey: hu2025benchmarking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.13092"}
tags: ['Agentic', 'RAG', 'Training Techniques', 'Reinforcement Learning']
---
Recently, there has been growing interest in leveraging large language models
(LLMs) to generate symbolic world models from textual descriptions. Although
LLMs have been extensively explored in the context of world modeling, prior
studies encountered several challenges, including evaluation randomness,
dependence on indirect metrics, and a limited domain scope. To address these
limitations, we introduce a novel benchmark, Text2World, based on planning
domain definition language (PDDL), featuring hundreds of diverse domains and
employing multi-criteria, execution-based metrics for a more robust evaluation.
We benchmark current LLMs using Text2World and find that reasoning models
trained with large-scale reinforcement learning outperform others. However,
even the best-performing model still demonstrates limited capabilities in world
modeling. Building on these insights, we examine several promising strategies
to enhance the world modeling capabilities of LLMs, including test-time
scaling, agent training, and more. We hope that Text2World can serve as a
crucial resource, laying the groundwork for future research in leveraging LLMs
as world models. The project page is available at
https://text-to-world.github.io/.
