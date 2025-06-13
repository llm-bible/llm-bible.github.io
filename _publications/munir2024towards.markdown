---
layout: publication
title: 'Towards Evaluating Large Language Models For Graph Query Generation'
authors: Siraj Munir, Alessandro Aldini
conference: "Arxiv"
year: 2024
bibkey: munir2024towards
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.08449'}
tags: ['Agentic', 'Few-Shot', 'RAG', 'Model Architecture', 'Tools', 'GPT', 'Merging', 'Prompting', 'Applications']
---
Large Language Models (LLMs) are revolutionizing the landscape of Generative
Artificial Intelligence (GenAI), with innovative LLM-backed solutions emerging
rapidly. However, when applied to database technologies, specifically query
generation for graph databases and Knowledge Graphs (KGs), LLMs still face
significant challenges. While research on LLM-driven query generation for
Structured Query Language (SQL) exists, similar systems for graph databases
remain underdeveloped. This paper presents a comparative study addressing the
challenge of generating Cypher queries a powerful language for interacting with
graph databases using open-access LLMs. We rigorously evaluate several LLM
agents (OpenAI ChatGPT 4o, Claude Sonnet 3.5, Google Gemini Pro 1.5, and a
locally deployed Llama 3.1 8B) using a designed few-shot learning prompt and
Retrieval Augmented Generation (RAG) backed by Chain-of-Thoughts (CoT)
reasoning. Our empirical analysis of query generation accuracy reveals that
Claude Sonnet 3.5 outperforms its counterparts in this specific domain.
Further, we highlight promising future research directions to address the
identified limitations and advance LLM-driven query generation for graph
databases.
