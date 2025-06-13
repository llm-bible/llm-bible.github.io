---
layout: publication
title: 'Transitgpt: A Generative Ai-based Framework For Interacting With GTFS Data Using Large Language Models'
authors: Saipraneeth Devunuri, Lewis Lehe
conference: "Arxiv"
year: 2024
bibkey: devunuri2024generative
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.06831"}
tags: ['Fine-Tuning', 'Tools', 'GPT', 'RAG', 'Model Architecture', 'Training Techniques', 'Pretraining Methods', 'Prompting']
---
This paper introduces a framework that leverages Large Language Models (LLMs)
to answer natural language queries about General Transit Feed Specification
(GTFS) data. The framework is implemented in a chatbot called TransitGPT with
open-source code. TransitGPT works by guiding LLMs to generate Python code that
extracts and manipulates GTFS data relevant to a query, which is then executed
on a server where the GTFS feed is stored. It can accomplish a wide range of
tasks, including data retrieval, calculations, and interactive visualizations,
without requiring users to have extensive knowledge of GTFS or programming. The
LLMs that produce the code are guided entirely by prompts, without fine-tuning
or access to the actual GTFS feeds. We evaluate TransitGPT using GPT-4o and
Claude-3.5-Sonnet LLMs on a benchmark dataset of 100 tasks, to demonstrate its
effectiveness and versatility. The results show that TransitGPT can
significantly enhance the accessibility and usability of transit data.
