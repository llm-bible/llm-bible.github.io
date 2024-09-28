---
layout: publication
title: DataFrame QA A Universal LLM Framework on DataFrame Question Answering Without Data Exposure
authors: Ye Junyi, Du Mengnan, Wang Guiling
conference: "Arxiv"
year: 2024
bibkey: ye2024dataframe
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.15463"}
tags: ['ARXIV', 'Applications', 'GPT', 'LLM', 'Prompt', 'Tools']
---
This paper introduces DataFrame question answering (QA) a novel task that utilizes large language models (LLMs) to generate Pandas queries for information retrieval and data analysis on dataframes emphasizing safe and non-revealing data handling. Our method which solely relies on dataframe column names not only ensures data privacy but also significantly reduces the context window in the prompt streamlining information processing and addressing major challenges in LLM-based data analysis. We propose DataFrame QA as a comprehensive framework that includes safe Pandas query generation and code execution. Various LLMs notably GPT-4 are evaluated using the pass@1 metric on the renowned WikiSQL and our newly developed UCI-DataFrameQA tailored for complex data analysis queries. Our findings indicate that GPT-4 achieves pass@1 rates of 86 on WikiSQL and 97 on UCI-DataFrameQA underscoring its capability in securely retrieving and aggregating dataframe values and conducting sophisticated data analyses. This approach deployable in a zero-shot manner without prior training or adjustments proves to be highly adaptable and secure for diverse applications.
