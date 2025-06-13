---
layout: publication
title: 'Br-taxqa-r: A Dataset For Question Answering With References For Brazilian Personal Income Tax Law, Including Case Law'
authors: Juvenal Domingos Júnior, Augusto Faria, E. Seiti De Oliveira, Erick De Brito, Matheus Teotonio, Andre Assumpção, Diedre Carmo, Roberto Lotufo, Jayr Pereira
conference: "Arxiv"
year: 2025
bibkey: júnior2025br
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.15916"}
tags: ['Model Architecture', 'Tools', 'Reinforcement Learning', 'RAG', 'GPT', 'Applications']
---
This paper presents BR-TaxQA-R, a novel dataset designed to support question answering with references in the context of Brazilian personal income tax law. The dataset contains 715 questions from the 2024 official Q\&A document published by Brazil's Internal Revenue Service, enriched with statutory norms and administrative rulings from the Conselho Administrativo de Recursos Fiscais (CARF). We implement a Retrieval-Augmented Generation (RAG) pipeline using OpenAI embeddings for searching and GPT-4o-mini for answer generation. We compare different text segmentation strategies and benchmark our system against commercial tools such as ChatGPT and Perplexity.ai using RAGAS-based metrics. Results show that our custom RAG pipeline outperforms commercial systems in Response Relevancy, indicating stronger alignment with user queries, while commercial models achieve higher scores in Factual Correctness and fluency. These findings highlight a trade-off between legally grounded generation and linguistic fluency. Crucially, we argue that human expert evaluation remains essential to ensure the legal validity of AI-generated answers in high-stakes domains such as taxation. BR-TaxQA-R is publicly available at https://huggingface.co/datasets/unicamp-dl/BR-TaxQA-R.
