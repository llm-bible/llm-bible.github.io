---
layout: publication
title: 'Evaluating Research Quality With Large Language Models: An Analysis Of Chatgpt''s Effectiveness With Different Settings And Inputs'
authors: Mike Thelwall
conference: "Arxiv"
year: 2024
bibkey: thelwall2024evaluating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2408.06752'}
tags: ['RAG', 'GPT', 'Model Architecture', 'Prompting', 'Reinforcement Learning']
---
Evaluating the quality of academic journal articles is a time consuming but
critical task for national research evaluation exercises, appointments and
promotion. It is therefore important to investigate whether Large Language
Models (LLMs) can play a role in this process. This article assesses which
ChatGPT inputs (full text without tables, figures and references; title and
abstract; title only) produce better quality score estimates, and the extent to
which scores are affected by ChatGPT models and system prompts. The results
show that the optimal input is the article title and abstract, with average
ChatGPT scores based on these (30 iterations on a dataset of 51 papers)
correlating at 0.67 with human scores, the highest ever reported. ChatGPT 4o is
slightly better than 3.5-turbo (0.66), and 4o-mini (0.66). The results suggest
that article full texts might confuse LLM research quality evaluations, even
though complex system instructions for the task are more effective than simple
ones. Thus, whilst abstracts contain insufficient information for a thorough
assessment of rigour, they may contain strong pointers about originality and
significance. Finally, linear regression can be used to convert the model
scores into the human scale scores, which is 31% more accurate than guessing.
