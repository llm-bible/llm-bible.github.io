---
layout: publication
title: 'Prompt Engineering: How Prompt Vocabulary Affects Domain Knowledge'
authors: Dimitri Schreiter
conference: "Arxiv"
year: 2025
bibkey: schreiter2025prompt
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.17037'}
tags: ['Prompting', 'Applications', 'Tools']
---
Prompt engineering has emerged as a critical component in optimizing large language models (LLMs) for domain-specific tasks. However, the role of prompt specificity, especially in domains like STEM (physics, chemistry, biology, computer science and mathematics), medicine, and law, remains underexplored. This thesis addresses the problem of whether increasing the specificity of vocabulary in prompts improves LLM performance in domain-specific question-answering and reasoning tasks. We developed a synonymization framework to systematically substitute nouns, verbs, and adjectives with varying specificity levels, measuring the impact on four LLMs: Llama-3.1-70B-Instruct, Granite-13B-Instruct-V2, Flan-T5-XL, and Mistral-Large 2, across datasets in STEM, law, and medicine. Our results reveal that while generally increasing the specificity of prompts does not have a significant impact, there appears to be a specificity range, across all considered models, where the LLM performs the best. Identifying this optimal specificity range offers a key insight for prompt design, suggesting that manipulating prompts within this range could maximize LLM performance and lead to more efficient applications in specialized domains.
