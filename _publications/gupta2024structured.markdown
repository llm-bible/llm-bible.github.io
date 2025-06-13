---
layout: publication
title: 'STACKFEED: Structured Textual Actor-critic Knowledge Base Editing With Feedback'
authors: Naman Gupta, Shashank Kirtania, Priyanshu Gupta, Krishna Kariya, Sumit Gulwani, Arun Iyer, Suresh Parthasarathy, Arjun Radhakrishna, Sriram K. Rajamani, Gustavo Soares
conference: "Arxiv"
year: 2024
bibkey: gupta2024structured
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.10584"}
tags: ['Agentic', 'RAG', 'Tools', 'Reinforcement Learning']
---
Large Language Models (LLMs) often generate incorrect or outdated
information, especially in low-resource settings or when dealing with private
data. To address this, Retrieval-Augmented Generation (RAG) uses external
knowledge bases (KBs), but these can also suffer from inaccuracies. We
introduce STACKFEED, a novel Structured Textual Actor-Critic Knowledge base
editing with FEEDback approach that iteratively refines the KB based on expert
feedback using a multi-actor, centralized critic reinforcement learning
framework. Each document is assigned to an actor, modeled as a ReACT agent,
which performs structured edits based on document-specific targeted
instructions from a centralized critic. Experimental results show that
STACKFEED significantly improves KB quality and RAG system performance,
enhancing accuracy by up to 8% over baselines.
