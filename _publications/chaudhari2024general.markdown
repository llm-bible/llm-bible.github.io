---
layout: publication
title: Phantom General Trigger Attacks On Retrieval Augmented Language Generation
authors: Chaudhari Harsh, Severi Giorgio, Abascal John, Jagielski Matthew, Choquette-choo Christopher A., Nasr Milad, Nita-rotaru Cristina, Oprea Alina
conference: "Arxiv"
year: 2024
bibkey: chaudhari2024general
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.20485"}
tags: ['Applications', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Security', 'Tools', 'Training Techniques']
---
Retrieval Augmented Generation (RAG) expands the capabilities of modern large language models (LLMs) in chatbot applications enabling developers to adapt and personalize the LLM output without expensive training or fine-tuning. RAG systems use an external knowledge database to retrieve the most relevant documents for a given query providing this context to the LLM generator. While RAG achieves impressive utility in many applications its adoption to enable personalized generative models introduces new security risks. In this work we propose new attack surfaces for an adversary to compromise a victims RAG system by injecting a single malicious document in its knowledge database. We design Phantom general two-step attack framework against RAG augmented LLMs. The first step involves crafting a poisoned document designed to be retrieved by the RAG system within the top-k results only when an adversarial trigger a specific sequence of words acting as backdoor is present in the victims queries. In the second step a specially crafted adversarial string within the poisoned document triggers various adversarial attacks in the LLM generator including denial of service reputation damage privacy violations and harmful behaviors. We demonstrate our attacks on multiple LLM architectures including Gemma Vicuna and Llama.
