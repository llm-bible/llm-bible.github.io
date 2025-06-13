---
layout: publication
title: 'A New Pipeline For Generating Instruction Dataset Via RAG And Self Fine-tuning'
authors: Chih-wei Song, Yu-kai Lee, Yin-te Tsai
conference: "Arxiv"
year: 2024
bibkey: song2024new
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.05911"}
tags: ['Agentic', 'Training Techniques', 'Tools', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Applications']
---
With the rapid development of large language models in recent years, there
has been an increasing demand for domain-specific Agents that can cater to the
unique needs of enterprises and organizations. Unlike general models, which
strive for broad coverage, these specialized Agents rely on focused datasets
tailored to their intended applications. This research proposes a pipeline that
leverages the power of LLMs and the Retrieval-Augmented Generation related
framework to construct high-quality instruction datasets for fine-tuning on
specific domains using custom document collections. By ingesting
domain-specific documents, the pipeline generates relevant and contextually
appropriate instructions, thus effectively creating a comprehensive dataset for
fine-tuning LLMs on the target domain. This approach overcomes the limitations
of traditional dataset creation methods, which often rely on manual curation or
web-scraping techniques that may introduce noise and irrelevant data. Notably,
our pipeline offers a dynamic solution that can quickly adapt to updates or
modifications in the domain-specific document collection, eliminating the need
for complete retraining. Additionally, it addresses the challenge of data
scarcity by enabling the generation of instruction datasets from a limited set
of initial documents, rendering it suitable for unpopular or specialized
domains where comprehensive datasets are scarce. As a case study, we apply this
approach to the domain of psychiatry, a field requiring specialized knowledge
and sensitive handling of patient information. The resulting fine-tuned LLM
demonstrates showcases the viability of the proposed approach and underscores
its potential for widespread adoption across various industries and domains
where tailored, accurate, and contextually relevant language models are
indispensable.
