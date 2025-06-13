---
layout: publication
title: 'Automating The Generation Of Prompts For Llm-based Action Choice In PDDL Planning'
authors: Katharina Stein, Daniel Fišer, Jörg Hoffmann, Alexander Koller
conference: "Arxiv"
year: 2023
bibkey: stein2023automating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2311.09830'}
tags: ['RAG', 'Prompting']
---
Large language models (LLMs) have revolutionized a large variety of NLP
tasks. An active debate is to what extent they can do reasoning and planning.
Prior work has assessed the latter in the specific context of PDDL planning,
based on manually converting three PDDL domains into natural language (NL)
prompts. Here we automate this conversion step, showing how to leverage an LLM
to automatically generate NL prompts from PDDL input. Our automatically
generated NL prompts result in similar LLM-planning performance as the previous
manually generated ones. Beyond this, the automation enables us to run much
larger experiments, providing for the first time a broad evaluation of LLM
planning performance in PDDL. Our NL prompts yield better performance than PDDL
prompts and simple template-based NL prompts. Compared to symbolic planners,
LLM planning lags far behind; but in some domains, our best LLM configuration
scales up further than A\\(^\star\\) using LM-cut.
