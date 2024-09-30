---
layout: publication
title: 'RE-GAINS & Enchant: Intelligent Tool Manipulation Systems For Enhanced Query Responses'
authors: Girhepuje Sahil, Sajeev Siva Sankar, Jain Purvam, Sikder Arya, Varma Adithya Rama, George Ryan, Srinivasan Akshay Govind, Kurup Mahendra, Sinha Ashmit, Mondal Sudip
conference: "Arxiv"
year: 2024
bibkey: girhepuje2024re
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.15724"}
tags: ['Pretraining Methods', 'Prompting', 'RAG', 'Tools']
---
Large Language Models (LLMs) currently struggle with tool invocation and chaining as they often hallucinate or miss essential steps in a sequence. We propose RE-GAINS and EnChAnT two novel frameworks that empower LLMs to tackle complex user queries by making API calls to external tools based on tool descriptions and argument lists. Tools are chained based on the expected output without receiving the actual results from each individual call. EnChAnT an open-source solution leverages an LLM format enforcer OpenChat 3.5 (an LLM) and ToolBenchs API Retriever. RE-GAINS utilizes OpenAI models and embeddings with a specialized prompt based on the ()easoning vi() ()lanning ((RAP)) framework. Both frameworks are low cost (0.01 per query). Our key contribution is enabling LLMs for tool invocation and chaining using modifiable externally described tools.
