---
layout: publication
title: 'General Llms As Instructors For Domain-specific Llms: A Sequential Fusion Method To Integrate Extraction And Editing'
authors: Xin Zhang, Tianjie Ju, Huijia Liang, Ying Fu, Qin Zhang
conference: "Arxiv"
year: 2024
bibkey: zhang2024general
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.15736"}
tags: ['Fine-Tuning', 'Tools', 'RAG', 'Reinforcement Learning', 'Merging', 'Training Techniques', 'Few-Shot']
---
The substantial interest in updating Large Language Models (LLMs) without
retraining from scratch is accompanied by several challenges. This is
particularly true when updating LLMs with datasets that necessitate
domain-expert reasoning across extensive texts, despite limited samples. We
termed the scenario as the Few-Shot Domain-Expert Reasoning for Updating LLMs
(FDoR-UL). Traditional methods such as Low-Rank Adaptation (LoRA) and Retrieval
Augmented Generation (RAG) are inadequate for addressing this critical issue,
particularly evident in our exploration of a specific medical dataset that
epitomizes the distinct needs of FDoR-UL. To tackle this challenge, we
introduce a Sequential Fusion method to integrate knowledge from complex
contexts into LLMs. This method employs a two-stage framework: initially
leveraging general LLMs to perform relation extraction for knowledge
acquisition from complex texts, followed by updating domain-specific LLMs
through Knowledge Editing (KE). Employing our method, domain-specific LLMs
achieved a 71.7% accuracy (an average gain of 39.1%) in question-answering
tasks. Furthermore, we expanded our evaluation to a novel economics-management
dataset we developed, where our method achieved a 75.0% accuracy (an average
gain of 45.0%). These findings underscore the effectiveness and flexibility of
our approach in FDoR-UL across various domains.
