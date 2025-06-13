---
layout: publication
title: 'Can Long-context Language Models Subsume Retrieval, RAG, SQL, And More?'
authors: Jinhyuk Lee, Anthony Chen, Zhuyun Dai, Dheeru Dua, Devendra Singh Sachan, Michael Boratko, Yi Luan, Sébastien M. R. Arnold, Vincent Perot, Siddharth Dalmia, Hexiang Hu, Xudong Lin, Panupong Pasupat, Aida Amini, Jeremy R. Cole, Sebastian Riedel, Iftekhar Naim, Ming-wei Chang, Kelvin Guu
conference: "Arxiv"
year: 2024
bibkey: lee2024can
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.13121'}
tags: ['Reinforcement Learning', 'RAG', 'Prompting', 'Tools']
---
Long-context language models (LCLMs) have the potential to revolutionize our
approach to tasks traditionally reliant on external tools like retrieval
systems or databases. Leveraging LCLMs' ability to natively ingest and process
entire corpora of information offers numerous advantages. It enhances
user-friendliness by eliminating the need for specialized knowledge of tools,
provides robust end-to-end modeling that minimizes cascading errors in complex
pipelines, and allows for the application of sophisticated prompting techniques
across the entire system. To assess this paradigm shift, we introduce LOFT, a
benchmark of real-world tasks requiring context up to millions of tokens
designed to evaluate LCLMs' performance on in-context retrieval and reasoning.
Our findings reveal LCLMs' surprising ability to rival state-of-the-art
retrieval and RAG systems, despite never having been explicitly trained for
these tasks. However, LCLMs still face challenges in areas like compositional
reasoning that are required in SQL-like tasks. Notably, prompting strategies
significantly influence performance, emphasizing the need for continued
research as context lengths grow. Overall, LOFT provides a rigorous testing
ground for LCLMs, showcasing their potential to supplant existing paradigms and
tackle novel tasks as model capabilities scale.
