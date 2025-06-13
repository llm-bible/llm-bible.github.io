---
layout: publication
title: 'Medeir: A Specialized Medical Embedding Model For Enhanced Information Retrieval'
authors: Anand Selvadurai, Jasheen Shaik, Girish Chandrasekar, Shriradhakrishnan Balamurugan, Eswara Reddy
conference: "Arxiv"
year: 2025
bibkey: selvadurai2025specialized
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.13482'}
tags: ['RAG', 'Training Techniques', 'Applications', 'Fine-Tuning', 'Reinforcement Learning', 'Tokenization', 'Pretraining Methods']
---
Embedding models have become essential for retrieval-augmented generation (RAG) tasks, semantic clustering, and text re-ranking. But despite their growing use, many of these come with notable limitations. For example, Jina fails to capture the semantic content of medical documents, while models such as MiniLM often perform poorly on long-form documents. Domain-adapted models, while specialized, often underperform in general-purpose tasks, reducing their overall applicability. General-domain tokenizers often misinterpret medical vocabulary. The limitations of current embedding models, whether in tokenization accuracy, domain comprehension, or handling long sequences, highlight the need for more versatile solutions. In this work, we present MedEIR, a novel embedding model and tokenizer jointly optimized for both medical and general NLP tasks, incorporating ALiBi-based long-context processing to support sequences of up to 8,192 tokens. MedEIR was pre-trained on only 6 billion tokens, significantly fewer than Jina's, followed by fine-tuning on 3 million sentence pairs. MedEIR consistently outperforms Jina V2 and MiniLM across MTEB benchmarks, achieving top scores on ArguAna (55.24), NFCorpus (38.44), MedicalQARetrieval (74.25), SciFact (72.04), and TRECCOVID (79.56). These results highlight the potential of MedEIR as a highly effective embedding model, demonstrating strong performance across both general-purpose and domain-specific tasks and outperforming existing models on multiple benchmarks.
