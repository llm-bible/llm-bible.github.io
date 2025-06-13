---
layout: publication
title: 'Sqlprompt: In-context Text-to-sql With Minimal Labeled Data'
authors: Ruoxi Sun, Sercan Ö. Arik, Rajarishi Sinha, Hootan Nakhost, Hanjun Dai, Pengcheng Yin, Tomas Pfister
conference: "Arxiv"
year: 2023
bibkey: sun2023text
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2311.02883'}
tags: ['Few-Shot', 'Prompting', 'In-Context Learning']
---
Text-to-SQL aims to automate the process of generating SQL queries on a
database from natural language text. In this work, we propose "SQLPrompt",
tailored to improve the few-shot prompting capabilities of Text-to-SQL for
Large Language Models (LLMs). Our methods include innovative prompt design,
execution-based consistency decoding strategy which selects the SQL with the
most consistent execution outcome among other SQL proposals, and a method that
aims to improve performance by diversifying the SQL proposals during
consistency selection with different prompt designs ("MixPrompt") and
foundation models ("MixLLMs"). We show that *SQLPrompt* outperforms
previous approaches for in-context learning with few labeled data by a large
margin, closing the gap with finetuning state-of-the-art with thousands of
labeled data.
