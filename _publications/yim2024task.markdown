---
layout: publication
title: 'The Task-oriented Queries Benchmark (toqb)'
authors: Yim Keun Soo
conference: "Arxiv"
year: 2024
bibkey: yim2024task
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.02943"}
tags: ['Applications', 'Prompting', 'Reinforcement Learning', 'Tools', 'Uncategorized']
---
Task-oriented queries (e.g., one-shot queries to play videos, order food, or
call a taxi) are crucial for assessing the quality of virtual assistants,
chatbots, and other large language model (LLM)-based services. However, a
standard benchmark for task-oriented queries is not yet available, as existing
benchmarks in the relevant NLP (Natural Language Processing) fields have
primarily focused on task-oriented dialogues. Thus, we present a new
methodology for efficiently generating the Task-oriented Queries Benchmark
(ToQB) using existing task-oriented dialogue datasets and an LLM service. Our
methodology involves formulating the underlying NLP task to summarize the
original intent of a speaker in each dialogue, detailing the key steps to
perform the devised NLP task using an LLM service, and outlining a framework
for automating a major part of the benchmark generation process. Through a case
study encompassing three domains (i.e., two single-task domains and one
multi-task domain), we demonstrate how to customize the LLM prompts (e.g.,
omitting system utterances or speaker labels) for those three domains and
characterize the generated task-oriented queries. The generated ToQB dataset is
made available to the public. We further discuss new domains that can be added
to ToQB by community contributors and its practical applications.
