---
layout: publication
title: 'Is Chatgpt A Good Software Librarian? An Exploratory Study On The Use Of Chatgpt For Software Library Recommendations'
authors: Jasmine Latendresse, Sayedhassan Khatoonabadi, Ahmad Abdellatif, Emad Shihab
conference: "Arxiv"
year: 2024
bibkey: latendresse2024is
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.05128"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'Merging', 'GPT', 'Fine-Tuning']
---
Software libraries play a critical role in the functionality, efficiency, and
maintainability of software systems. As developers increasingly rely on Large
Language Models (LLMs) to streamline their coding processes, the effectiveness
of these models in recommending appropriate libraries becomes crucial yet
remains largely unexplored. In this paper, we assess the effectiveness of
ChatGPT as a software librarian and identify areas for improvement. We
conducted an empirical study using GPT-3.5 Turbo to generate Python code for
10,000 Stack Overflow questions. Our findings show that ChatGPT uses
third-party libraries nearly 10% more often than human developers, favoring
widely adopted and well-established options. However, 14.2% of the recommended
libraries had restrictive copyleft licenses, which were not explicitly
communicated by ChatGPT. Additionally, 6.5% of the libraries did not work out
of the box, leading to potential developer confusion and wasted time. While
ChatGPT can be an effective software librarian, it should be improved by
providing more explicit information on maintainability metrics and licensing.
We recommend that developers implement rigorous dependency management practices
and double-check library licenses before integrating LLM-generated code into
their projects.
