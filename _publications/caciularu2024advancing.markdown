---
layout: publication
title: 'TACT: Advancing Complex Aggregative Reasoning With Information Extraction Tools'
authors: Caciularu Avi, Jacovi Alon, Ben-david Eyal, Goldshtein Sasha, Schuster Tal, Herzig Jonathan, Elidan Gal, Globerson Amir
conference: "Arxiv"
year: 2024
bibkey: caciularu2024advancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.03618"}
tags: ['Few Shot', 'In Context Learning', 'Prompting', 'RAG', 'Reinforcement Learning', 'Tools']
---
Large Language Models (LLMs) often do not perform well on queries that require the aggregation of information across texts. To better evaluate this setting and facilitate modeling efforts we introduce TACT - Text And Calculations through Tables a dataset crafted to evaluate LLMs reasoning and computational abilities using complex instructions. TACT contains challenging instructions that demand stitching information scattered across one or more texts and performing complex integration on this information to generate the answer. We construct this dataset by leveraging an existing dataset of texts and their associated tables. For each such tables we formulate new queries and gather their respective answers. We demonstrate that all contemporary LLMs perform poorly on this dataset achieving an accuracy below 3837;. To pinpoint the difficulties and thoroughly dissect the problem we analyze model performance across three components table-generation Pandas command-generation and execution. Unexpectedly we discover that each component presents substantial challenges for current LLMs. These insights lead us to propose a focused modeling framework which we refer to as IE as a tool. Specifically we propose to add tools for each of the above steps and implement each such tool with few-shot prompting. This approach shows an improvement over existing prompting techniques offering a promising direction for enhancing model capabilities in these tasks.
