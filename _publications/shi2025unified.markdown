---
layout: publication
title: 'Unified Generative Search And Recommendation'
authors: Teng Shi, Jun Xu, Xiao Zhang, Xiaoxue Zang, Kai Zheng, Yang Song, Enyun Yu
conference: "Arxiv"
year: 2025
bibkey: shi2025unified
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.05730"}
tags: ['Training Techniques', 'RAG', 'Tools', 'Prompting']
---
Modern commercial platforms typically offer both search and recommendation
functionalities to serve diverse user needs, making joint modeling of these
tasks an appealing direction. While prior work has shown that integrating
search and recommendation can be mutually beneficial, it also reveals a
performance trade-off: enhancements in one task often come at the expense of
the other. This challenge arises from their distinct information requirements:
search emphasizes semantic relevance between queries and items, whereas
recommendation depends more on collaborative signals among users and items.
Effectively addressing this trade-off requires tackling two key problems: (1)
integrating both semantic and collaborative signals into item representations,
and (2) guiding the model to distinguish and adapt to the unique demands of
search and recommendation. The emergence of generative retrieval with Large
Language Models (LLMs) presents new possibilities. This paradigm encodes items
as identifiers and frames both search and recommendation as sequential
generation tasks, offering the flexibility to leverage multiple identifiers and
task-specific prompts. In light of this, we introduce GenSAR, a unified
generative framework for balanced search and recommendation. Our approach
designs dual-purpose identifiers and tailored training strategies to
incorporate complementary signals and align with task-specific objectives.
Experiments on both public and commercial datasets demonstrate that GenSAR
effectively reduces the trade-off and achieves state-of-the-art performance on
both tasks.
