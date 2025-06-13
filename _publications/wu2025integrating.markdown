---
layout: publication
title: 'Integrating Chain-of-thought And Retrieval Augmented Generation Enhances Rare Disease Diagnosis From Clinical Notes'
authors: Da Wu, Zhanliang Wang, Quan Nguyen, Kai Wang
conference: "Arxiv"
year: 2025
bibkey: wu2025integrating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.12286"}
tags: ['GPT', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Prompting']
---
Background: Several studies show that large language models (LLMs) struggle
with phenotype-driven gene prioritization for rare diseases. These studies
typically use Human Phenotype Ontology (HPO) terms to prompt foundation models
like GPT and LLaMA to predict candidate genes. However, in real-world settings,
foundation models are not optimized for domain-specific tasks like clinical
diagnosis, yet inputs are unstructured clinical notes rather than standardized
terms. How LLMs can be instructed to predict candidate genes or disease
diagnosis from unstructured clinical notes remains a major challenge. Methods:
We introduce RAG-driven CoT and CoT-driven RAG, two methods that combine
Chain-of-Thought (CoT) and Retrieval Augmented Generation (RAG) to analyze
clinical notes. A five-question CoT protocol mimics expert reasoning, while RAG
retrieves data from sources like HPO and OMIM (Online Mendelian Inheritance in
Man). We evaluated these approaches on rare disease datasets, including 5,980
Phenopacket-derived notes, 255 literature-based narratives, and 220 in-house
clinical notes from Childrens Hospital of Philadelphia. Results: We found that
recent foundations models, including Llama 3.3-70B-Instruct and
DeepSeek-R1-Distill-Llama-70B, outperformed earlier versions such as Llama 2
and GPT-3.5. We also showed that RAG-driven CoT and CoT-driven RAG both
outperform foundation models in candidate gene prioritization from clinical
notes; in particular, both methods with DeepSeek backbone resulted in a top-10
gene accuracy of over 40% on Phenopacket-derived clinical notes. RAG-driven CoT
works better for high-quality notes, where early retrieval can anchor the
subsequent reasoning steps in domain-specific evidence, while CoT-driven RAG
has advantage when processing lengthy and noisy notes.
