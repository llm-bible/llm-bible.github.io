---
layout: publication
title: 'ARC: Argument Representation And Coverage Analysis For Zero-shot Long Document Summarization With Instruction Following Llms'
authors: Mohamed Elaraby, Diane Litman
conference: "Arxiv"
year: 2025
bibkey: elaraby2025argument
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.23654'}
tags: ['RAG', 'Applications', 'Tools', 'Reinforcement Learning', 'Ethics and Bias']
---
Integrating structured information has long improved the quality of abstractive summarization, particularly in retaining salient content. In this work, we focus on a specific form of structure: argument roles, which are crucial for summarizing documents in high-stakes domains such as law. We investigate whether instruction-tuned large language models (LLMs) adequately preserve this information. To this end, we introduce Argument Representation Coverage (ARC), a framework for measuring how well LLM-generated summaries capture salient arguments. Using ARC, we analyze summaries produced by three open-weight LLMs in two domains where argument roles are central: long legal opinions and scientific articles. Our results show that while LLMs cover salient argument roles to some extent, critical information is often omitted in generated summaries, particularly when arguments are sparsely distributed throughout the input. Further, we use ARC to uncover behavioral patterns -- specifically, how the positional bias of LLM context windows and role-specific preferences impact the coverage of key arguments in generated summaries, emphasizing the need for more argument-aware summarization strategies.
