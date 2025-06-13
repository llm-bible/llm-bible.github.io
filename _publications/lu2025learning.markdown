---
layout: publication
title: 'Learning To Generate Structured Output With Schema Reinforcement Learning'
authors: Yaxi Lu, Haolun Li, Xin Cong, Zhong Zhang, Yesai Wu, Yankai Lin, Zhiyuan Liu, Fangming Liu, Maosong Sun
conference: "Arxiv"
year: 2025
bibkey: lu2025learning
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.18878'}
tags: ['Reinforcement Learning', 'Agentic', 'Tools']
---
This study investigates the structured generation capabilities of large
language models (LLMs), focusing on producing valid JSON outputs against a
given schema. Despite the widespread use of JSON in integrating language models
with programs, there is a lack of comprehensive analysis and benchmarking of
these capabilities. We explore various aspects of JSON generation, such as
structure understanding, escaping, and natural language description, to
determine how to assess and enable LLMs to generate valid responses. Building
upon this, we propose SchemaBench features around 40K different JSON schemas to
obtain and assess models' abilities in generating valid JSON. We find that the
latest LLMs are still struggling to generate a valid JSON string. Moreover, we
demonstrate that incorporating reinforcement learning with a Fine-grained
Schema Validator can further enhance models' understanding of JSON schema,
leading to improved performance. Our models demonstrate significant improvement
in both generating JSON outputs and downstream tasks.
