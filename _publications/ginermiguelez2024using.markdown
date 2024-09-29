---
layout: publication
title: Using Large Language Models To Enrich The Documentation Of Datasets For Machine Learning
authors: Giner-miguelez Joan, Gómez Abel, Cabot Jordi
conference: "Arxiv"
year: 2024
bibkey: ginermiguelez2024using
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.15320"}
tags: ['GPT', 'Model Architecture', 'Prompting', 'Reinforcement Learning']
---
Recent regulatory initiatives like the European AI Act and relevant voices in the Machine Learning (ML) community stress the need to describe datasets along several key dimensions for trustworthy AI such as the provenance processes and social concerns. However this information is typically presented as unstructured text in accompanying documentation hampering their automated analysis and processing. In this work we explore using large language models (LLM) and a set of prompting strategies to automatically extract these dimensions from documents and enrich the dataset description with them. Our approach could aid data publishers and practitioners in creating machine-readable documentation to improve the discoverability of their datasets assess their compliance with current AI regulations and improve the overall quality of ML models trained on them. In this paper we evaluate the approach on 12 scientific dataset papers published in two scientific journals (Natures Scientific Data and Elseviers Data in Brief) using two different LLMs (GPT3.5 and Flan-UL2). Results show good accuracy with our prompt extraction strategies. Concrete results vary depending on the dimensions but overall GPT3.5 shows slightly better accuracy (812137;) than FLAN-UL2 (691337;) although it is more prone to hallucinations. We have released an open-source tool implementing our approach and a replication package including the experiments code and results in an open-source repository.
