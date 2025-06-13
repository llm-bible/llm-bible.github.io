---
layout: publication
title: 'Coderepoqa: A Large-scale Benchmark For Software Engineering Question Answering'
authors: Ruida Hu, Chao Peng, Jingyi Ren, Bo Jiang, Xiangxin Meng, Qinyun Wu, Pengfei Gao, Xinchen Wang, Cuiyun Gao
conference: "Arxiv"
year: 2024
bibkey: hu2024large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.14764"}
  - {name: "Code", url: "https://github.com/kinesiatricssxilm14/CodeRepoQA"}
tags: ['RAG', 'Applications', 'Has Code', 'Tools']
---
In this work, we introduce CodeRepoQA, a large-scale benchmark specifically
designed for evaluating repository-level question-answering capabilities in the
field of software engineering. CodeRepoQA encompasses five programming
languages and covers a wide range of scenarios, enabling comprehensive
evaluation of language models. To construct this dataset, we crawl data from 30
well-known repositories in GitHub, the largest platform for hosting and
collaborating on code, and carefully filter raw data. In total, CodeRepoQA is a
multi-turn question-answering benchmark with 585,687 entries, covering a
diverse array of software engineering scenarios, with an average of 6.62
dialogue turns per entry.
  We evaluate ten popular large language models on our dataset and provide
in-depth analysis. We find that LLMs still have limitations in
question-answering capabilities in the field of software engineering, and
medium-length contexts are more conducive to LLMs' performance. The entire
benchmark is publicly available at
https://github.com/kinesiatricssxilm14/CodeRepoQA.
