---
layout: publication
title: 'Oreo: A Plug-in Context Reconstructor To Enhance Retrieval-augmented Generation'
authors: Sha Li, Naren Ramakrishnan
conference: "Arxiv"
year: 2025
bibkey: li2025plug
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.13019'}
tags: ['Reinforcement Learning', 'RAG', 'Agentic', 'Training Techniques']
---
Retrieval-Augmented Generation (RAG) aims to augment the capabilities of
Large Language Models (LLMs) by retrieving and incorporate external documents
or chunks prior to generation. However, even improved retriever relevance can
brings erroneous or contextually distracting information, undermining the
effectiveness of RAG in downstream tasks. We introduce a compact, efficient,
and pluggable module designed to refine retrieved chunks before using them for
generation. The module aims to extract and reorganize the most relevant and
supportive information into a concise, query-specific format. Through a
three-stage training paradigm - comprising supervised fine - tuning,
contrastive multi-task learning, and reinforcement learning-based alignment -
it prioritizes critical knowledge and aligns it with the generator's
preferences. This approach enables LLMs to produce outputs that are more
accurate, reliable, and contextually appropriate.
