---
layout: publication
title: 'On Evaluating The Integration Of Reasoning And Action In LLM Agents With Database Question Answering'
authors: Linyong Nan, Ellen Zhang, Weijin Zou, Yilun Zhao, Wenfei Zhou, Arman Cohan
conference: "Arxiv"
year: 2023
bibkey: nan2023evaluating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.09721"}
tags: ['Agentic', 'Model Architecture', 'Survey Paper', 'Tools', 'GPT', 'Applications']
---
This study introduces a new long-form database question answering dataset
designed to evaluate how Large Language Models (LLMs) interact with a SQL
interpreter. The task necessitates LLMs to strategically generate multiple SQL
queries to retrieve sufficient data from a database, to reason with the
acquired context, and to synthesize them into a comprehensive analytical
narrative. Our findings highlight that this task poses great challenges even
for the state-of-the-art GPT-4 model. We propose and evaluate two interaction
strategies, and provide a fine-grained analysis of the individual stages within
the interaction. A key discovery is the identification of two primary
bottlenecks hindering effective interaction: the capacity for planning and the
ability to generate multiple SQL queries. To address the challenge of
accurately assessing answer quality, we introduce a multi-agent evaluation
framework that simulates the academic peer-review process, enhancing the
precision and reliability of our evaluations. This framework allows for a more
nuanced understanding of the strengths and limitations of current LLMs in
complex retrieval and reasoning tasks.
