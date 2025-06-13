---
layout: publication
title: 'Solving Data-centric Tasks Using Large Language Models'
authors: Shraddha Barke, Christian Poelitz, Carina Suzana Negreanu, Benjamin Zorn, José Cambronero, Andrew D. Gordon, Vu Le, Elnaz Nouri, Nadia Polikarpova, Advait Sarkar, Brian Slininger, Neil Toronto, Jack Williams
conference: "Arxiv"
year: 2024
bibkey: barke2024solving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.11734"}
tags: ['Tools', 'Prompting', 'Reinforcement Learning']
---
Large language models (LLMs) are rapidly replacing help forums like
StackOverflow, and are especially helpful for non-professional programmers and
end users. These users are often interested in data-centric tasks, such as
spreadsheet manipulation and data wrangling, which are hard to solve if the
intent is only communicated using a natural-language description, without
including the data. But how do we decide how much data and which data to
include in the prompt? This paper makes two contributions towards answering
this question. First, we create a dataset of real-world NL-to-code tasks
manipulating tabular data, mined from StackOverflow posts. Second, we introduce
a cluster-then-select prompting technique, which adds the most representative
rows from the input data to the LLM prompt. Our experiments show that LLM
performance is indeed sensitive to the amount of data passed in the prompt, and
that for tasks with a lot of syntactic variation in the input table, our
cluster-then-select technique outperforms a random selection baseline.
