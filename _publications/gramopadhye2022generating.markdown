---
layout: publication
title: Generating Executable Action Plans With Environmentally-aware Language Models
authors: Gramopadhye Maitrey, Szafir Daniel
conference: "Arxiv"
year: 2022
bibkey: gramopadhye2022generating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.04964"}
  - {name: "Code", url: "https://github.com/hri-ironlab/scene_aware_language_planner"}
tags: ['Agentic', 'Has Code', 'Pretraining Methods']
---
Large Language Models (LLMs) trained using massive text datasets have recently shown promise in generating action plans for robotic agents from high level text queries. However these models typically do not consider the robots environment resulting in generated plans that may not actually be executable due to ambiguities in the planned actions or environmental constraints. In this paper we propose an approach to generate environmentally-aware action plans that agents are better able to execute. Our approach involves integrating environmental objects and object relations as additional inputs into LLM action plan generation to provide the system with an awareness of its surroundings resulting in plans where each generated action is mapped to objects present in the scene. We also design a novel scoring function that along with generating the action steps and associating them with objects helps the system disambiguate among object instances and take into account their states. We evaluated our approach using the VirtualHome simulator and the ActivityPrograms knowledge base and found that action plans generated from our system had a 31037; improvement in executability and a 14737; improvement in correctness over prior work. The complete code and a demo of our method is publicly available at https://github.com/hri-ironlab/scene\_aware\_language\_planner.
