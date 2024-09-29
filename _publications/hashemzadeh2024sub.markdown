---
layout: publication
title: Sub45;goal Distillation A Method To Improve Small Language Agents
authors: Hashemzadeh Maryam, Stengel-eskin Elias, Chandar Sarath, Cote Marc-alexandre
conference: "Arxiv"
year: 2024
bibkey: hashemzadeh2024sub
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.02749"}
tags: ['Agentic', 'Distillation', 'Efficiency And Optimization', 'RAG', 'Reinforcement Learning']
---
While Large Language Models (LLMs) have demonstrated significant promise as agents in interactive tasks their substantial computational requirements and restricted number of calls constrain their practical utility especially in long45;horizon interactive tasks such as decision45;making or in scenarios involving continuous ongoing tasks. To address these constraints we propose a method for transferring the performance of an LLM with billions of parameters to a much smaller language model (770M parameters). Our approach involves constructing a hierarchical agent comprising a planning module which learns through Knowledge Distillation from an LLM to generate sub45;goals and an execution module which learns to accomplish these sub45;goals using elementary actions. In detail we leverage an LLM to annotate an oracle path with a sequence of sub45;goals towards completing a goal. Subsequently we utilize this annotated data to fine45;tune both the planning and execution modules. Importantly neither module relies on real45;time access to an LLM during inference significantly reducing the overall cost associated with LLM interactions to a fixed cost. In ScienceWorld a challenging and multi45;task interactive text environment our method surpasses standard imitation learning based solely on elementary actions by 16.737; (absolute). Our analysis highlights the efficiency of our approach compared to other LLM45;based methods. Our code and annotated data for distillation can be found on GitHub.
