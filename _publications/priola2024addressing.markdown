---
layout: publication
title: 'Addressing Hallucinations With RAG And NMISS In Italian Healthcare LLM Chatbots'
authors: Maria Paola Priola
conference: "Arxiv"
year: 2024
bibkey: priola2024addressing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.04235"}
tags: ['Model Architecture', 'Tools', 'Reinforcement Learning', 'RAG', 'GPT', 'Applications']
---
I combine detection and mitigation techniques to addresses hallucinations in
Large Language Models (LLMs). Mitigation is achieved in a question-answering
Retrieval-Augmented Generation (RAG) framework while detection is obtained by
introducing the Negative Missing Information Scoring System (NMISS), which
accounts for contextual relevance in responses. While RAG mitigates
hallucinations by grounding answers in external data, NMISS refines the
evaluation by identifying cases where traditional metrics incorrectly flag
contextually accurate responses as hallucinations. I use Italian health news
articles as context to evaluate LLM performance. Results show that Gemma2 and
GPT-4 outperform the other models, with GPT-4 producing answers closely aligned
with reference responses. Mid-tier models, such as Llama2, Llama3, and Mistral
benefit significantly from NMISS, highlighting their ability to provide richer
contextual information. This combined approach offers new insights into the
reduction and more accurate assessment of hallucinations in LLMs, with
applications in real-world healthcare tasks and other domains.
