---
layout: publication
title: 'Text-to-sql Domain Adaptation Via Human-llm Collaborative Data Annotation'
authors: Yuan Tian, Daniel Lee, Fei Wu, Tung Mai, Kun Qian, Siddhartha Sahai, Tianyi Zhang, Yunyao Li
conference: "Arxiv"
year: 2025
bibkey: tian2025text
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.15980'}
  - {name: "Code", url: 'https://github.com/adobe/nl_sql_analyzer'}
tags: ['Has Code', 'Training Techniques', 'GPT', 'Applications', 'Fine-Tuning', 'Model Architecture', 'Reinforcement Learning', 'Pretraining Methods']
---
Text-to-SQL models, which parse natural language (NL) questions to executable
SQL queries, are increasingly adopted in real-world applications. However,
deploying such models in the real world often requires adapting them to the
highly specialized database schemas used in specific applications. We find that
existing text-to-SQL models experience significant performance drops when
applied to new schemas, primarily due to the lack of domain-specific data for
fine-tuning. This data scarcity also limits the ability to effectively evaluate
model performance in new domains. Continuously obtaining high-quality
text-to-SQL data for evolving schemas is prohibitively expensive in real-world
scenarios. To bridge this gap, we propose SQLsynth, a human-in-the-loop
text-to-SQL data annotation system. SQLsynth streamlines the creation of
high-quality text-to-SQL datasets through human-LLM collaboration in a
structured workflow. A within-subjects user study comparing SQLsynth with
manual annotation and ChatGPT shows that SQLsynth significantly accelerates
text-to-SQL data annotation, reduces cognitive load, and produces datasets that
are more accurate, natural, and diverse. Our code is available at
https://github.com/adobe/nl_sql_analyzer.
