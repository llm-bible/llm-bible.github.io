---
layout: publication
title: Writing your own book A method for going from closed to open book QA to improve robustness and performance of smaller LLMs
authors: Kokaia Giorgi, Sinha Pratyush, Jiang Yutong, Boujemaa Nozha
conference: "Arxiv"
year: 2023
bibkey: kokaia2023writing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.11334"}
tags: ['ARXIV', 'Applications', 'GPT', 'LLM', 'Prompt', 'RAG', 'Security']
---
We introduce two novel methods Tree-Search and Self-contextualizing QA designed to enhance the performance of large language models (LLMs) in question-answering tasks. Tree-Search is a sampling technique specifically created to extract diverse information from an LLM for a given prompt. Self-contextualizing QA leverages Tree-Search to enable the model to create its own context using a wide range of information relevant to the prompt evaluate it explicitly and return a open book answer to the initial prompt . We demonstrate that the quality of generated answers improves according to various metrics including accuracy informativeness coherence and consistency as evaluated by GPT3.5(text-davinci-003). Furthermore we show that our methods result in increased robustness and that performance is positively correlated with tree size benefiting both answer quality and robustness. Finally we discuss other promising applications of Tree-Search highlighting its potential to enhance a broad range of tasks beyond question-answering. noindent We also discuss several areas for future work including refining the Tree-Search and Self-Contextualizing QA methods improving the coherence of the generated context and investigating the impact of bootstrapping on model robustness
