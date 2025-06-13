---
layout: publication
title: 'Dialogue Benchmark Generation From Knowledge Graphs With Cost-effective Retrieval-augmented Llms'
authors: Reham Omar, Omij Mangukiya, Essam Mansour
conference: "Arxiv"
year: 2025
bibkey: omar2025dialogue
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.09928"}
tags: ['Tools', 'GPT', 'Applications', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques']
---
Dialogue benchmarks are crucial in training and evaluating chatbots engaging
in domain-specific conversations. Knowledge graphs (KGs) represent semantically
rich and well-organized data spanning various domains, such as DBLP, DBpedia,
and YAGO. Traditionally, dialogue benchmarks have been manually created from
documents, neglecting the potential of KGs in automating this process. Some
question-answering benchmarks are automatically generated using extensive
preprocessing from KGs, but they do not support dialogue generation. This paper
introduces Chatty-Gen, a novel multi-stage retrieval-augmented generation
platform for automatically generating high-quality dialogue benchmarks tailored
to a specific domain using a KG. Chatty-Gen decomposes the generation process
into manageable stages and uses assertion rules for automatic validation
between stages. Our approach enables control over intermediate results to
prevent time-consuming restarts due to hallucinations. It also reduces reliance
on costly and more powerful commercial LLMs. Chatty-Gen eliminates upfront
processing of the entire KG using efficient query-based retrieval to find
representative subgraphs based on the dialogue context. Our experiments with
several real and large KGs demonstrate that Chatty-Gen significantly
outperforms state-of-the-art systems and ensures consistent model and system
performance across multiple LLMs of diverse capabilities, such as GPT-4o,
Gemini 1.5, Llama 3, and Mistral.
