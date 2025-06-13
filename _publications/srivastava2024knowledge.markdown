---
layout: publication
title: 'Knowledge Planning In Large Language Models For Domain-aligned Counseling Summarization'
authors: Aseem Srivastava, Smriti Joshi, Tanmoy Chakraborty, Md Shad Akhtar
conference: "Arxiv"
year: 2024
bibkey: srivastava2024knowledge
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.14907'}
tags: ['RAG', 'Applications', 'Tools']
---
In mental health counseling, condensing dialogues into concise and relevant
summaries (aka counseling notes) holds pivotal significance. Large Language
Models (LLMs) exhibit remarkable capabilities in various generative tasks;
however, their adaptation to domain-specific intricacies remains challenging,
especially within mental health contexts. Unlike standard LLMs, mental health
experts first plan to apply domain knowledge in writing summaries. Our work
enhances LLMs' ability by introducing a novel planning engine to orchestrate
structuring knowledge alignment. To achieve high-order planning, we divide
knowledge encapsulation into two major phases: (i) holding dialogue structure
and (ii) incorporating domain-specific knowledge. We employ a planning engine
on Llama-2, resulting in a novel framework, PIECE. Our proposed system employs
knowledge filtering-cum-scaffolding to encapsulate domain knowledge.
Additionally, PIECE leverages sheaf convolution learning to enhance its
understanding of the dialogue's structural nuances. We compare PIECE with 14
baseline methods and observe a significant improvement across ROUGE and Bleurt
scores. Further, expert evaluation and analyses validate the generation quality
to be effective, sometimes even surpassing the gold standard. We further
benchmark PIECE with other LLMs and report improvement, including Llama-2
(+2.72%), Mistral (+2.04%), and Zephyr (+1.59%), to justify the
generalizability of the planning engine.
