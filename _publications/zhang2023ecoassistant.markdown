---
layout: publication
title: EcoAssistant Using LLM Assistant More Affordably and Accurately
authors: Zhang Jieyu, Krishna Ranjay, Awadallah Ahmed H., Wang Chi
conference: "Arxiv"
year: 2023
bibkey: zhang2023ecoassistant
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.03046"}
tags: ['ARXIV', 'GPT', 'Pretraining Methods', 'Tools']
---
Today users ask Large language models (LLMs) as assistants to answer queries that require external knowledge; they ask about the weather in a specific city about stock prices and even about where specific locations are within their neighborhood. These queries require the LLM to produce code that invokes external APIs to answer the users question yet LLMs rarely produce correct code on the first try requiring iterative code refinement upon execution results. In addition using LLM assistants to support high query volumes can be expensive. In this work we contribute a framework EcoAssistant that enables LLMs to answer code-driven queries more affordably and accurately. EcoAssistant contains three components. First it allows the LLM assistants to converse with an automatic code executor to iteratively refine code or to produce answers based on the execution results. Second we use a hierarchy of LLM assistants which attempts to answer the query with weaker cheaper LLMs before backing off to stronger expensive ones. Third we retrieve solutions from past successful queries as in-context demonstrations to help subsequent queries. Empirically we show that EcoAssistant offers distinct advantages for affordability and accuracy surpassing GPT-4 by 10 points of success rate with less than 50 of GPT-4s cost.
