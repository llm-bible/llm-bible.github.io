---
layout: publication
title: 'Making Task-oriented Dialogue Datasets More Natural By Synthetically Generating Indirect User Requests'
authors: Amogh Mannekote, Jinseok Nam, Ziming Li, Jian Gao, Kristy Elizabeth Boyer, Bonnie J. Dorr
conference: "Arxiv"
year: 2024
bibkey: mannekote2024making
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.07794"}
tags: ['RAG', 'Applications', 'Reinforcement Learning']
---
Indirect User Requests (IURs), such as "It's cold in here" instead of "Could
you please increase the temperature?" are common in human-human task-oriented
dialogue and require world knowledge and pragmatic reasoning from the listener.
While large language models (LLMs) can handle these requests effectively,
smaller models deployed on virtual assistants often struggle due to resource
constraints. Moreover, existing task-oriented dialogue benchmarks lack
sufficient examples of complex discourse phenomena such as indirectness. To
address this, we propose a set of linguistic criteria along with an LLM-based
pipeline for generating realistic IURs to test natural language understanding
(NLU) and dialogue state tracking (DST) models before deployment in a new
domain. We also release IndirectRequests, a dataset of IURs based on the Schema
Guided Dialog (SGD) corpus, as a comparative testbed for evaluating the
performance of smaller models in handling indirect requests.
