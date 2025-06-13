---
layout: publication
title: 'MCS-SQL: Leveraging Multiple Prompts And Multiple-choice Selection For Text-to-sql Generation'
authors: Dongjun Lee, Choongwon Park, Jaehyuk Kim, Heesoo Park
conference: "Arxiv"
year: 2024
bibkey: lee2024mcs
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.07467"}
tags: ['Fine-Tuning', 'Efficiency and Optimization', 'RAG', 'Training Techniques', 'Pretraining Methods', 'Prompting']
---
Recent advancements in large language models (LLMs) have enabled in-context
learning (ICL)-based methods that significantly outperform fine-tuning
approaches for text-to-SQL tasks. However, their performance is still
considerably lower than that of human experts on benchmarks that include
complex schemas and queries, such as BIRD. This study considers the sensitivity
of LLMs to the prompts and introduces a novel approach that leverages multiple
prompts to explore a broader search space for possible answers and effectively
aggregate them. Specifically, we robustly refine the database schema through
schema linking using multiple prompts. Thereafter, we generate various
candidate SQL queries based on the refined schema and diverse prompts. Finally,
the candidate queries are filtered based on their confidence scores, and the
optimal query is obtained through a multiple-choice selection that is presented
to the LLM. When evaluated on the BIRD and Spider benchmarks, the proposed
method achieved execution accuracies of 65.5% and 89.6%, respectively,
significantly outperforming previous ICL-based methods. Moreover, we
established a new SOTA performance on the BIRD in terms of both the accuracy
and efficiency of the generated queries.
