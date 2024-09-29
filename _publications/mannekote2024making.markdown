---
layout: publication
title: Making Task-Oriented Dialogue Datasets More Natural by Synthetically Generating Indirect User Requests
authors: Mannekote Amogh, Nam Jinseok, Li Ziming, Gao Jian, Boyer Kristy Elizabeth, Dorr Bonnie J.
conference: "Arxiv"
year: 2024
bibkey: mannekote2024making
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.07794"}
tags: ['Applications', 'RAG', 'Reinforcement Learning']
---
Indirect User Requests (IURs) such as Its cold in here instead of Could you please increase the temperature are common in human-human task-oriented dialogue and require world knowledge and pragmatic reasoning from the listener. While large language models (LLMs) can handle these requests effectively smaller models deployed on virtual assistants often struggle due to resource constraints. Moreover existing task-oriented dialogue benchmarks lack sufficient examples of complex discourse phenomena such as indirectness. To address this we propose a set of linguistic criteria along with an LLM-based pipeline for generating realistic IURs to test natural language understanding (NLU) and dialogue state tracking (DST) models before deployment in a new domain. We also release IndirectRequests a dataset of IURs based on the Schema Guided Dialog (SGD) corpus as a comparative testbed for evaluating the performance of smaller models in handling indirect requests.
