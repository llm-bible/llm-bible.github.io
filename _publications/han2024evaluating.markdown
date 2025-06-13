---
layout: publication
title: 'Evaluating Llm-based Approaches To Legal Citation Prediction: Domain-specific Pre-training, Fine-tuning, Or RAG? A Benchmark And An Australian Law Case Study'
authors: Jiuzhou Han, Paul Burgess, Ehsan Shareghi
conference: "Arxiv"
year: 2024
bibkey: han2024evaluating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.06272"}
tags: ['Training Techniques', 'Reinforcement Learning', 'RAG', 'Merging', 'Pretraining Methods', 'Fine-Tuning', 'Prompting', 'Pre-Training']
---
Large Language Models (LLMs) have demonstrated strong potential across legal tasks, yet the problem of legal citation prediction remains under-explored. At its core, this task demands fine-grained contextual understanding and precise identification of relevant legislation or precedent. We introduce the AusLaw Citation Benchmark, a real-world dataset comprising 55k Australian legal instances and 18,677 unique citations which to the best of our knowledge is the first of its scale and scope. We then conduct a systematic benchmarking across a range of solutions: (i) standard prompting of both general and law-specialised LLMs, (ii) retrieval-only pipelines with both generic and domain-specific embeddings, (iii) supervised fine-tuning, and (iv) several hybrid strategies that combine LLMs with retrieval augmentation through query expansion, voting ensembles, or re-ranking. Results show that neither general nor law-specific LLMs suffice as stand-alone solutions, with performance near zero. Instruction tuning (of even a generic open-source LLM) on task-specific dataset is among the best performing solutions. We highlight that database granularity along with the type of embeddings play a critical role in retrieval-based approaches, with hybrid methods which utilise a trained re-ranker delivering the best results. Despite this, a performance gap of nearly 50% remains, underscoring the value of this challenging benchmark as a rigorous test-bed for future research in legal-domain.
