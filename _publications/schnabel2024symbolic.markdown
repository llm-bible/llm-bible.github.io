---
layout: publication
title: 'Symbolic Prompt Program Search: A Structure-aware Approach To Efficient Compile-time Prompt Optimization'
authors: Schnabel Tobias, Neville Jennifer
conference: "Arxiv"
year: 2024
bibkey: schnabel2024symbolic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.02319"}
  - {name: "Code", url: "https://github.com/microsoft/sammo"}
tags: ['Applications', 'Efficiency And Optimization', 'Has Code', 'Prompting', 'RAG', 'Tools']
---
In many modern LLM applications such as retrieval augmented generation prompts have become programs themselves. In these settings prompt programs are repeatedly called with different user queries or data instances. A big practical challenge is optimizing such prompt programs. Recent work has mostly focused on either simple prompt programs or assumed that the general structure of a prompt program is fixed. We introduce SAMMO a framework to perform symbolic prompt program search for compile-time optimizations of prompt programs. SAMMO represents prompt programs on a symbolic level which allows for a rich set of transformations that can be searched over during optimization. We show that SAMMO generalizes previous methods and improves the performance of complex prompts on (1) instruction tuning (2) RAG pipeline tuning and (3) prompt compression across several different LLMs. We make all code available open-source at https://github.com/microsoft/sammo .
