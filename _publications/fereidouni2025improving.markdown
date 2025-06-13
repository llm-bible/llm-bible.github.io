---
layout: publication
title: 'Improving Multi-turn Task Completion In Task-oriented Dialog Systems Via Prompt Chaining And Fine-grained Feedback'
authors: Moghis Fereidouni, Md Sajid Ahmed, Adib Mosharrof, A. B. Siddique
conference: "Arxiv"
year: 2025
bibkey: fereidouni2025improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.13298"}
tags: ['Training Techniques', 'Tools', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning', 'Prompting']
---
Task-oriented dialog (TOD) systems facilitate users in accomplishing complex,
multi-turn tasks through natural language. While traditional approaches rely on
extensive fine-tuning and annotated data for each domain, instruction-tuned
large language models (LLMs) offer a more flexible alternative. However, LLMs
struggle to reliably handle multi-turn task completion, particularly with
accurately generating API calls and adapting to new domains without explicit
demonstrations. To address these challenges, we propose RealTOD, a novel
framework that enhances TOD systems through prompt chaining and fine-grained
feedback mechanisms. Prompt chaining enables zero-shot domain adaptation via a
two-stage prompting strategy, eliminating the need for human-curated
demonstrations. Meanwhile, the fine-grained feedback mechanism improves task
completion by verifying API calls against domain schemas and providing precise
corrective feedback when errors are detected. We conduct extensive experiments
on the SGD and BiTOD benchmarks using four LLMs. RealTOD improves API accuracy,
surpassing AutoTOD by 37.74% on SGD and SimpleTOD by 11.26% on BiTOD. Human
evaluations further confirm that LLMs integrated with RealTOD achieve superior
task completion, fluency, and informativeness compared to existing methods.
