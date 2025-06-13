---
layout: publication
title: 'A Schema-guided Reason-while-retrieve Framework For Reasoning On Scene Graphs With Large-language-models (llms)'
authors: Yiye Chen, Harpreet Sawhney, Nicholas Gydé, Yanan Jian, Jack Saunders, Patricio Vela, Ben Lundell
conference: "Arxiv"
year: 2025
bibkey: chen2025schema
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.03450"}
tags: ['Agentic', 'Tools', 'Model Architecture', 'Attention Mechanism', 'Few-Shot', 'Prompting']
---
Scene graphs have emerged as a structured and serializable environment
representation for grounded spatial reasoning with Large Language Models
(LLMs). In this work, we propose SG-RwR, a Schema-Guided Retrieve-while-Reason
framework for reasoning and planning with scene graphs. Our approach employs
two cooperative, code-writing LLM agents: a (1) Reasoner for task planning and
information queries generation, and a (2) Retriever for extracting
corresponding graph information following the queries. Two agents collaborate
iteratively, enabling sequential reasoning and adaptive attention to graph
information. Unlike prior works, both agents are prompted only with the scene
graph schema rather than the full graph data, which reduces the hallucination
by limiting input tokens, and drives the Reasoner to generate reasoning trace
abstractly.Following the trace, the Retriever programmatically query the scene
graph data based on the schema understanding, allowing dynamic and global
attention on the graph that enhances alignment between reasoning and retrieval.
Through experiments in multiple simulation environments, we show that our
framework surpasses existing LLM-based approaches in numerical Q\&A and
planning tasks, and can benefit from task-level few-shot examples, even in the
absence of agent-level demonstrations. Project code will be released.
