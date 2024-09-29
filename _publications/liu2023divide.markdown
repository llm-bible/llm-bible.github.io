---
layout: publication
title: Divide And Prompt\: Chain Of Thought Prompting For Text-to-sql
authors: Liu Xiping, Tan Zhao
conference: "Arxiv"
year: 2023
bibkey: liu2023divide
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2304.11556"}
tags: ['Pretraining Methods', 'Prompting', 'RAG']
---
Chain-of-thought (CoT) prompting combined with large language models (LLMs) have achieved encouraging results on complex reasoning tasks. Text-to-SQL is a critical semantic parsing task that converts natural language questions into SQL statements involving a complex reasoning process. However there is little work about using CoT prompting to activate LLMs reasoning capabilities on Text-to-SQL tasks. In this work we propose a new paradigm for prompting Text-to-SQL tasks called Divide-and-Prompt which first divides the task into subtasks and then approach each subtask through CoT. We present 3 prompting-based methods to enhance the Text-to-SQL ability of LLMs. Experiments show that these prompts guide LLMs to generate Text-to-SQL with higher execution accuracy.
