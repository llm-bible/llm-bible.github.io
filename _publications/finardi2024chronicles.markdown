---
layout: publication
title: The Chronicles of RAG The Retriever the Chunk and the Generator
authors: Finardi Paulo, Avila Leonardo, Castaldoni Rodrigo, Gengo Pedro, Larcher Celio, Piau Marcos, Costa Pablo, Caridá Vinicius
conference: "Arxiv"
year: 2024
bibkey: finardi2024chronicles
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.07883"}
tags: ['Applications', 'Efficiency And Optimization', 'GPT', 'Language Modeling', 'Model Architecture', 'RAG']
---
Retrieval Augmented Generation (RAG) has become one of the most popular paradigms for enabling LLMs to access external data and also as a mechanism for grounding to mitigate against hallucinations. When implementing RAG you can face several challenges like effective integration of retrieval models efficient representation learning data diversity computational efficiency optimization evaluation and quality of text generation. Given all these challenges every day a new technique to improve RAG appears making it unfeasible to experiment with all combinations for your problem. In this context this paper presents good practices to implement optimize and evaluate RAG for the Brazilian Portuguese language focusing on the establishment of a simple pipeline for inference and experiments. We explored a diverse set of methods to answer questions about the first Harry Potter book. To generate the answers we used the OpenAIs gpt-4 gpt-4-1106-preview gpt-3.5-turbo-1106 and Googles Gemini Pro. Focusing on the quality of the retriever our approach achieved an improvement of MRR@10 by 35.4 compared to the baseline. When optimizing the input size in the application we observed that it is possible to further enhance it by 2.4. Finally we present the complete architecture of the RAG with our recommendations. As result we moved from a baseline of 57.88 to a maximum relative score of 98.61.
