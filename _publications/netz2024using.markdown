---
layout: publication
title: Using Grammar Masking to Ensure Syntactic Validity in LLM-based Modeling Tasks
authors: Netz Lukas, Reimer Jan, Rumpe Bernhard
conference: "Arxiv"
year: 2024
bibkey: netz2024using
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.06146"}
tags: ['Few Shot', 'Prompting', 'Training Techniques']
---
We present and evaluate a method called grammar masking which is used to guide large language models (LLMs) toward producing syntactically correct models for a given context-free grammar. Prompt engineering methods such as few-shot learning or priming can be used to improve the chances of an LLM producing correct syntax but the more complex the grammar the more time-consuming and less promising these methods become. Previous work is focused primarily on the usage of either language model training or prompt engineering. In this work a method is presented that restricts the output to a given grammar using constrained decoding to ensure the output adheres to a valid syntax. We use several DSLs built with MontiCore and task multiple LLMs to produce models with and without constrained decoding. A corresponding parser is used to confirm the syntactic correctness of each model. We show that grammar masking can dramatically improve the modeling capabilities of several LLMs reducing the need for well-refined prompting while increasing the chance of producing correct models.
