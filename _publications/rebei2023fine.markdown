---
layout: publication
title: 'Fine-tuning Language Models For Context-specific SQL Query Generation'
authors: Rebei Amine
conference: "Arxiv"
year: 2023
bibkey: rebei2023fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.02251"}
tags: ['Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
The ability to generate SQL queries from natural language has significant
implications for making data accessible to non-specialists. This paper presents
a novel approach to fine-tuning open-source large language models (LLMs) for
the task of transforming natural language into SQL queries within the retail
domain. We introduce models specialized in generating SQL queries, trained on
synthetic datasets tailored to the Snowflake SQL and GoogleSQL dialects. Our
methodology involves generating a context-specific dataset using GPT-4, then
fine-tuning three open-source LLMs(Starcoder Plus, Code-Llama, and Mistral)
employing the LoRa technique to optimize for resource constraints. The
fine-tuned models demonstrate superior performance in zero-shot settings
compared to the baseline GPT-4, with Code-Llama achieving the highest accuracy
rates, at 81.58% for Snowflake SQL and 82.66% for GoogleSQL. These results
underscore the effectiveness of fine-tuning LLMs on domain-specific tasks and
suggest a promising direction for enhancing the accessibility of relational
databases through natural language interfaces.
