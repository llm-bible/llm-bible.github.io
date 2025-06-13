---
layout: publication
title: 'From Words To Collisions: Llm-guided Evaluation And Adversarial Generation Of Safety-critical Driving Scenarios'
authors: Yuan Gao, Mattia Piccinini, Korbinian Moller, Amr Alanwar, Johannes Betz
conference: "Arxiv"
year: 2025
bibkey: gao2025from
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.02145"}
  - {name: "Code", url: "https://github.com/TUM-AVS/From-Words-to-Collisions"}
tags: ['Responsible AI', 'Agentic', 'Security', 'Tools', 'Has Code', 'Prompting']
---
Ensuring the safety of autonomous vehicles requires virtual scenario-based testing, which depends on the robust evaluation and generation of safety-critical scenarios. So far, researchers have used scenario-based testing frameworks that rely heavily on handcrafted scenarios as safety metrics. To reduce the effort of human interpretation and overcome the limited scalability of these approaches, we combine Large Language Models (LLMs) with structured scenario parsing and prompt engineering to automatically evaluate and generate safety-critical driving scenarios. We introduce Cartesian and Ego-centric prompt strategies for scenario evaluation, and an adversarial generation module that modifies trajectories of risk-inducing vehicles (ego-attackers) to create critical scenarios. We validate our approach using a 2D simulation framework and multiple pre-trained LLMs. The results show that the evaluation module effectively detects collision scenarios and infers scenario safety. Meanwhile, the new generation module identifies high-risk agents and synthesizes realistic, safety-critical scenarios. We conclude that an LLM equipped with domain-informed prompting techniques can effectively evaluate and generate safety-critical driving scenarios, reducing dependence on handcrafted metrics. We release our open-source code and scenarios at: https://github.com/TUM-AVS/From-Words-to-Collisions.
