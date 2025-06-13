---
layout: publication
title: 'Sense And Sensitivity: Examining The Influence Of Semantic Recall On Long Context Code Reasoning'
authors: Adam Štorek, Mukur Gupta, Samira Hajizadeh, Prashast Srivastava, Suman Jana
conference: "Arxiv"
year: 2025
bibkey: štorek2025sense
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.13353'}
tags: ['Reinforcement Learning', 'RAG']
---
Although modern Large Language Models (LLMs) support extremely large contexts, their effectiveness in utilizing long context for code reasoning remains unclear. This paper investigates LLM reasoning ability over code snippets within large repositories and how it relates to their recall ability. Specifically, we differentiate between lexical code recall (verbatim retrieval) and semantic code recall (remembering what the code does). To measure semantic recall, we propose SemTrace, a code reasoning technique where the impact of specific statements on output is attributable and unpredictable. We also present a method to quantify semantic recall sensitivity in existing benchmarks. Our evaluation of state-of-the-art LLMs reveals a significant drop in code reasoning accuracy as a code snippet approaches the middle of the input context, particularly with techniques requiring high semantic recall like SemTrace. Moreover, we find that lexical recall varies by granularity, with models excelling at function retrieval but struggling with line-by-line recall. Notably, a disconnect exists between lexical and semantic recall, suggesting different underlying mechanisms. Finally, our findings indicate that current code reasoning benchmarks may exhibit low semantic recall sensitivity, potentially underestimating LLM challenges in leveraging in-context information.
