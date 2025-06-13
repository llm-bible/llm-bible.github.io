---
layout: publication
title: 'Treerare: Syntax Tree-guided Retrieval And Reasoning For Knowledge-intensive Question Answering'
authors: Boyi Zhang, Zhuo Liu, Hangfeng He
conference: "Arxiv"
year: 2025
bibkey: zhang2025syntax
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.00331"}
tags: ['Tools', 'Applications']
---
In real practice, questions are typically complex and knowledge-intensive, requiring Large Language Models (LLMs) to recognize the multifaceted nature of the question and reason across multiple information sources. Iterative and adaptive retrieval, where LLMs decide when and what to retrieve based on their reasoning, has been shown to be a promising approach to resolve complex, knowledge-intensive questions. However, the performance of such retrieval frameworks is limited by the accumulation of reasoning errors and misaligned retrieval results. To overcome these limitations, we propose TreeRare (Syntax Tree-Guided Retrieval and Reasoning), a framework that utilizes syntax trees to guide information retrieval and reasoning for question answering. Following the principle of compositionality, TreeRare traverses the syntax tree in a bottom-up fashion, and in each node, it generates subcomponent-based queries and retrieves relevant passages to resolve localized uncertainty. A subcomponent question answering module then synthesizes these passages into concise, context-aware evidence. Finally, TreeRare aggregates the evidence across the tree to form a final answer. Experiments across five question answering datasets involving ambiguous or multi-hop reasoning demonstrate that TreeRare achieves substantial improvements over existing state-of-the-art methods.
