---
layout: publication
title: 'Memory-augmented Agent Training For Business Document Understanding'
authors: Jiale Liu, Yifan Zeng, Malte Højmark-bertelsen, Marie Normann Gadeberg, Huazheng Wang, Qingyun Wu
conference: "Arxiv"
year: 2024
bibkey: liu2024memory
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.15274"}
tags: ['Agentic', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG', 'Fine-Tuning', 'Prompting']
---
Traditional enterprises face significant challenges in processing business
documents, where tasks like extracting transport references from invoices
remain largely manual despite their crucial role in logistics operations. While
Large Language Models offer potential automation, their direct application to
specialized business domains often yields unsatisfactory results. We introduce
Matrix (Memory-Augmented agent Training through Reasoning and Iterative
eXploration), a novel paradigm that enables LLM agents to progressively build
domain expertise through experience-driven memory refinement and iterative
learning. To validate this approach, we collaborate with one of the world's
largest logistics companies to create a dataset of Universal Business Language
format invoice documents, focusing on the task of transport reference
extraction. Experiments demonstrate that Matrix outperforms prompting a single
LLM by 30.3%, vanilla LLM agent by 35.2%. We further analyze the metrics of the
optimized systems and observe that the agent system requires less API calls,
fewer costs and can analyze longer documents on average. Our methods establish
a new approach to transform general-purpose LLMs into specialized business
tools through systematic memory enhancement in document processing tasks.
