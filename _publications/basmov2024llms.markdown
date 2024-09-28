---
layout: publication
title: LLMs Reading Comprehension Is Affected by Parametric Knowledge and Struggles with Hypothetical Statements
authors: Basmov Victoria, Goldberg Yoav, Tsarfaty Reut
conference: "Arxiv"
year: 2024
bibkey: basmov2024llms
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.06283"}
tags: ['ARXIV', 'Applications', 'GPT', 'Tools']
---
The task of reading comprehension (RC) often implemented as context-based question answering (QA) provides a primary means to assess language models natural language understanding (NLU) capabilities. Yet when applied to large language models (LLMs) with extensive built-in world knowledge this method can be deceptive. If the context aligns with the LLMs internal knowledge it is hard to discern whether the models answers stem from context comprehension or from LLMs internal information. Conversely using data that conflicts with the models knowledge creates erroneous trends which distort the results. To address this issue we suggest to use RC on imaginary data based on fictitious facts and entities. This task is entirely independent of the models world knowledge enabling us to evaluate LLMs linguistic abilities without the interference of parametric knowledge. Testing ChatGPT GPT-4 LLaMA 2 and Mixtral on such imaginary data we uncover a class of linguistic phenomena posing a challenge to current LLMs involving thinking in terms of alternative hypothetical scenarios. While all the models handle simple affirmative and negative contexts with high accuracy they are much more prone to error when dealing with modal and conditional contexts. Crucially these phenomena also trigger the LLMs vulnerability to knowledge-conflicts again. In particular while some models prove virtually unaffected by knowledge conflicts in affirmative and negative contexts when faced with more semantically involved modal and conditional environments they often fail to separate the text from their internal knowledge.
