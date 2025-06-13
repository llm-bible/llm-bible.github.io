---
layout: publication
title: 'Sql-palm: Improved Large Language Model Adaptation For Text-to-sql (extended)'
authors: Ruoxi Sun, Sercan Ö. Arik, Alex Muzio, Lesly Miculicich, Satya Gundabathula, Pengcheng Yin, Hanjun Dai, Hootan Nakhost, Rajarishi Sinha, Zifeng Wang, Tomas Pfister
conference: "Arxiv"
year: 2023
bibkey: sun2023sql
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.00739"}
tags: ['Fine-Tuning', 'Tools', 'RAG', 'Training Techniques', 'Pretraining Methods', 'Few-Shot', 'Prompting', 'In-Context Learning']
---
Text-to-SQL, the process of translating natural language into Structured
Query Language (SQL), represents a transformative application of large language
models (LLMs), potentially revolutionizing how humans interact with data. This
paper introduces the SQL-PaLM framework, a comprehensive solution for
understanding and enhancing Text-to-SQL using LLMs, using in the learning
regimes of few-shot prompting and instruction fine-tuning. With few-shot
prompting, we explore the effectiveness of consistency decoding with
execution-based error filtering. With instruction fine-tuning, we delve deep in
understanding the critical paradigms that influence the performance of tuned
LLMs. In particular, we investigate how performance can be improved through
expanded training data coverage and diversity, synthetic data augmentation, and
integrating query-specific database content. We propose a test-time selection
method to further refine accuracy by integrating SQL outputs from multiple
paradigms with execution feedback as guidance. Additionally, we tackle the
practical challenge of navigating intricate databases with a significant number
of tables and columns, proposing efficient techniques for accurately selecting
relevant database elements to enhance Text-to-SQL performance. Our holistic
approach yields substantial advancements in Text-to-SQL, as demonstrated on two
key public benchmarks, Spider and BIRD. Through comprehensive ablations and
error analyses, we shed light on the strengths and weaknesses of our framework,
offering valuable insights into Text-to-SQL's future work.
