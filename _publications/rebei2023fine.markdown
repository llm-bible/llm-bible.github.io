---
layout: publication
title: Fine45;tuning Language Models For Context45;specific SQL Query Generation
authors: Rebei Amine
conference: "Arxiv"
year: 2023
bibkey: rebei2023fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.02251"}
tags: ['Applications', 'Fine Tuning', 'GPT', 'Model Architecture']
---
The ability to generate SQL queries from natural language has significant implications for making data accessible to non45;specialists. This paper presents a novel approach to fine45;tuning open45;source large language models (LLMs) for the task of transforming natural language into SQL queries within the retail domain. We introduce models specialized in generating SQL queries trained on synthetic datasets tailored to the Snowflake SQL and GoogleSQL dialects. Our methodology involves generating a context45;specific dataset using GPT45;4 then fine45;tuning three open45;source LLMs(Starcoder Plus Code45;Llama and Mistral) employing the LoRa technique to optimize for resource constraints. The fine45;tuned models demonstrate superior performance in zero45;shot settings compared to the baseline GPT45;4 with Code45;Llama achieving the highest accuracy rates at 81.5837; for Snowflake SQL and 82.6637; for GoogleSQL. These results underscore the effectiveness of fine45;tuning LLMs on domain45;specific tasks and suggest a promising direction for enhancing the accessibility of relational databases through natural language interfaces.
