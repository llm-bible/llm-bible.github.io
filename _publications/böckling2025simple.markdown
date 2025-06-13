---
layout: publication
title: 'Walk&retrieve: Simple Yet Effective Zero-shot Retrieval-augmented Generation Via Knowledge Graph Walks'
authors: Martin Böckling, Heiko Paulheim, Andreea Iana
conference: "Arxiv"
year: 2025
bibkey: böckling2025simple
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.16849'}
tags: ['RAG', 'Efficiency and Optimization', 'Training Techniques', 'Applications', 'Tools', 'Fine-Tuning', 'Pretraining Methods']
---
Large Language Models (LLMs) have showcased impressive reasoning abilities, but often suffer from hallucinations or outdated knowledge. Knowledge Graph (KG)-based Retrieval-Augmented Generation (RAG) remedies these shortcomings by grounding LLM responses in structured external information from a knowledge base. However, many KG-based RAG approaches struggle with (i) aligning KG and textual representations, (ii) balancing retrieval accuracy and efficiency, and (iii) adapting to dynamically updated KGs. In this work, we introduce Walk&Retrieve, a simple yet effective KG-based framework that leverages walk-based graph traversal and knowledge verbalization for corpus generation for zero-shot RAG. Built around efficient KG walks, our method does not require fine-tuning on domain-specific data, enabling seamless adaptation to KG updates, reducing computational overhead, and allowing integration with any off-the-shelf backbone LLM. Despite its simplicity, Walk&Retrieve performs competitively, often outperforming existing RAG systems in response accuracy and hallucination reduction. Moreover, it demonstrates lower query latency and robust scalability to large KGs, highlighting the potential of lightweight retrieval strategies as strong baselines for future RAG research.
