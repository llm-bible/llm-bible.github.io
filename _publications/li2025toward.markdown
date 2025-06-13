---
layout: publication
title: 'Toward Multi-session Personalized Conversation: A Large-scale Dataset And Hierarchical Tree Framework For Implicit Reasoning'
authors: Xintong Li, Jalend Bantupalli, Ria Dharmani, Yuwei Zhang, Jingbo Shang
conference: "Arxiv"
year: 2025
bibkey: li2025toward
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.07018"}
tags: ['Tools', 'Agentic', 'Applications', 'Reinforcement Learning']
---
There has been a surge in the use of large language models (LLM)
conversational agents to generate responses based on long-term history from
multiple sessions. However, existing long-term open-domain dialogue datasets
lack complex, real-world personalization and fail to capture implicit
reasoning-where relevant information is embedded in subtle, syntactic, or
semantically distant connections rather than explicit statements. In such
cases, traditional retrieval methods fail to capture relevant context, and
long-context modeling also becomes inefficient due to numerous complicated
persona-related details. To address this gap, we introduce ImplexConv, a
large-scale long-term dataset with 2,500 examples, each containing
approximately 100 conversation sessions, designed to study implicit reasoning
in personalized dialogues. Additionally, we propose TaciTree, a novel
hierarchical tree framework that structures conversation history into multiple
levels of summarization. Instead of brute-force searching all data, TaciTree
enables an efficient, level-based retrieval process where models refine their
search by progressively selecting relevant details. Our experiments demonstrate
that TaciTree significantly improves the ability of LLMs to reason over
long-term conversations with implicit contextual dependencies.
