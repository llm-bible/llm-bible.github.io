---
layout: publication
title: 'PET-SQL: A Prompt-enhanced Two-round Refinement Of Text-to-sql With Cross-consistency'
authors: Zhishuai Li, Xiang Wang, Jingjing Zhao, Sun Yang, Guoqing Du, Xiaoru Hu, Bin Zhang, Yuxiao Ye, Ziyue Li, Rui Zhao, Hangyu Mao
conference: "Arxiv"
year: 2024
bibkey: li2024pet
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.09732"}
tags: ['Few-Shot', 'Tools', 'Prompting', 'In-Context Learning']
---
Recent advancements in Text-to-SQL (Text2SQL) emphasize stimulating the large
language models (LLM) on in-context learning, achieving significant results.
Nevertheless, they face challenges when dealing with verbose database
information and complex user intentions. This paper presents a two-stage
framework to enhance the performance of current LLM-based natural language to
SQL systems. We first introduce a novel prompt representation, called
reference-enhanced representation, which includes schema information and
randomly sampled cell values from tables to instruct LLMs in generating SQL
queries. Then, in the first stage, question-SQL pairs are retrieved as few-shot
demonstrations, prompting the LLM to generate a preliminary SQL (PreSQL). After
that, the mentioned entities in PreSQL are parsed to conduct schema linking,
which can significantly compact the useful information. In the second stage,
with the linked schema, we simplify the prompt's schema information and
instruct the LLM to produce the final SQL. Finally, as the post-refinement
module, we propose using cross-consistency across different LLMs rather than
self-consistency within a particular LLM. Our methods achieve new SOTA results
on the Spider benchmark, with an execution accuracy of 87.6%.
